---
layout: default
title: Getting Started
nav_order: 3
---

# Step 1) Start python

### UBC provides students with server space where you can run python using a [Jupyter Notebook](https://ubc.syzygy.ca/jupyter)
* This is good for getting your bearings because everything is already set up.  You don't have to worry about installing anything on your own system.
 * Login with your CWL.  You'll then be taken to a blank jupyter window!

# Step 2) Download the workshop files

## a) To do this, we open a command terminal, and clone the github repository containing all the necessary files.
* This may sound intimidating/confusing.  But don't worry, its easy.  You don't need to know command line to do this.

## b) In they Jupyter window you just opened, click "New" in the top right and select "Terminal" from the dropdown menu

## c) In the new terminal window that opens, right click and paste the following command into the terminal window then hit enter:

### git clone https://github.com/ubc-library-rc/Geospatial-Analysis-Visualization-with-Python

* "git clone" is a command that tells git (a file tracking software) to to download a set of programs and files known as a repository
* [url](https://github.com/ubc-library-rc/Geospatial-Analysis-Visualization-with-Python) is the location of the repository for this workshop with all the files and code

<a href="git_Clone.mp4" target="_blank">Open Video in new tab</a>

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="git_Clone.mp4" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>

# Step 3) Navigating Jupyter Notebooks

* After cloning the repository, you will notice a folder titled "Geospatial Analysis and Visualization with Python" appear
  * Double clicking the folder will open it.
  * You'll see a couple more folders and a collection of files
* Files with the .ipynb tag on the end are "Jupyter Notebooks" 
  * You'll notice two inside:
      * Geospatial Analysis & Visualization with Python.ipynb
        * This is he notebook we'll be using if you plan to follow along live
        * There are a few points in here where write/edit the code to work through some problems
      * Backup.ipynb
        * This version is fully functional as is and can be used if you want to work through this on your own or copy some of the code.
