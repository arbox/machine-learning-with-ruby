require 'yaml'
require 'rake/clean'
CLEAN.include '*.json'

namespace :test do
  task :links2 do
    require 'awesome_bot'
    content = File.read('README.md')
    result = AwesomeBot.check(content)
    puts result.success(nil) ? ':)' : ':('
  end

  CMD_STRING = YAML.load_file('.travis.yml')['script']
  desc 'Test links with AwesomeBot'
  task :links do
    system(CMD_STRING)
  end
end

desc 'Regenerate the TOC.'
task :toc do
  `node_modules/markdown-toc/cli.js -i README.md`
end

desc 'Create the www sources.'
task :webgen do
  DOCS_DIR = 'www/_mkdocs_source/'
  SRC_FILES = ['README.md', 'FAQ.md', 'motivation.md']
  SRC_FILES.each do |name|
    nodoc(name)
  end
end

def nodoc(file)
  lines = File.readlines(file)

  if file == 'README.md'
    file = 'index.md'
  end
  File.open(DOCS_DIR + file, 'w') do |file|
    lines.each do |line|
      unless line =~ /<!-- nodoc/ .. line =~ /<!-- doc/
        file.write(line)
      end
    end
  end
end

desc 'Upload files to the web server.'
task :release => :webgen do
  `cd www && mkdocs build`
  `cd www/_site && git add . && git commit -m "Release: $(date +%F-%H:%M)"`
end
