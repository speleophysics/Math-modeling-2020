# Setting up your computer for Math modeling class

Below you will find summaries for setup of software and **Github** repositories for *Mathematical Modeling of Geological Processes.* 

Code in the class will be written in the [Python](http://www.python.org) programming language. **Python** is a general purpose programming language that can be used to do all kinds of things (write computer games, generate websites, data analysis and visualization, and even for *mathematical modeling!*). There are many packages available for Python that extend its basic functionality. We will need many of these packages for the exercises in this course. To make our lives easier, we will install a specific *distribution* of Python called **Anaconda**, which includes most of the packages that we will need for scientific programming in Python and also includes a variety of other useful software, such as a package management software called **conda**, which we can use to install any other packages we might need.

## Anaconda python distribution

The individual version of **Anaconda**  is free, meaning that you can easily transfer the tools that you learn in this course to wherever you find yourself working in the future (*no need for expensive licenses, e.g. as with Matlab or other similar programming languages*). 

To download and install Anaconda using this [link](https://www.anaconda.com/products/individual). Chose the installer for your OS, and make sure you *install Python 3 as opposed to Python 2*, that is, the installer should be Python 3.x of some variety. It gives a choice for 32-bit vs 64-bit. Most of you probably have 64-bit machines, so chose this option unless you know that you have a 32-bit machine. 

You can find some general information about using Anaconda [here](https://docs.anaconda.com/anaconda/user-guide/getting-started/).

## Visual Studio Code (or VS Code)

**VS Code** is what is called an [interactive development environment](https://en.wikipedia.org/wiki/Integrated_development_environment) or **IDE**. It is a text editor for coding that is combined with a lot of additional functionality that makes writing, reading, running, and debugging code easier. This software is also free. When working with Python code in this class, we will primarily use VS Code.

You can find information on downloading and installing VS Code [here](https://code.visualstudio.com/).

There is extensive documentation on using VS Code. A good place to start is this [set of videos](https://code.visualstudio.com/docs/getstarted/introvideos). In particular, I suggest you watch the **Getting Started** video, which takes you through the install process and the **Extensions** video, which will show you how to install extensions. There is also a portion of the User Manual [that explains how to install extensions](https://code.visualstudio.com/docs/editor/extension-gallery).

For this course you will need the following extensions to be installed:

* Python
* Anaconda Extension Pack
* GitHub Pull Requests and Issues
* GitLens
* Live Share
* Live Share Audio
* Live Share Extension Pack

Use the instructions found at the links above to install these extensions within your copy of VS Code.

Anaconda also comes with another IDE called **[Spyder](https://www.spyder-ide.org/)**. This is also a quite capable IDE, but it does not have some of the interactive components that we will use in class.

## Git and Github

**Git** is a [distributed version control system](https://www.atlassian.com/git/tutorials/what-is-version-control). It allows us to keep track of changes within our code by creating shapshots of that code (called commits) at different points in time. This can be incredibly useful if you mess something up in your code and want to revert to an older version. However, it also helps you to keep track of progress or go back and see the history of your changes. 

**Github** is an online server where you can publish your git repositories. This is important because it creates an online backup of your work. It also makes it easier to share your code with others. In fact, Git and Github really shine when you have a team of programmers working on the same code. It provides a very useful workflow for collaborative programming.

### Git-it

[Git-it](https://github.com/jlord/git-it-electron) is a desktop app that provides a brief tutorial to the process of installing and using git. Read through the intro page at the above link and then go to the [releases section to download Git-it](http://github.com/jlord/git-it-electron/releases).

To prepare yourself for using Git in class, go through the first 6 "challenges" provided by Git-it, ending with "Forks and Clones".

## Setting up git repositories for class

In class, we will use two different git repositories. One is a **master class repository** that contains code that I provide and/or create during lectures. This *is* that master repository (Math-modeling-2020).  

The second repository will be your **own repository** where you store and track your own code. If you wanted, you could also create a separate repository specifically for your project, as this would help to separate out your project code from your in-class and homework code. 

### Forking the master course repo

To set up the main course repository on your own computer follow the instructions in Git-it for forking a repository. Only, instead of forking `patchwork`, fork [`Math-modeling-2020`](https://github.com/speleophysics/Math-modeling-2020). 

