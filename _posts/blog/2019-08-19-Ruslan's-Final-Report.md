---
layout: post
title: GSoC Final Report by Ruslan 
categories: blog
excerpt: work product submission on the scona project during GSoC program
image:
  feature:
link:
date: 2019-08-19
modified:
share: true
author: ruslan_yermakov
---

## TL;DR - GSoC Summary

> **Student**: Ruslan Yermakov  
**Mentor**: Dr Kirstie Whitaker    
**Organization**: [INCF](https://www.incf.org/gsoc2019/projectlist)    
**Project**: In the course of the program I was working on the open-source project [**scona**](https://github.com/WhitakerLab/scona) - a toolkit to perform brain network analyses. 
The goal of my project was to produce publication-ready brain network analysis results and visualizations from the command line. 

In this blog I am sharing the achieved deliverables and results with the community.

## The scope of the project

Neuroscientists and neuroimaging researches perform structural network analyses on the MRI data.
Scona is designed to imrove this experience and to help researchers run brain analyses quickly and reliably in order to capture many aspects of brain structure and function.

My project is mainly focused on the visualisation part that is now included in the scona package.
  
Achieved deliverables:
- implementation of visualization module to plot MRI data and the results of structural covariance brain network analyses;  
- development of visualisation functions which allows users to produce publication-ready plots based on the results of the performed analysis for publication in a scientific journal;  
- writing documentation and tutorials to help users better understand how to use the package;
- fixing bugs and issues in the project; 


#### Links to my contributions

There are a bunch of [issues](https://github.com/WhitakerLab/scona/issues) within the project, which were used to discuss new features, to find solutions for challenges and to communicate the results. 
You can easily search for issues by filtering using label “visualisations” and/or “enhancement”.

Here are the links to my merged Pull Requests that cover all the work:
1) [Implementation of visualisation tools #121](https://github.com/WhitakerLab/scona/pull/121)
2) [Implementation of anatomical network visualisations #140](https://github.com/WhitakerLab/scona/pull/140)
3) [Add Nilearn plotting functionality to scona #145](https://github.com/WhitakerLab/scona/pull/145)
4) [TODO - open new one here new opened]()

<figure class="half">
  <img src="/images/Ruslan-GSoC/2pic.png" alt="Picture 1">
  <img src="/images/Ruslan-GSoC/3pic.png" alt="Picture 2">
</figure>
<figure class="half">
  <img src="/images/Ruslan-GSoC/1pic.png" alt="Picture 3">
  <img src="/images/Ruslan-GSoC/4pic.png" alt="Picture 4">
  <figcaption> Created plots from the sample dataset </figcaption>
</figure>

#### Challenges

Of course, there were some challenges during my project. 
To name a few: writing understandable tutorials, adjusting parameters to ensure the produced figures are ready to be published in the research paper and … colorbars (do not underestimate them!).
Probably the hardest thing was to write clear tutorials to demonstrate the usage of scona package for data visualization. 
Together with the supportive community, we managed to accomplish the task. 
Moreover, owing to the constant feedback from my mentor, I was able to develop visualization functions that produce publication-ready plots, thereby achieving my goal in this project.

#### Wish I could do more

Now, when I became comfortable with the project, I feel like I could have contributed more to the development of the command-line tool itself. 
I feel like I could have contributed more if I initially had more knowledge on the neuroscience topic. 
Nevertheless, Kirstie did her best to explain the gist of the major concepts and ideas to newbies like me, which allowed me to write documentation and to improve the code for conducting brain analysis, i.e. to improve the performance of small-world coefficient calculations. 

## Future Plans

As per my future plans, in October 2019 I am starting my Master's studies in Data Science at RWTH University in Aachen, Germany.


## Thanks
Many thanks to my mentor Dr Kirstie Whitaker and to Isla Staden, who were always very helpful and responsive.

 