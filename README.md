# Machine Learning with Ruby [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="ruby.jpg" align="right" width="100px" height="100px" />][ruby]

> Useful resources for machine learning in [Ruby][ruby]

This curated list comprises [_awesome_](https://github.com/sindresorhus/awesome/blob/master/awesome.md)
resources, libraries, information sources about Machine Learning with the [Ruby programming language](ruby).

This list comes from our day to day work on ML Applications.

Our main goal is to promote Ruby as a tool for Machine Learning Tasks. Your help,
suggestions and contributions are welcome! We kindly ask you to study
the [Contribution](#contributing) section. Follow us on [Twitter](https://twitter.com/RubyNLP)
and please spread the word using the `#RubyML` hash tag!



<!-- nodoc -->
## Contents

<!-- toc -->

- [Machine Learning Libraries](#machine-learning-libraries)
- [Articles, Posts, Talks, and Presentations](#articles-posts-talks-and-presentations)
- [Projects and Code Examples](#projects-and-code-examples)
- [Books](#books)
- [Community](#community)
- [Needs your Help!](#needs-your-help)
- [Related Resources](#related-resources)
- [Contributing](#contributing)
- [License](#license)

<!-- tocstop -->

<!-- doc -->

## Machine Learning Libraries

[Machine Learning](https://en.wikipedia.org/wiki/Machine_learning) Algorithms
in pure Ruby or written in other programming languages with appropriate bindings
for Ruby.

- [rb-libsvm](https://github.com/febeling/rb-libsvm) -
  Support Vector Machines with Ruby.
- [weka-jruby](https://github.com/paulgoetze/weka-jruby) -
  JRuby bindings for Weka, different ML algorithms implemented through Weka.
- [decisiontree](https://github.com/igrigorik/decisiontree) -
  Decision Tree ID3 Algorithm in pure Ruby
  <sup>[[post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>.
- [rtimbl](https://github.com/maspwr/rtimbl) -
  Memory based learners from the Timbl framework.
- [classifier-reborn](https://github.com/jekyll/classifier-reborn) -
  General classifier module to allow Bayesian and other types of classifications.
- [lda-ruby](https://github.com/ealdent/lda-ruby) -
  Ruby implementation of the [LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation)
  (Latent Dirichlet Allocation) for automatic Topic Modelling and Document Clustering.
- [liblinear-ruby-swig](https://github.com/tomz/liblinear-ruby-swig) -
  Ruby interface to LIBLINEAR (much more efficient than LIBSVM for text classification).
- [linnaeus](https://github.com/djcp/linnaeus) -
  Redis-backed Bayesian classifier.
- [maxent_string_classifier](https://github.com/mccraigmccraig/maxent_string_classifier) -
  JRuby maximum entropy classifier for string data, based on the OpenNLP Maxent framework.
- [naive_bayes](https://github.com/reddavis/Naive-Bayes) -
  Simple Naive Bayes classifier.
- [nbayes](https://github.com/oasic/nbayes) -
  Full-featured, Ruby implementation of Naive Bayes.
- [omnicat](https://github.com/mustafaturan/omnicat) -
  Generalized rack framework for text classifications.
- [omnicat-bayes](https://github.com/mustafaturan/omnicat-bayes) -
  Naive Bayes text classification implementation as an OmniCat classifier strategy.
- [ruby-fann](https://github.com/tangledpath/ruby-fann) -
  Ruby bindings to the [Fast Artificial Neural Network Library (FANN)](http://leenissen.dk/fann/wp/).
- [scoruby](https://github.com/asafschers/scoruby) -
  Ruby scoring API for [PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html) (Predictive Model Markup Language).

## Articles, Posts, Talks, and Presentations

- 2017
  - _Scientific Computing on JRuby_ by [Prasun Anand](https://twitter.com/prasun_anand)
    <sup>[[slides](https://www.slideshare.net/PrasunAnand2/fosdem2017-scientific-computing-on-jruby) |
    [video](https://ftp.fau.de/fosdem/2017/K.4.201/ruby_scientific_computing_on_jruby.mp4) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computing-on-jruby) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computation-on-jruby)]</sup>
  - _Unicode Normalization in Ruby_ by [Starr Horne](https://twitter.com/starrhorne)
    <sup>[[post](http://blog.honeybadger.io/ruby_unicode_normalization/)]</sup>
- 2016
  - _Practical Machine Learning with Ruby_ by [Jordan Hudgens](https://twitter.com/jordanhudgens)
    <sup>[[tutorial](https://www.crondose.com/2016/12/practical-machine-learning-ruby/)]</sup>
  - _Quickly Create a Telegram Bot in Ruby_ by [Ardian Haxha](https://twitter.com/ArdianHaxha)
    <sup>[[tutorial](https://www.sitepoint.com/quickly-create-a-telegram-bot-in-ruby/)]</sup>
  - _Deep Learning: An Introduction for Ruby Developers_ by [Geoffrey Litt](https://twitter.com/geoffreylitt)
    <sup>[[slides](https://speakerdeck.com/geoffreylitt/deep-learning-an-introduction-for-ruby-developers)]</sup>
  - _How I made a pure-Ruby word2vec program more than 3x faster_ by [Kei Sawada](https://twitter.com/remore)
    <sup>[[slides](https://speakerdeck.com/remore/how-i-made-a-pure-ruby-word2vec-program-more-than-3x-faster)]</sup>
  - _Dōmo arigatō, Mr. Roboto: Machine Learning with Ruby_ by [Eric Weinstein](https://twitter.com/ericqweinstein)
    <sup>[[slides](https://speakerdeck.com/ericqweinstein/domo-arigato-mr-roboto-machine-learning-with-ruby) | [video](https://www.youtube.com/watch?v=T1nFQ49TyeA)]</sup>
- 2015
  - _N-gram Analysis for Fun and Profit_ by [Jesus Castello](https://github.com/matugm)
    <sup>[[tutorial](http://www.blackbytes.info/2015/09/ngram-analysis-ruby/)]</sup>
  - _Machine Learning made simple with Ruby_ by [Lorenzo Masini](https://github.com/rugginoso)
    <sup>[[tutorial](https://www.leanpanda.com/blog/2015/08/24/machine-learning-automatic-classification/)]</sup>
  - _Using Ruby Machine Learning to Find Paris Hilton Quotes_ by [Rick Carlino](https://github.com/RickCarlino)
    <sup>[[tutorial](https://web-beta.archive.org/web/20160515115739/http://datamelon.io/blog/2015/using-ruby-machine-learning-id-paris-hilton-quotes.html)]</sup>
  - _Exploring Natural Language Processing in Ruby_ by [Kevin Dias](https://github.com/diasks2)
    <sup>[[slides](https://www.slideshare.net/diasks2/exploring-natural-language-processing-in-ruby)]</sup>
  - _Machine Learning made simple with Ruby_ by [Lorenzo Masini](https://twitter.com/rugginoso)
    <sup>[[post](https://www.leanpanda.com/blog/2015/08/24/machine-learning-automatic-classification/)]</sup>
  - _Practical Data Science in Ruby_ by Bobby Grayson
    <sup>[[slides](http://slides.com/bobbygrayson/p#/)]</sup>
- 2014
  - _Natural Language Parsing with Ruby_ by [Glauco Custódio](https://github.com/glaucocustodio)
    <sup>[[tutorial](http://glaucocustodio.github.io/2014/11/10/natural-language-parsing-with-ruby/)]</sup>
  - _Demystifying Data Science: Analyzing Conference Talks with Rails and Ngrams_ by
    [Todd Schneider](https://github.com/toddwschneider)
    <sup>[[video](https://www.youtube.com/watch?v=2ZDCxwB29Bg) | [code](https://github.com/Genius/abstractogram)]</sup>
  - _Natural Language Processing with Ruby_ by [Konstantin Tennhard](https://github.com/t6d)
    <sup>[[video](https://www.youtube.com/watch?v=5u86qVh8r0M) | [video](https://www.youtube.com/watch?v=oFmy_QBQ5DU) |
    [video](https://www.youtube.com/watch?v=sPkeeWnsMn0) |
    [slides](http://euruko2013.org/speakers/presentations/natural_language_processing_with_ruby_and_opennlp-tennhard.pdf)]</sup>
- 2013
  - _How to parse 'go' - Natural Language Processing in Ruby_ by
    [Tom Cartwright](https://twitter.com/tomcartwrightuk)
    <sup>[[slides](https://www.slideshare.net/TomCartwright/natual-language-processing-in-ruby) |
    [video](https://skillsmatter.com/skillscasts/4883-how-to-parse-go)]</sup>
  - _Natural Language Processing in Ruby_ by [Brandon Black](https://github.com/brandonblack)
    <sup>[[slides](https://speakerdeck.com/brandonblack/natural-language-processing-in-ruby) |
    [video](http://confreaks.tv/videos/railsconf2013-natural-language-processing-with-ruby)]</sup>
  - _Natural Language Processing with Ruby: n-grams_ by [Nathan Kleyn](https://github.com/nathankleyn)
    <sup>[[tutorial](https://www.sitepoint.com/natural-language-processing-ruby-n-grams/) |
    [code](https://github.com/nathankleyn/ruby_nlp)]</sup>
  - _Seeking Lovecraft, Part 1: An introduction to NLP and the Treat Gem_ by
    [Robert Qualls](https://github.com/rlqualls)
    <sup>[[tutorial](https://www.sitepoint.com/seeking-lovecraft-part-1-an-introduction-to-nlp-and-the-treat-gem/)]</sup>
- 2012
  - _Machine Learning with Ruby, Part One_ by [Vasily Vasinov](https://twitter.com/vasinov)
    <sup>[[tutorial](http://www.vasinov.com/blog/machine-learning-with-ruby-part-one/)]</sup>
- 2011
  - _Ruby one-liners_ by [Benoit Hamelin](https://twitter.com/benoithamelin)
    <sup>[[post](http://benoithamelin.tumblr.com/ruby1line)]</sup>
  - _Clustering in Ruby_ by [Colin Drake](https://twitter.com/colinfdrake)
    <sup>[[post](https://colindrake.me/2011/05/28/clustering-in-ruby/)]</sup>
- 2010
  - _bayes_motel – Bayesian classification for Ruby_ by [Mike Perham](https://twitter.com/mperham)
    <sup>[[post](http://www.mikeperham.com/2010/04/28/bayes_motel-bayesian-classification-for-ruby/)]</sup>
- 2009
  - _Porting the UEA-Lite Stemmer to Ruby_ by [Jason Adams](https://twitter.com/ealdent)
    <sup>[[post](https://ealdent.wordpress.com/2009/07/16/porting-the-uea-lite-stemmer-to-ruby/)]</sup>
  - _NLP Resources for Ruby_ by [Jason Adams](https://twitter.com/ealdent)
    <sup>[[post](https://ealdent.wordpress.com/2009/09/13/nlp-resources-for-ruby/)]</sup>
- 2008
  - _Support Vector Machines (SVM) in Ruby_ by [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[post](https://www.igvita.com/2008/01/07/support-vector-machines-svm-in-ruby/)]</sup>
  - _Practical text classification with Ruby_ by [Gleicon Moraes](https://twitter.com/gleicon)
    <sup>[[post](https://zenmachine.wordpress.com/practical-text-classification-with-ruby/) |
    [code](https://github.com/gleicon/zenmachine)]</sup>
- 2007
  - _Decision Tree Learning in Ruby_ by [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>

## Projects and Code Examples

- [Going the Distance](https://github.com/schneems/going_the_distance) -
  Implementations of various distance algorithms with example calculations.
- [Named entity recognition with Stanford NER and Ruby](https://github.com/mblongii/ruby-ner) -
  NER Examples in Ruby and Java with some [explanations](https://web.archive.org/web/20120722225402/http://mblongii.com/2012/04/15/named-entity-recognition-with-stanford-ner-and-ruby/).
- [Words Counted](http://rubywordcount.com/) -
  examples of customizable word statistics powered by
  [words_counted](https://github.com/abitdodgy/words_counted).

## Books

-  [Kirk, Matthew](https://twitter.com/mjkirk).
   _Thoughtful Machine Learning: A Test-Driven Approach_
   O'Reilly, 2014.
   <sup>[[Amazon](https://www.amazon.com/Thoughtful-Machine-Learning-Test-Driven-Approach/dp/1449374069) |
         [code](https://github.com/thoughtfulml/examples)]</sup>

## Community

- [Reddit](https://www.reddit.com/r/LanguageTechnology/search?q=ruby&restrict_sr=on)
- [Stack Overflow](http://stackoverflow.com/search?q=%5Bnlp%5D+and+%5Bruby%5D)
- [Twitter](https://twitter.com/search?q=Ruby%20NLP%20%23ruby%20OR%20%23nlproc%20OR%20%23rubynlp%20OR%20%23nlp&src=typd&lang=en)

## Needs your Help!

All projects in this section are really important for the community but need
more attention. Please if you have spare time and dedication spend some hours
on the code here.

## Related Resources

- [Awesome Ruby](https://github.com/markets/awesome-ruby#natural-language-processing) -
  Among other awesome items a short list of NLP related projects.
- [Ruby NLP](https://github.com/diasks2/ruby-nlp) -
  State-of-Art collection of Ruby libraries for NLP.
- [Speech and Natural Language Processing](https://github.com/edobashira/speech-language-processing) -
  General List of NLP related resources (mostly not for Ruby programmers).
- [Scientific Ruby](http://sciruby.com/) -
  Linear Algebra, Visualization and Scientific Computing for Ruby.
- [iRuby](https://github.com/SciRuby/iruby) - IRuby kernel for Jupyter (formelly IPython).
- [Kiba](https://github.com/thbar/kiba) -
  Lightweight [ETL](https://en.wikipedia.org/wiki/Extract,_transform,_load) (Extract, Transform, Load) pipeline.
- [Awesome OCR](https://github.com/kba/awesome-ocr) -
  Multitude of OCR (Optical Character Recognition) resources.
- [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) -
  Machine Learning with TensorFlow libraries.
- [rb-gsl](https://github.com/SciRuby/rb-gsl) -
  Ruby interface to the [GNU Scientific Library](https://www.gnu.org/software/gsl/).
- [The Definitive Guide to Ruby's C API](https://silverhammermba.github.io/emberb/) -
  Modern Reference and Tutorial on Embedding and Extending Ruby using C programming language.

## Contributing

We are very glad to see you in this section and highly appreciate any help!

But we also take care about the quality of this list. If you want to contribute
please:

- agree that your work will be published under the terms of the `CC0` license;
- carefully read the [Contribution Guidelines][contributing].

Some of the open tasks for contributors are listed in the [todo file][todo].
You may want to start there.

## License

[![Creative Commons Zero 1.0](http://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/) `Awesome ML with Ruby` by [Andrei Beliankou](https://github.com/arbox) and
[Contributors](https://github.com/arbox/machine-learning-with-ruby/graphs/contributors).

To the extent possible under law, the person who associated CC0 with
`Awesome ML with Ruby` has waived all copyright and related or neighboring rights
to `Awesome ML with Ruby`.

You should have received a copy of the CC0 legalcode along with this
work. If not, see <https://creativecommons.org/publicdomain/zero/1.0/>.

<!--- Links --->
[ruby]: https://www.ruby-lang.org/en/
[motivation]: https://github.com/arbox/nlp-with-ruby/blob/master/motivation.md
[contributing]: https://github.com/arbox/nlp-with-ruby/blob/master/CONTRIBUTING.md
[todo]: https://github.com/arbox/nlp-with-ruby/blob/master/todo.md
[faq]: https://github.com/arbox/nlp-with-ruby/blob/master/FAQ.md
