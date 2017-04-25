[[RubyNLP](https://github.com/arbox/nlp-with-ruby) | [RubyDataScience](https://github.com/arbox/data-science-with-ruby) | [RubyInterop](https://github.com/arbox/ruby-interoperability) ]

# Machine Learning with Ruby [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="ruby.jpg" align="right" width="100px" height="100px" />][ruby]

> Useful resources for machine learning in [Ruby][ruby]


This curated list comprises [_awesome_](https://github.com/sindresorhus/awesome/blob/master/awesome.md)
resources, libraries, information sources about Machine Learning with the [Ruby programming language][ruby].

This list comes from our day to day work on ML Applications.

Our main goal is to promote Ruby as a tool for Machine Learning Tasks. Your help,
suggestions and contributions are welcome! We kindly ask you to study
the [Contribution](#contributing) section.

Follow us on [Twitter](https://twitter.com/RubyNLP)
and please spread the word using the `#RubyML` hash tag!



<!-- nodoc -->
## Contents

<!-- toc -->

- [Machine Learning Libraries](#machine-learning-libraries)
- [Data Structures](#data-structures)
- [External Dependencies](#external-dependencies)
- [Articles, Posts, Talks, and Presentations](#articles-posts-talks-and-presentations)
- [Projects and Code Examples](#projects-and-code-examples)
- [Heroku buildpacks](#heroku-buildpacks)
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
  Support Vector Machines with Ruby and the [LIBSVM](http://www.csie.ntu.edu.tw/~cjlin/libsvm/) library.
  <sup>[[bundled][bundled]]</sup>
- [weka-jruby](https://github.com/paulgoetze/weka-jruby) -
  JRuby bindings for Weka, different ML algorithms implemented through Weka.
- [decisiontree](https://github.com/igrigorik/decisiontree) -
  Decision Tree ID3 Algorithm in pure Ruby.
  <sup>[[GraphViz][graphviz] |
        [post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>.
- [rtimbl](https://github.com/maspwr/rtimbl) -
  Memory based learners from the Timbl framework.
- [classifier-reborn](https://github.com/jekyll/classifier-reborn) -
  General classifier module to allow Bayesian and other types of classifications.
  <sup>[[GLS][gls]]</sup>
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
  <sup>[[bundled][bundled]]</sup>
- [scoruby](https://github.com/asafschers/scoruby) -
  Ruby scoring API for [PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html) (Predictive Model Markup Language).
- [tlearn-rb](https://github.com/josephwilk/tlearn-rb) -
  Recurrent Neural Network library for Ruby.
- [kmeans-clusterer](https://github.com/gbuesing/kmeans-clusterer) -
  k-means clustering in Ruby.
- [k_means](https://github.com/reddavis/K-Means) -
  Attempting to build a fast, memory efficient K-Means program.
- [knn](https://github.com/reddavis/knn) -
  Simple K Nearest Neighbour Algorithm.
- [neural-net-ruby](https://github.com/gbuesing/neural-net-ruby) -
  A neural network, written in Ruby.
- [liblinear-ruby](https://github.com/kei500/liblinear-ruby) -
  Ruby interface to LIBLINEAR using SWIG.
- [PCA](https://github.com/gbuesing/pca) -
  Principal component analysis (PCA) in Ruby.
- [phashion](https://github.com/westonplatter/phashion) -
  Ruby wrapper around pHash, the perceptual hash library for detecting duplicate multimedia files.
  <sup>[[ImageMagick][] | [libjpeg][]]</sup>
- [Cerebrum](https://github.com/irfansharif/cerebrum) -
  Artificial Neural Networks in Ruby.
- [flann](https://github.com/mariusmuja/flann) -
  Fast Library for Approximate Nearest Neighbors.
  <sup>[[flann][]]</sup>
- [ai4r](https://github.com/SergioFierens/ai4r) -
  Artificial Intelligence for Ruby.

## Data Structures

- [narray](https://github.com/masa16/narray) -
 Ruby/NArray: N-dimensional Numerical Array for Ruby.
- [NMatrix](https://github.com/sciruby/nmatrix) -
  Dense and sparse linear algebra library for Ruby via [SciRuby](http://sciruby.com/).
- [kdtree](https://github.com/gurgeous/kdtree) -
  Blazingly fast, native, 2d kdtree.


## External Dependencies
* [GSL (GNU Scientific Library)](http://www.gnu.org/software/gsl/)
```brew install gsl```
* [OpenCV](http://opencv.org/)
```brew tap homebrew/science && brew install opencv```
* [Graphviz](http://www.graphviz.org/)
```brew install graphviz```
* [Gnuplot](http://www.gnuplot.info/)
```brew install gnuplot --with-x11```
* [X11/XQuartz](http://xquartz.macosforge.org/landing/)
* [ImageMagick](http://www.imagemagick.org/) && libjpeg
```brew install imagemagick && brew install libjpeg```
* [R](http://www.r-project.org/)
```brew tap homebrew/science && brew install r```
* [Octave](https://www.gnu.org/software/octave/)
```brew tap homebrew/science && brew install octave --without-docs```

## Articles, Posts, Talks, and Presentations

- 2017
  - _Scientific Computing on JRuby_ by [Prasun Anand](https://twitter.com/prasun_anand)
    <sup>[[slides](https://www.slideshare.net/PrasunAnand2/fosdem2017-scientific-computing-on-jruby) |
    [video](https://ftp.fau.de/fosdem/2017/K.4.201/ruby_scientific_computing_on_jruby.mp4) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computing-on-jruby) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computation-on-jruby)]</sup>
- 2016
  - _Practical Machine Learning with Ruby_ by [Jordan Hudgens](https://twitter.com/jordanhudgens)
    <sup>[[tutorial](https://www.crondose.com/2016/12/practical-machine-learning-ruby/)]</sup>
  - _Deep Learning: An Introduction for Ruby Developers_ by [Geoffrey Litt](https://twitter.com/geoffreylitt)
    <sup>[[slides](https://speakerdeck.com/geoffreylitt/deep-learning-an-introduction-for-ruby-developers)]</sup>
  - _How I made a pure-Ruby word2vec program more than 3x faster_ by [Kei Sawada](https://twitter.com/remore)
    <sup>[[slides](https://speakerdeck.com/remore/how-i-made-a-pure-ruby-word2vec-program-more-than-3x-faster)]</sup>
  - _Dōmo arigatō, Mr. Roboto: Machine Learning with Ruby_ by [Eric Weinstein](https://twitter.com/ericqweinstein)
    <sup>[[slides](https://speakerdeck.com/ericqweinstein/domo-arigato-mr-roboto-machine-learning-with-ruby) | [video](https://www.youtube.com/watch?v=T1nFQ49TyeA)]</sup>
- 2015
  - _Machine Learning made simple with Ruby_ by [Lorenzo Masini](https://github.com/rugginoso)
    <sup>[[tutorial](https://www.leanpanda.com/blog/2015/08/24/machine-learning-automatic-classification/)]</sup>
  - _Using Ruby Machine Learning to Find Paris Hilton Quotes_ by [Rick Carlino](https://github.com/RickCarlino)
    <sup>[[tutorial](https://web-beta.archive.org/web/20160515115739/http://datamelon.io/blog/2015/using-ruby-machine-learning-id-paris-hilton-quotes.html)]</sup>
  - _Machine Learning made simple with Ruby_ by [Lorenzo Masini](https://twitter.com/rugginoso)
    <sup>[[post](https://www.leanpanda.com/blog/2015/08/24/machine-learning-automatic-classification/)]</sup>
- 2014
  - Test Driven Neural Networks by [Matthew Kirk](https://twitter.com/mjkirk)<sup>[[video](https://www.youtube.com/watch?v=ppf8m-3uXvU&t=36s)]</sup>
  - _Five machine learning techniques that you can use in your Ruby apps today_ by [Benjamin Curtis](https://twitter.com/stympy)
  <sup>[[video](https://www.youtube.com/watch?v=crziu7dk6Vw) |
        [slides](https://speakerdeck.com/stympy/machine-learning-techniques)]</sup>
- 2013
  - Sentiment Analysis using Support Vector Machines in Ruby by [Matthew Kirk](https://twitter.com/mjkirk) <sup>[[video](https://www.youtube.com/watch?v=iSug6CgxWxc)]</sup>
- 2012
  - _Machine Learning with Ruby, Part One_ by [Vasily Vasinov](https://twitter.com/vasinov)
    <sup>[[tutorial](http://www.vasinov.com/blog/machine-learning-with-ruby-part-one/)]</sup>
  - _Recurrent Neural Networks in Ruby_ by [Joseph Wilk](https://twitter.com/josephwilk)
    <sup>[[post](http://blog.josephwilk.net/ruby/recurrent-neural-networks-in-ruby.html)]</sup>
  - Recommendation Engines using Machine Learning, and JRuby by [Matthew Kirk](https:twitter.com/mjkirk) <sup>[[video](https://www.youtube.com/watch?v=hsZcrlbBg_0)]</sup>
- 2011
  - _Clustering in Ruby_ by [Colin Drake](https://twitter.com/colinfdrake)
    <sup>[[post](https://colindrake.me/2011/05/28/clustering-in-ruby/)]</sup>
- 2010
  - _bayes_motel – Bayesian classification for Ruby_ by [Mike Perham](https://twitter.com/mperham)
    <sup>[[post](http://www.mikeperham.com/2010/04/28/bayes_motel-bayesian-classification-for-ruby/)]</sup>
- 2009

- 2008
  - _Support Vector Machines (SVM) in Ruby_ by [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[post](https://www.igvita.com/2008/01/07/support-vector-machines-svm-in-ruby/)]</sup>
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
- https://github.com/hexgnu/rmw-svm
- https://github.com/hexgnu/wine_clustering

## Heroku buildpacks

* [GSL and Ruby buildpack](https://github.com/tomwolfe/heroku-buildpack-gsl-ruby)
* [OpenCV and Ruby buildpack](https://github.com/lilibethdlc/heroku-buildpack-ruby-opencv)
* [ImageMagick buildpack](https://github.com/mcollina/heroku-buildpack-imagemagick)

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

- [scikit-learn algorithm cheatsheet](http://scikit-learn.org/stable/tutorial/machine_learning_map/)
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

[![Creative Commons Zero 1.0](http://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
`Awesome ML with Ruby` by [Andrei Beliankou](https://github.com/arbox) and
[Contributors](https://github.com/arbox/machine-learning-with-ruby/graphs/contributors).

To the extent possible under law, the person who associated CC0 with
`Awesome ML with Ruby` has waived all copyright and related or neighboring rights
to `Awesome ML with Ruby`.

You should have received a copy of the CC0 legalcode along with this
work. If not, see <https://creativecommons.org/publicdomain/zero/1.0/>.

<!--- Links --->
[ruby]: https://www.ruby-lang.org/en/
[motivation]: https://github.com/arbox/machine-learning-with-ruby/blob/master/motivation.md
[contributing]: https://github.com/arbox/machine-learning-with-ruby/blob/master/contributing.md
[todo]: https://github.com/arbox/machine-lerning-with-ruby/blob/master/todo.md
[faq]: https://github.com/arbox/machine-learning-with-ruby/blob/master/FAQ.md
