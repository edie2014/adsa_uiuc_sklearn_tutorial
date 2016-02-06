Scikit-learn Tutorial
=====================

Heavily based on (and shortened from) the SciPy [2015 tutorial](https://github.com/amueller/scipy_2015_sklearn_tutorial) by [Kyle Kastner](https://kastnerkyle.github.io/)([@kastnerkyle](https://twitter.com/kastnerkyle)) and [Andreas Mueller](http://amuller.github.io)([@t3kcit](https://twitter.com/t3kcit)), which was, in turn, based on the SciPy [2013 tutorial](https://github.com/jakevdp/sklearn_scipy2013) by [Gael Varoquaux](http://gael-varoquaux.info), [Olivier Grisel](http://ogrisel.com) and [Jake VanderPlas](http://jakevdp.github.com).

You can find the video recordings of the SciPy 2015 tutorial on youtube:

- [Part 1](https://www.youtube.com/watch?v=80fZrVMurPM)
- [Part 2](https://www.youtube.com/watch?v=Ud-FsEWegmA)

Instructor
----------

- [Vlad Niculae](https://vene.ro) ([@vnfrombucharest](https://twitter.com/vnfrombucharest)), Cornell University

Installation Notes
------------------

First your need to make sure you have Python on your machine. In order to check it you can just type: 

    python -V 
    
If Python is installed, you should be able to see somethng like this: 

    Python 2.7.11

Otherwise you will see something else. If you don't have python try to install it via brew: 

    brew install python 

Both Python2.7 and 3.4 should both work fine for this tutorial.
If you don't have brew, you can inatll it [here](http://brew.sh/). 

This tutorial will require recent installations of *numpy*, *scipy*,
*matplotlib*, *scikit-learn* and *ipython* with ipython
notebook.

The last one is important, you should be able to type:

    ipython notebook

in your terminal window and see the notebook panel load in your web browser. 
Try opening and running a notebook from the material to see check that it works.
If you don't have `ipython`, 
you can install it through `pip`: 

    pip instal ipython 
   
For users who do not yet have these packages installed, a relatively
painless way to install all the requirements is to use a package such as
[Anaconda CE](http://store.continuum.io/ "Anaconda CE"), which can be
downloaded and installed for free.

After getting the material, you should run ``python check_env.py`` to verify
your environment.

If you are missing any package, use `pip` to instal them. For example to instal `numpy` we can do: 

    pip install numpy

Downloading the Tutorial Materials
----------------------------------
I would highly recommend using git, not only for this tutorial, but for the
general betterment of your life.  Once git is installed, you can clone the
material in this tutorial by using the git address shown above:

    git clone git://github.com/vene/asda_uiuc_sklearn_tutorial.git

If you can't or don't want to install git, there is a link above to download
the contents of this repository as a zip file.  We may make minor changes to
the repository in the days before the tutorial, however, so cloning the
repository is a much better option.

Data Downloads
--------------

The data for this tutorial is not included in the repository.  We will be
using several data sets during the tutorial: most are built-in to scikit-
learn, which includes code which automatically downloads and caches these
data.  Because the wireless network at conferences can often be spotty, it
would be a good idea to download these data sets before arriving at the
conference. Run ``fetch_data.py`` to download all necessary data beforehand.

Outline
=======

TODO
