## Welcome to Data Science 1: Databases, Data Analysis, and Visualization!

#### Goals

Here's a short list of the things we'll accomplish in this tutorial.

* Install Anaconda ("Conda", for short)
* Install and verify packages with Conda's package manager
* Use Conda to create and run  a new virtual environment
* Understand the difference between installing packages with Conda, and installing packages in a virtual environment with PIP.
* Run iPython
* Begin using Jupyter Notebooks!


### Step 1: Installing Anaconda

The two most popular languages in Data Science are Python and R.  In our courses, we'll be focusing on Python.  This means we'll have access to awesome Data Science tools in Python, such as Anaconda!

####What is Anaconda?

Anaconda is a Python distribution built specially for Data Science and Analytics, distributed by a company called Continuum Analytics.  This is free, easy to use, and really, really powerful! If you're doing data science in Python, you can be pretty sure they're using Anaconda.

(From here on out, we'll refer to Anaconda by it's nickname, Conda.)

####Anaconda vs. Miniconda

We're going to start by installing Conda.  This is fairly straightforward, but just in case you have questions, you can follow [this link](https://conda.io/docs/user-guide/install/macos.html) to the full installation guide for Conda.  

We have two different options for installation: Anaconda and Miniconda.  Functionally, Miniconda is the same as Anaconda--they both contain Conda and the necessary dependencies to run Conda.  The main difference is that Anaconda is much larger, because it also contains the most popular data science packages as well: scipy, numpy, pandas, etc.  Miniconda is smaller, doesn't contain any of these.  

Since we'll be using all of these packages, we'll save ourselves some work by just installing the regular Anaconda package.  You can download it by following [this link](https://www.anaconda.com/download/#macos). (NOTE:  We'll be using Python 3 in this course, so make sure you download the correct version!)

Once you've downloaded the installer, run it and follow the instructions.  When the installation has finished, you'll want to open a terminal and verify the installation worked correctly.  

1.  Open a terminal
2.  run `conda list`

If the installation worked correctly, you should see terminal output listing all the different commands you can use with Conda. If you get an error message saying that the command `conda` is not recognized, try restarting your terminal and running `conda list` again.  


### Step 2: iPython

Now that Conda is up and running, let's play with some of the tools and see what all the fuss is about!

One of the coolest tools in Conda is `iPython`.  iPython is the engine behind Jupyter notebooks, but it's also an interactive python shell that makes coding Python in the terminal bearable.  

Let's begin!

1.  Open the terminal and type `iPython` to open iPython in the terminal.

If you've ever written Python code in the terminal, iPython should feel very familiar.  It's essentially the same experience, but with some added bells and whistles to make life easier, referred to as "magic commands".  For a full list of iPython magic commands, follow [this link](http://ipython.readthedocs.io/en/stable/interactive/magics.html) to see the documentation.


Let's try out some of the more useful ones--
