
# CCNY/CUNY Intro to Jupyter Workshop for Digital Humanities

These are notebooks and slides for a workshop introducing Jupyter. Jupyter is a technology which is widespread in data science but is also being used in many other fields, including the digital humanities, to combine data analysis, text, images, and media in a single document. While this workshop will focus on its use in humanities, faculty from other disciplines are welcome to participate.

If you work on a laptop, please bring it along. Loaner laptops will be available at the workshop; please include a request for one with your response.

## Preperation/Requirements

No prior experience is required but certainly some would be helpful. It will particularly speed things up if you have some software installed. After a presentation about Jupyter we will be engaged in a hands-on demo with your laptop. You must have a

* Laptop running Windows/Mac OS/Linux (Chrome may be ok)
* Modern Browser such as Google Chrome, Firefox, or Safari (MS-Edge may be ok)

Tablets such as Ipads, even with keyboards, are still clunky working with jupyter. This is not recommended.

## Recommended Installation

While Jupyter can be used in the cloud, it will be useful for you to be able to leave the workshop with the ability to work on your own laptop or computers. If your data set is moderately sized, modern laptops are able to handle most tasks. It is often easier to begin your analysis on your laptop and move the notebooks to the cloud when more convenient. Sometimes one may find going back and forth many times as your analysis develops. There are many many was to install juptyer. Unfortunately there are many libraries and extensions that also should be installed to be able to get the most out of your work. We are going to be focusing on python here although many of the same things can be done in R or in other computing languages. In order to be able to install compatable versions of all the software packages it is convenient to work with a *distribution system*. This is a set of installers and repositories that attepts to take the hard work of making sure there are not conflicts with the parts. The most prominant one these days is the

* [Anaconda Python Distribution](https://www.anaconda.com/download/)

Please install this for your platform. Choose the 64-bit graphical installer python 3.7 version. We plan to have USB keys but it will be much faster if you do this ahead of time. If, for some reason you cannot or do not want to install anaconda we can accomodate some of you on our little Jupyterhub. It is a buggy and may strain under multiple users but should be sufficient for the workshop. For reference the url is

* [ccnyhub.org](ccnyhub.org)

## Packages We will use

There are a number of python packages we will use during the workshop. It makes sense to, again, install them ahead of time. They are

* numpy (should be pre-installed with Anaconda)
* matplotlib (should be pre-installed with Anaconda)
* pandas (should be pre-installed with Anaconda)
* requests
* nltk
* wordcloud

Each of these can be installed either by opening a notebook and running the command 

* ! conda install requests nltk wordcloud -c conda-forge

in your notebook, or typing

* conda install requests nltk wordcloud -c conda-forge

in the terminal.

## Workshop

* Intro_to_juptyer.pdf (opening presentation)
* part1-intro-to-python-and-jupyter.ipynb (intro to python and basic jupyter)
* part2-table-data-analysis.ipynb (working with tabular data through python-pandas)
* part3-three-book-word-analysis.ipynb (down loading texts and working with them)

## Refrences


## Credits

This workshop was developed by Michael Grossberg with extensive help from Hannah Aizenmann.

