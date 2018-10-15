# python-novice-DTU-2018-10-17

This page is rendered as an html page [here](https://hjelmj.github.io/python-novice-DTU-2018-10-17/).

This lesson is an introduction to programming in Python for people with little or no previous programming experience. It uses plotting as its motivating example.
 
This lesson is mostly based on material from the [Software Carpentry](https://software-carpentry.org/) lesson [Plotting and Programming in Python](https://swcarpentry.github.io/python-novice-gapminder/).


## To do *before* the workshop
[Pre-workshop survey](https://docs.google.com/forms/d/e/1FAIpQLSdh6y849ImfnA3RLCHRmPiLBFM1-ju4DtZfG7TPKc2g2dXmIA/viewform): please fill this in at least two days in advance of the workshop!


## Workshop Pre-requisites

1. Learners need to understand what files and directories are, and what a [working directory](https://en.wikipedia.org/wiki/Working_directory) is.

2. Learners must install Python and Jupyter Notebook before the class starts - we strongly recommend that you use the platform independent [Anaconda Python Distribution](https://www.anaconda.com/distribution/) provided for free by Anaconda, Inc. This distribution comes with a large number of scientific packages pre-installed, including Jupyter Notebook.

    * download the Python 3.7 version of Anaconda [here](https://www.anaconda.com/download/) for your operating system (macOS, Linux, Windows)

    * If you already have Anaconda installed, please make sure you have Python version 3.5 or newer installed (if you are running Python 2.7 we can send you instructions for setting up an extra Python 3 environment alongside your Python 2.7 installation using Anaconda - contact Johan or Doris).

3. Learners must get the gapminder data before class starts: please download and unzip the file [python-novice-gapminder-data.zip](https://files.dtu.dk/u/4iVV-a8lVf_wJVX4/python-novice-gapminder-data.zip?l)


## Set-up instructions 

Detailed setup instructions (for the installation of Anaconda) can be found [here](https://swcarpentry.github.io/python-novice-gapminder/setup/).


## Agenda for the workshop
We recommend that you open a blank notebook and type along with the instructor. 
This is also a good way to keep a record of what you've done, your solutions to the exercises, and any problems you have encountered.

*Schedule:*

| Time | Topic | Content |
|-------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|
| 09:00 | 0. Meet up in room 8 in building 780 (Risø Campus)	 | Setup, and any questions / installation trobleshooting |
| 09:15 | 1. [Running and Quitting](https://swcarpentry.github.io/python-novice-gapminder/01-run-quit/index.html)	 | How can I run Python programs? |
| 09:30 | 2. [Variables and Assignment](https://swcarpentry.github.io/python-novice-gapminder/02-variables/index.html) | How can I store data in programs? |
| 09:50 | 3. [Data Types and Type Conversion](https://swcarpentry.github.io/python-novice-gapminder/03-types-conversion/index.html)	 | What kinds of data do programs store?   How can I convert one type to another? |
| 10:10 | 4. [Built-in Functions and Help](https://swcarpentry.github.io/python-novice-gapminder/04-built-in/index.html) | How can I use built-in functions?   How can I find out what they do?   What kind of errors can occur in programs? |
| 10:35 | 5. **Morning Coffee**	 | Break (15 min) |
| 10:50 | 6. [Libraries](https://swcarpentry.github.io/python-novice-gapminder/06-libraries/index.html) | How can I use software that other people have written?   How can I find out what that software does? |
| 11:10 | 7. [Reading Tabular Data into DataFrames](https://swcarpentry.github.io/python-novice-gapminder/07-reading-tabular/index.html) | How can I read tabular data? |
| 11:30 | 8. [Pandas DataFrames](https://swcarpentry.github.io/python-novice-gapminder/08-data-frames/index.html) | How can I do statistical analysis of tabular data? |
| 12:00 | 9. [Plotting with Matplotlib](https://swcarpentry.github.io/python-novice-gapminder/09-plotting/index.html) | How can I plot my data?   How can I save my plot for publishing? |
| 12:30 | 10. **Lunch**	 | Break (50 min) |
| 13:20 | 11. [Lists](https://swcarpentry.github.io/python-novice-gapminder/11-lists/index.html) | How can I store multiple values? |
| 13:40 | 12. [For Loops](https://swcarpentry.github.io/python-novice-gapminder/12-for-loops/index.html)	 | How can I make a program do many things? |
| 14:05 | 13. [Looping Over Data Sets](https://swcarpentry.github.io/python-novice-gapminder/13-looping-data-sets/index.html)		  | How can I process many data sets with a single command? |
| 14:20 | 14. [Writing Functions](https://swcarpentry.github.io/python-novice-gapminder/14-writing-functions/index.html) | How can I create my own functions? |
| 14:45 | 15. [Variable Scope](https://swcarpentry.github.io/python-novice-gapminder/15-scope/index.html)	 | How do function calls actually work? How can I determine where errors occurred? |
| 15:05 | 16. **Afternoon Coffee** | Break (10 min) |
| 15:15 | 17. [Conditionals](https://swcarpentry.github.io/python-novice-gapminder/17-conditionals/index.html)	 | How can programs do different things for different data? |
| 15:40 | 18. [Programming Style](https://swcarpentry.github.io/python-novice-gapminder/18-style/index.html)	 | How can I make my programs more readable?   How do most programmers format their code? How can programs check their own operation? |
| 16:00 | 19. Wrap-Up	 | What have we learned?   What else is out there and where do I find it? |
| 16:10 | 20. **Finish** |  |
| *By email after class* | 21. Feedback | How did the class go? --> Survey will be emailed out |

 
## Workshop repository

All the notebooks used by the instructors can be found [here](https://github.com/hjelmj/python-novice-DTU-2018-10-17).

## What else is out there?

The Python based scientific eco-system is growing fast and there are many useful generic and domain specific packages that are available. There is a quite comprehensive list of tutorials, packages, books etc on the [Topical Software](https://www.scipy.org/topical-software.html) page from the SciPy documentation pages.

### Matlab to Python/NumPy

For those with experience from MATLAB there are some useful resources to aid in the process of getting proficient with Numpy/Scipy, see for example the page ["NumPy for Matlab users"](https://docs.scipy.org/doc/numpy-1.15.0/user/numpy-for-matlab-users.html) and the table from Mathesaurus [here](http://mathesaurus.sourceforge.net/matlab-numpy.html).

### Tutorials & Galleries

Some of the most useful sets of tutorials for getting started include:

* [Software Carpentry]() - Lessons to help getting started with Python, Version Control, Unix Shell, etc
* [Python SciPy Lecture Notes](https://www.scipy-lectures.org/) - a tutorial and an excellent reference
* [Lectures on Scientific Computing](https://github.com/jrjohansson/scientific-python-lectures) by J.R. Johansson - another excellent set of tutorials. In particular [Lecture 4 on Matplotlib](https://nbviewer.jupyter.org/github/jrjohansson/scientific-python-lectures/tree/master/Lecture-4-Matplotlib.ipynb) is very good and is strongly recommended.
* This is not a tutorial but a useful figure to study to understand [the anatomy of a matplotlib figure]()

There are interesting and useful galleries with examples of notebooks for many different purposes (*e.g.* you can find the LIGO gravitational wave detection analysis as a notebook [here]()), see for example:

* [A Gallery of Interesting Notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks) - an great collection of notebooks curated by the Jupyter team.
* [Matplotlib's Gallery](https://matplotlib.org/gallery/index.html) - full of examples of different plot types and provides the source code for all of them (try to copy the link to the source code, and then type `%load <insert copied link here>` in a cell in a Jupyter notebook and see what happens...(then execute this cell).
* [The Python Graph Gallery](https://python-graph-gallery.com/) -  a large collection of examples also covering other popular visualization packages.


### Cheat Sheets

The following are examples of cheat sheets that can be helpful. The ones linked to below are provided by DataCamp and are geared towards Data Science.

* [Numpy Cheat Sheet ](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Numpy_Python_Cheat_Sheet.pdf)
* [Pandas Cheat Sheet](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/PandasPythonForDataScience.pdf)
* [Linear Algebra with SciPy](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Python_SciPy_Cheat_Sheet_Linear_Algebra.pdf)

### Books


### Scientific Packages - some examples

FIXME
