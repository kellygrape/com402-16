---
layout: post
title:  February 9, 2016 - Media Queries and Grid Based Design
date:   2016-02-09
permalink: lesson-07/
---

##Class Goal

We will discuss CSS layout using a grid and how to implement a pre-made grid system into your designs.

##Lesson Plan

### Grids and CSS

This lesson will introduce you to using a grid system for positioning content.  We have already done this in previous lessons - remember the activity we did in lesson 17 ([layout activity](/lessons/2014-10-03-advancedhtmlcss.html)) - using columns to lay out our content and creating sidebars and main content areas.

To design with a grid, you need to consider that your content can be broken up into rows and columns.  Every row can have any number of columns, but it looks nice if your columns are of predictable width.

**More Information**

- http://www.thegridsystem.org/
- http://jordanlev.github.io/grid/

### Grid Systems

There are probably over a hundred grid systems out there. Here are some that I have used and liked.

- [960 Grid System](http://960.gs/) (Note - this is NOT responsive)
- [Skeleton Grid](http://www.getskeleton.com/) (This is one of the simplest frameworks - and one of the first responsive grid systems I encountered!)
- [Base CSS](http://getbase.org/) (another framework, a bit more complicated to get set up but really simple code-wise)
- [Unsemantic Grid](http://unsemantic.com/) (The successor to 960 grid).
- [Gridism](http://cobyism.com/gridism/) (Very different, but simple!)
  
  
### Using Skeleton Grid

First, visit the [Skeleton Grid](http://getskeleton.com/) website.  Click the "Download" button.

Create a folder in your class work folder and name it `skeleton`.  Unzip the files you just downloaded into this new folder you created.

**Building a Landing Page**

Let's use the Skeleton example and build a landing page!

Go to the <a href="../media/0209/landing.zip">example code</a> (you can also get it from the Skeleton github repo, but I've pulled out just the files we want!).

**Use the files from this download to overwrite the things in your skeleton folder**.

Let's walk through the code and see what's happening.


### Free Coding Time

- Create a new file in your Skeleton folder.  
- Name it **layout.html**.  
- Include the skeleton grid and normalize (like in your landing page!)  
- Create a new CSS file and name it layout.css
- Include this CSS file in your layout file.
- Try to replicate <a href="../media/0202/layout3.png">this layout</a> using Skeleton's CSS.  Does having the grid system already built help you?