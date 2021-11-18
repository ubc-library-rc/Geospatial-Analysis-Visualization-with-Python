---
layout: default
title: Getting Started
nav_order: 2
---

# Getting Started
{: .no_toc }
This section provides a broad overview of Python along with an applied introduction.

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

# Why Python?

Its a great language! But its not the only language. Just as English, Cantonese, or Punjabi could all be used to explain systemic racism; Python, Javascirpt, or R can all be used to quantify and visualize the scale of the problem.   like python because its very flexible, fairly easy to read / write, well suited for data analysis, has lots of packages for GIS, and it's completely free!

## Packages

Python has a number of built in functionality, but many of the most useful tools and functions come require us to [import](https://docs.python.org/3/reference/simple_stmts.html#import) packages.

* Packages are pre-written blocks of code, sometimes referred to as libraries.
* They are built for addressing specific tasks: e.g. linear algebra, mapping, plotting.

## Accessing Python

Today We'll be using a UBC server with python already installed on it.  If you want to install Python on your own computer, check out [Anaconda](https://www.anaconda.com/products/individual).

* Anaconda will install most commonly used python packages and set everything up for you.
* Anaconda won't install *every* package we're using today, but installing new packages is fairly straightforward.

## Other resources

If you're having issues with Python, a great place to check out is [Stack Overflow](https://stackoverflow.com/).  It is a popular forum where you can search, post, and answer coding questions.
* A related site that is more GIS focused site is [Stack Exchange](https://gis.stackexchange.com/)


# Download the Code and Data

**1**{: .label .label-red } **Start a Jupyter Lab**

UBC provides server space where you can run Python using [Jupyter Lab](https://ubc.syzygy.ca/jupyter).  Login with your CWL.  You'll then be taken to a blank jupyter lab.
* This is good option for getting your bearings because nearly everything is already set up. You don't have to worry about installing anything on your own system.
* This may sound intimidating/confusing.  But don't worry, its easy.  You don't need to know command line to do this.  I'll walk you through step by step.  You can also refer to the video below for help


**2**{: .label .label-red } **Open a terminal**

We're going to open a command terminal and use command line clone the Github workshop's repository.

* In they Jupyter window, click File>"New" in the top right and select "Terminal" from the drop-down menu.

**3**{: .label .label-red } **Clone the Repository**

Cloning tells Git (a file tracking software) to download a repository (collection of code, data, etc.) for this workshop.  In the new terminal window that opens, paste this command and hit enter:

		https://github.com/ubc-library-rc/Geospatial-Analysis-Visualization-with-Python

A folder called Geocoding-Web-Mapping-with-Python should now be visible.  You can explore it using file viewer on the left, or you can use the command line (see video).

**4**{: .label .label-red } **Installing a Package**

In the terminal window type the command below and hit enter to install the geopy package.  We aren't actually working with this package today, but this package was used to geocode the addressees in the [dataset in this workshop](https://ubc-library-rc.github.io/Geocoding-Web-Mapping-with-Python/).

    pip install geopy

**5**{: .label .label-red }  **Opening a Jupyter Notebook**

In the file viewer You will notice a folder with the same name as the repository you just cloned, double clicking the folder will open it.  You'll see a folders and a collection of files.  The one we'll be working in is called "Python_Notebooks".  Double click to enter.
* The .ipynb tag on the end denotes a Jupyter "Notebook"
  * A Notebook is a collection of Python code and annotations that can be run interactively.
	* Double click on "Getting Started with Python.ipynb" to open it.

# Video Reference

This video covers the above steps - **Note** the video instructions reference a different workshop, but the procedures are exactly the same.

<iframe width="560" height="315" src="https://www.youtube.com/embed/_lqzOLeSlo0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>