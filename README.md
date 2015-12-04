# Final Project

## Instructions

This repository is a stub for your final project. Fork it as a template for your project, and develop your code in the forked repository. For details on how to fork and turn in the project, see section 3 of the github education  [documentation](https://education.github.com/guide/forks). After you fork the repository, please enable the issue tracker in the repository settings so that others in the class (including the professor) can provide feedback.

Expand on the readme questions below to provide an overview of the goals, background, and challenges for the final project. You can delete the questions as you write text that answers them, or leave the prompts in place. You can also delete this instruction section if you like.

## Introduction

This is a final project for the [Interacting with Data](https://github.com/Brown-BIOL2430-S04-Fall2015/syllabus) graduate seminar that took place in the fall of 2015. The goal was to build an interactive visualization that illustrates the (multivariate) central limit theorem, an important statistical result.

To view the complete visualization, click [here](https://rawgit.com/tylerdevlin/finalproject/master/2D_CentralLimitThrm.html). Read on to learn more about the details of our work.

This project was carried out in equal part by **Daniel Kunin** and **Tyler Dae Devlin**, who were juniors at Brown University at the time.

## The Theorem

This visualization is not meant to replace a rigorous development of the mathematical results in question. Rather, it is designed to supplement a more analytical approach to understanding the multivariate CLT. As such, we assume that the reader already familiar with the conventional univariate CLT at a minimum, and the multivariate CLT in the ideal case.

## Background

Ours is not the first attempt to create a visualization of the central limit theorem. In fact, there are even a few CLT visualizations in D3. See, for example, [Victor Powell's interactive animation](http://blog.vctr.me/posts/central-limit-theorem.html) of Sir Francis Galton's [bean machine](https://en.wikipedia.org/wiki/Bean_machine) or [Philipp Plewa's visualization](http://www.mpe.mpg.de/~pmplewa/showcase/clt/) of the CLT , which takes sample means from a uniform distribution. 

In Powell's animation, D3 is used mainly to visually simulate the process by which Galton's bean machine works while updating a histogram in real time. Plewa's illustration uses motion to connect the various steps involved in taking a sequence of sample means from a population. In our view, both visualizations are successful in communicating a particular facet of the univariate CLT.

To our knowledge, however, no attempt has been made to create a visualization of the multivariate CLT, which concerns joint probability distributions.

The fact that the formal mathematical treatment of the multivariate CLT is [fairly abstruse](https://en.wikipedia.org/wiki/Multivariate_normal_distribution) justifies the need for a well-designed intuitive visualization.

## This project

### Mapping of data to esthetics

How will aesthetic attributes ( X / Y / color / shape / size /texture / etc ) will be mapped to the data?

### Filtering

Are data filtered? ie in some views are some data not mapped to particular attributes of the image? What is the goal of the filtering?

### Extra ink

Are there aesthetic attributes that are not mapped to the data? If so, what purpose do they serve ( redundancy for robustness / improve visual metaphor / but data in context / beauty / etc )?

Are any data mapped to more than one aesthetic attribute? Why?

### Motion

If motion is used, what purpose does it serve ( metaphor (eg representing motion in real world) / transition continuity between views / etc )

### Perspective

To what extent is perspective (eg mappings) controlled by users vs hard coded in advance? How does this project aid in exploration vs exposition?

## Assessment

Was the new visualization successful at providing insight that was not possible or more difficult with previous approaches?

What are the main limitations of new approach?

What are future directions this could go in?


