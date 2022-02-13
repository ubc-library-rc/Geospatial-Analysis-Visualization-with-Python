---
layout: default
title: Getting Started
nav_order: 4
---

# Getting Started
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>


# Accessing Python

Today We'll be using a UBC server with python already installed on it.  If you want to install Python on your own computer, check out [Anaconda](https://www.anaconda.com/products/individual).

* Anaconda will install many of the most commonly used python packages and set everything up for you.
* Anaconda won't install *every* package we're using today, but installing new packages is fairly straightforward.

**Other resources**: If you're having issues with Python, a great place to check out is [Stack Overflow](https://stackoverflow.com/).  It is a popular forum where you can search, post, and answer coding questions.  A related site that is more GIS focused site is [Stack Exchange](https://gis.stackexchange.com/)


## Download the Code and Data

**Video Reference**: This video covers the steps in case you get lost.  *Note* this video is for a different workshop, but other than the github url and folder names, everything else is the same.

<iframe width="560" height="315" src="https://www.youtube.com/embed/_lqzOLeSlo0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


**1**{: .label .label-red } **Start a Jupyter Lab**

UBC provides server space where you can run Python using [Jupyter Lab](https://ubc.syzygy.ca/jupyter).  Login with your CWL.  You'll then be taken to a blank Jupyter lab.  This is a good option for getting your bearings because nearly everything is already set up.  You don't have to worry about installing anything on your own system.
* This may be intimidating, but don't worry, you don't need to know command line to do this.  I'll walk you through step by step.

**2**{: .label .label-red } **Open a terminal**

We're going to open a terminal and use command line clone ("download") the Github workshop's repository.  In they Jupyter window, click **File>>New** in the top right and select **Terminal** from the drop-down menu.

**3**{: .label .label-red } **Clone the Repository**

**clone** tells **git** (a file tracking software) to download a repository (collection of code, data, etc.) for this workshop.  A folder called **Geocoding-Web-Mapping-with-Python** will appear after you clone the repository.  You can explore it using the file viewer on the left, or you can use the command line.  In the new terminal window that opens, paste this command and hit enter:

```console
https://ubc-library-rc.github.io/Geospatial-Analysis-Visualization-with-Python/
```

**4**{: .label .label-red } **Installing a Package**

**pip** (package installer for Python) is a tool we can use to install packages.  All tha packages we need today are already installe, but if you needed to install one, this is how you would do it.  In the terminal window type the command below and hit enter to install the Geopy package:

```console
    pip install geopy
```

**5**{: .label .label-red }  **Opening a Jupyter Notebook**

In the file viewer you will see a folder called **Geospatial-Analysis-Visualization-with-Python**, double clicking the folder will open it.  You'll see a collection of folders and files.  The one we will be working in today is called **Python_Notebooks**.  In this folder you will see three files with **.ipynb** tag, that denotes a **Jupyter Notebook**.  A Notebook is a collection of code and annotations that can be run interactively.  Double click a notebook to open.  

* **Getting Started with Python.ipynb**: will give you an introduction to data analysis with Python.

* **Working with Geopandas.ipynb**: will give you an introduction to using geopands to:
  * Importing, edit, viewing, and writing vector data
  * Change coordinate reference systems
  * Spatial overlay
    * Clip


* **Example Workflow.ipynb**: Shows a practical application of how you can use python violence at the hands of Police in BC.  This will also introduce new skills:
  * Import a .csv file and project latitude/longitude data 
  * Spatial overlay
    * Spatial join
    * Point in polygon
  * Calculate kernel density
    * Save raster layer
