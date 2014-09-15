---
layout: project
title:  "Commit Guru"
date:   2014-05-16 00:00:00
author: Ben Grawi
categories:
- project
img: commitguru_0.png
thumb: thumb_commitguru_0.png
carousel:
- commitguru_0.png
client: RIT Independent Study
website: http://commit.guru
description: A site for displaying and predicting commits that introduce bugs into repos. 
---
I created my first site with a node.js backend framework called sails.js and a frontend in Angular.js
####About
I worked with RIT (now Concordia) professor Emad Shihab along with Christoffer Rosen, a 5th-year student at the time, to create a commit analyzing service designed to find patterns of bug-introducing commits in repositories and then make predictions for new commits. 

The frontend is my favorite AngularJS/Bootstrap stack, but the backend is actually a NodeJS server running Sails.js, which is an awesome framework I came across and fell in love with.

We also have a python daemon running, which I started work on, but Christoffer really brought it to fruition. It's purpose was to do the actual ingestion and statistical analysis of the repositories with R.

####Technologies

* HTML/CSS/JS
* AngularJS
* Bootstrap
* Sails.js on NodeJS
* Python
* PostgreSQL
* R

####Features

* Account creation and tracking
* Feedback on commit ranking
* Analysis of various commit metrics and suggestions of bug-inducing commits 
* Historical commit search and repository overview