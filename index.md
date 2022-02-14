---
layout: default
title: Introduction
nav_order: 1
---

# Geospatial Analysis and Visualization with Python
{: .no_toc }


Workshop created by June Skeeter june.skeeter@ubc.ca for the UBC Library Search Commons.

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

# Content Warning

This workshop deals with a difficult and painful subject that may be triggering to some, especially BIPOC individuals.  We are going to use a dataset of police killings and police involved deaths in Canada.  The intent behind choosing this dataset end goal of this workshop is to show that GIS, programming, data analysis, and data visualization can be powerful tools for promoting social and environmental justice issues.

# Learning Objectives

1) Cursory overview of data analysis with Python.

2) Introduction to geospatial analysis  with Python.
  * Reading and writing vector data.
  * Vector overlays.
  * Spatial intepolation.

3) Creating geospatial visualizations with Python

# Why Police-Involved Deaths in Canada?

Racism is ingrained in the history of policing in Canada since the founding of the Royal Canadian Mounted Police (RCMP) in 1873.  Police play a central tool in Canada's ongoing genocide of Indigenous people and they work to maintain systems of oppression throughout in Canadian society.  Canadian institutions rely on the lack of race based statistics and other demographic information to perpetuate a narrative that systemic racism is "just an American issue" and that Canada is "better".  As a white settler and immigrant from the United States, I fell for that narrative and did not question it for years.  
* We need to have discussions about systemic racism in Canada and make it part of the public discourse in order to hold Canadian institutions accountable.


## Notes on Terminology

**Police Killing:** A death directly resulting from police use of force.  Including but not limited to: shooting, tazing, other use of force.

**Police-Involved Deaths**  Any civilian death at the hands of police or in the custody of police.  Includes police killings deaths resulting from police negligence/inaction: suicide, overdoses, medical emergencies, etc.  This is broader term that is more difficult to refute on the grounds of semantics.  

## Increasing Police Violence in Canada

There has been an increasing trend in deaths at the hands of Canadian Police over recent years [<sup>1</sup>](https://police-involved-deaths-ca.github.io/Data/#increasing-police-violence-in-canada) .  This may be partly an result of greater access to information, but it is also likely that Canadian Police *are* becoming more violent.


<img src="https://police-involved-deaths-ca.github.io/Data/docs/images/Annual.png" alt="hi" class="inline" width="600"/>


