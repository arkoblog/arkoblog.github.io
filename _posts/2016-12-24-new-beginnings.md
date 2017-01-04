---
layout: post-no-feature
title: "Of maps, apps and geospatial analysis!"
author: "Arogya Koirala"
date: "24 Dec, 2016"
description: "Developing an application that helps us understand the condition of schools in Dhading"
category: articles
comments: true
tags: [sample post, readability, test]
---

Our team at Kathmandu Living Labs thought it'd be interesting to dig deeper into the data collected during the [Structural Integrity and Damage Assessment](http://www.kathmandulivinglabs.org/projects/structural-integrity-and-damage-assessment) project. The focus of this small exercise was to identify how we could leverage the data collected to generate actionable insights around the educational infrastructure of Dhading. 

I was particularly excited, for many reasons, which include:

* I couldn't believe that I was getting to work with data that was relevant to my own community. 
* Playing with geospatial data was completely alien to me, I had visualized geographic data before but barely understood how I did it. This was my chance at re-learning old concepts.
* I always wanted to try my hands at building a web application using R Shiny, and this was an excellent opportunity to do so.

Over the course of the week, we managed to build and deploy a small R Shiny app that, quite surprisingly, provided us with a wealth of information. Even though we barely scratched the surface of the large dataset, we were quickly able to learn about a lot of things, that include:

* How are schools distributed by eleveation around Dhading? 
* What are some schools in high/low elevation zones?
* What about students? How many students (also what proportion of students) in Dhading attend schools that are above 1500m?
* How many schools are more than 3kms away from the nearest road?
* ....and much more.

[The app is currently hosted in Shinyapps.io, click here to visit and play with it yourself!](https://arkoblog.shinyapps.io/app_dhading_survey/) 

Here is a screenshot of the app (unfortunately, it doesn't work with Google chrome, you'll have to view it on Firefox)

<img src="https://cloud.githubusercontent.com/assets/24402285/21640745/555bfbee-d29f-11e6-9b74-c8ae66e63620.PNG"/>

### Resources: 
If you would like to learn more about geospatial analysis and visualization using R, here are some links that were of great help during this project:

* [Introduction to Visualizing Spatial Data in R](https://cran.r-project.org/doc/contrib/intro-spatial-rl.pdf): An excellent resource to learn about spatial data frames, manipulation techniques, and some interesting visualization libraries such as ggmap, tmap and leaflet.
* [Leaflet for R](https://rstudio.github.io/leaflet/): The official website has some excellent refernces for the Leaflet R library.
* [This youtube playlist for R shiny](https://www.youtube.com/playlist?list=PL6wLL_RojB5xNOhe2OTSd-DPkMLVY9DfB) is all you need to get started with the library.

Happy playing! If you uncover any interesting insights, feel free to let me know by commenting below.
