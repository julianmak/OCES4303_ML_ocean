# OCES 4303 AI and Machine Learning in Marine Science

NOTE: I happen to be using some data relevant to ocean science, otherwise the "Ocean Science" bit is neither here nor there.

Material mostly in the notebooks, but some are in the lecture slides themselves (mostly the theory parts). At least three known ways of running these:

1) On your computer, by downloading the pack (there should be a green "code" button near the top right of this page, click it and there should be "download")

2) On your computer, `git clone` this repository. Then you can do `git pull` you get updates (if any). You may or may not want to fork the repository (need a GitHub account), then you can commit changes too.

3) In Google colab, but you will need to pull copies (code and data) to your own Google drive, otherwise changes are not saved.

Clicking the icon below will open a temporary Colab instance, where changes are by default not saved (and you will need to pull the data files with `!wget` commands that are currently commented out in the notebooks). There should be a "copy to drive button" near "file" near the top left for copying to drive.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julianmak/OCES4303_ML_ocean/blob/main/) (requires Google login)

### Topics included here

Will not be touching on LLMs here. Core topics are:

1. Data handling in Python by demonstration
2. Regression, statistics/probability, data scaling and cross-validation
3. Linear models and dimension reduction
4. Clustering
5. Classification problems
6. Decision Trees
7. Random Forests + Gradient Boosting
8. Neural Networks
9. Convolutional Neural Networks
10. Some other neural network architectures

Extra topics to include AI + Ethics, PINNs, SINDy, online learning, diffusion models, GANs, TDA, others that I feel like at some point.

### Other resources of use

There are already quite a lot of Google and YouTube resources to be honest. Ones I used enough times beyond entries on Wikpiedia, Medium and StackOverflow for writing this course are the following:

* [Brunton & Kutz book](https://databookuw.com/)
* [scikit-learn manual](https://scikit-learn.org/stable/)
* [Michael Pyrcz](https://www.youtube.com/channel/UCLqEr-xV-ceHdXXXrTId5ig)
* [Deep Learning with Python](https://deeplearningwithpython.io/)
* [Hands-on Machine Learning with R](https://bradleyboehmke.github.io/HOML/)

### known things to add/check:

* yaml and environment files
* all notebooks to run on Colab with modulo additiongs of `!pip` + will remote load data appropriately


