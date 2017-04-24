Resources for Machine Learning in Ruby
===

Gems
---

* [liblinear-ruby](https://github.com/kei500/liblinear-ruby): Ruby interface to LIBLINEAR using SWIG

* [classifier-reborn](https://github.com/jekyll/classifier-reborn): Bayesian and LSI classification
dependencies: GSL

* [categorize](https://github.com/helioid/categorize): Categorize is a text categorization library written in Ruby. It prioritizes performance over accuracy and is built to run online in dynamic web services

* [decisiontree](https://github.com/igrigorik/decisiontree): ID3-based implementation of the ML Decision Tree algorithm
dependencies: Graphviz

* [similarity](https://github.com/bbcrd/Similarity):
Calculate similarity between documents using TF-IDF weights
dependencies: GSL

* [rb-libsvm](https://github.com/febeling/rb-libsvm):
Ruby language bindings for LIBSVM
dependencies: None ([LIBSVM](http://www.csie.ntu.edu.tw/~cjlin/libsvm/) is bundled with the project)

* [ruby-fann](https://github.com/tangledpath/ruby-fann):
Ruby library for interfacing with FANN (Fast Artificial Neural Network)
dependencies: None ([FANN](http://leenissen.dk/fann/wp/) is bundled with the project)

* [tlearn-rb](https://github.com/josephwilk/tlearn-rb):
Recurrent Neural Network library for Ruby

* [kmeans-clusterer](https://github.com/gbuesing/kmeans-clusterer):
k-means clustering in Ruby

* [k_means](https://github.com/reddavis/K-Means):
Attempting to build a fast, memory efficient K-Means program

* [knn](https://github.com/reddavis/knn):
Simple K Nearest Neighbour Algorithm

* [distance_measures](https://github.com/reddavis/Distance-Measures):
A bunch of distance measures that extend Array

* [fast-stemmer](https://github.com/romanbsd/fast-stemmer):
Fast Porter stemmer based on a C version of the algorithm

* [statsample](https://github.com/clbustos/statsample):
A suite for basic and advanced statistics on Ruby
dependencies: GSL

* [statistics2](https://github.com/abscondment/statistics2):
Provides normal, Chi-square, t- and F- probability distributions for Ruby

* [ruby-graphviz](https://github.com/glejeune/Ruby-Graphviz)
dependencies: Graphviz

* [gnuplot](https://github.com/rdp/ruby_gnuplot/tree/master)
dependencies: Gnuplot

* [rb-gsl](https://github.com/blackwinter/rb-gsl):
Ruby interface to the GNU Scientific Library
dependencies: GSL

* [ruby-opencv](https://github.com/ruby-opencv/ruby-opencv/):
OpenCV wrapper for Ruby
dependencies: OpenCV

* [ai4r](https://github.com/SergioFierens/ai4r): Artificial Intelligence for Ruby - A Ruby playground for AI researchers

* [algorithms](https://github.com/kanwei/algorithms): Ruby algorithms and data structures. C extensions

* [phashion](https://github.com/westonplatter/phashion): Ruby wrapper around pHash, the perceptual hash library for detecting duplicate multimedia files
dependencies: ImageMagick, libjpeg

* [narray](https://github.com/masa16/narray): Ruby/NArray : N-dimensional Numerical Array for Ruby

* [kdtree](https://github.com/gurgeous/kdtree) a blazingly fast, native, 2d kdtree

* [rinruby](https://github.com/clbustos/rinruby): integrates the R interpreter in Ruby, making R's statistical routines and graphics available within Ruby
dependencies: R

* [octave-ruby](https://github.com/daikini/octave-ruby) A Ruby interface to the Octave interpreted language
dependencies: Octave

* [flann](https://github.com/mariusmuja/flann): Fast Library for Approximate Nearest Neighbors
dependencies: flann

* [NMatrix](https://github.com/sciruby/nmatrix): Dense and sparse linear algebra library for Ruby via [SciRuby](http://sciruby.com/)

* [Cerebrum](https://github.com/irfansharif/cerebrum): Artificial Neural Networks in Ruby

* [PCA](https://github.com/gbuesing/pca): Principal component analysis (PCA) in Ruby

* [neural-net-ruby](https://github.com/gbuesing/neural-net-ruby): A neural network, written in Ruby



Base dependencies
---

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

Heroku buildpacks
---

* [GSL and Ruby buildpack](https://github.com/tomwolfe/heroku-buildpack-gsl-ruby)
* [OpenCV and Ruby buildpack](https://github.com/lilibethdlc/heroku-buildpack-ruby-opencv)
* [ImageMagick buildpack](https://github.com/mcollina/heroku-buildpack-imagemagick)


Other resources
---

* [scikit-learn algorithm cheatsheet](http://scikit-learn.org/stable/tutorial/machine_learning_map/)
* [Thoughtful Machine Learning: A Test-Driven Approach](http://www.amazon.com/Thoughtful-Machine-Learning-Test-Driven-Approach/dp/1449374069)
* [Support Vector Machines (SVM) in Ruby](https://www.igvita.com/2008/01/07/support-vector-machines-svm-in-ruby/)
* [Recurrent Neural Networks in Ruby](http://blog.josephwilk.net/ruby/recurrent-neural-networks-in-ruby.html)
* [Five machine learning techniques that you can use in your Ruby apps today](https://www.youtube.com/watch?v=crziu7dk6Vw) [slides](https://speakerdeck.com/stympy/machine-learning-techniques)

* Projects
  * https://github.com/hexgnu/rmw-svm
  * https://github.com/hexgnu/wine_clustering

* https://github.com/tomz/libsvm-ruby-swig
* https://github.com/hexgnu/reem
* https://github.com/hexgnu/sentiment_analyzer
