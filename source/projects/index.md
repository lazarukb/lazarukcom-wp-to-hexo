---
title: Projects
id: '63411'
tags: []
comments: false
date: 2021-05-02 11:06:26
---

## vPlanSim

vPlanSim is an open source tool aimed at researchers and developers that need a visualization of their planning problem. It is built with Python and the [Visualization Toolkit (VTK)](https://vtk.org/), an open source 2D and 3D rendering and plotting library.

A [peer-reviewed paper](https://lazaruk.com/#vplansim-publication) including the vPlanSim software has been accepted for The 31st International Conference on Automated Planning and Scheduling (ICAPS 2021).

I was the primary Python programmer on this project. Having no previous experience with the VTK library it was exciting to be able to learn how to effectively use those tools to create the simulation that was desired.

The bulk of the original development work was performed with a private GitHub repository.

![](/vplan-contrib.png)

Contributions to the vPlan private repository on GitHub.

Roberts, J. O., Mastorakis, G., Lazaruk, B., Franco, S., Stokes, A. A., & Bernardini, S. (2021). vPlanSim: An Open Source Graphical Interface for the Visualisation and Simulation of AI Systems. _Proceedings of the International Conference on Automated Planning and Scheduling_, _31_(1), 486-490. Retrieved from https://ojs.aaai.org/index.php/ICAPS/article/view/15995

[GitHub](https://github.com/mastrogiorgis/vPlanSim)

[Publication](https://ojs.aaai.org/index.php/ICAPS/article/view/15995)

## Gradez

Gradez is an undergraduate group project that I contributed to as part of the University of London [level 5 course Agile Software Projects](https://london.ac.uk/courses/agile-software-projects). This was my first significant use of Node.js and Express to develop a site.

[GitHub](https://github.com/grade-leaderboard/uol-agile-group-project)

[Live Site](https://www.gradez.fun)

![](/gradez.jpeg)

Screenshot of the live Gradez site deployed to Azure, from 2021.

## Google Coding Challenge  
Bright Network Internship Experience UK

As part of this virtual technology stream internship I had an opportunity to "program YouTube" as part of the Google Coding Challenge. The template provided a few completed Class definitions and unit tests. I chose to implement this project in Python and I was able to produce some code to successfully pass all 71 unit tests.

I was particularly pleased with how I was able to use nested list comprehensions to enable the filtering and search functions with just a few lines of code.

All my modifications to the template are included in the python folder within the cloned repository at [https://github.com/lazarukb/google-code-sample](https://github.com/lazarukb/google-code-sample).

[GitHub](https://github.com/lazarukb/google-code-sample)

[Certificate of Completion](https://www.brightnetwork.co.uk/certificates/internship-experience-uk-techn_luw57elo2t90dm/)

## Undergraduate Data Science Project

For the University of London [level 5 course Programming with Data](https://london.ac.uk/courses/programming-data) I created a Jupyter notebook which downloaded speeches from American and Canadian political leaders, computed the sentiment of those speeches, and plotted various comparisons of the calculated values.

I used coding techniques that cached the actual speech data locally to reduce the number of times the source websites were being scraped. Data cleaning was performed programmatically on each execution of the relevant cells in the notebook.

![](/ds-project-review.png)

For this project I used several Python libraries including beautifulsoup, pypandoc, nltk, langdetect, and vaderSentiment-fr. As some of the speeches contained or were entirely in French it was necessary to detect those sentence tokens with langdetect and pass them through the French language sentiment analyzer.

I received an 86% on this project, on the UK grading scale. Although exact conversions are not published my research suggests that this would be equivalent to approximately 94% at a Canadian university. The evaluator concluded "This is an excellent project. The data capture and cleanup is extensive and well-executed. The code and narrative are clear and well laid out. The analysis is thorough and your journey of discovery is clear."

I cannot release the source code as it was a graded project.

![](/pwd-cells.png)

Jupyter Cells Screenshot

![](/pwd-histogram.png)

Histogram Plot Screenshot

![](/pwd-pandas.png)

pandas DataFrame Screenshot

![](/pwd-boxplot.png)

Box Plot Screenshot

![](/pwd-pairplot.png)

Pair Plot Screenshot

## Undergraduate Programming Project 2

The University of London [level 4 course Introduction to Programming II](https://london.ac.uk/courses/introduction-programming-ii) required a full five month semester of working on the same project. I chose to do several extensions to a music visualization template that we were provided.

As with my ITP1 code everything was object oriented. On every frame of computation the Fast Fourier Transform of the sound was calculated and used to generate various visualizations. I also implemented a number of ways the user could customize the visualizations through changing speeds, colours, thresholds at which projectiles would be generated, and so on.

*   Word bubbles that changed size and bounced off each other and the sides of the screen.
*   A scrolling ridge plot
*   A custom extension that produced projectiles and fireworks, using the p5.particle library

The most extensive of the visualizations was a custom one which took a downloaded elevation map, automatically cropped it down to a manageable size, mapped it to points on the canvas, and then changed the size and transparency of the points in relation to the calculations made on the sound.

I received 92% for this project. I cannot release the source code as it was a graded project.

![](/itp2-needles.png)

ITP2 Project Screenshot

![](/itp2-word-bubbles.png)

ITP2 Project Screenshot

![](/itp2-ridge.png)

ITP2 Project Screenshot

![](/itp2-fireworks.png)

ITP2 Project Screenshot

![](/itp2-elevation.png)

ITP2 Project Screenshot

## Undergraduate Programming Project 1

For the University of London [level 4 course Introduction to Programming I](https://london.ac.uk/courses/introduction-programming-i) used p5.js to create a basic platform game. My code was object-oriented and used arrays, constructors, and two types of particle generators to create "smoke" and "fireballs" which were affected by gravity and served as a hazard to the player character. Each of the mountains, volcanoes, trees, clouds, pits, and gems (not pictured) were created and managed through object orientation and stored in arrays for ease of management. The screen continued to spawn new objects as the character moved through the gameworld and remove objects as they disappeared from view. Theoretically the size of the world would have only been limited by the memory capacity of the system running the code.

This was my first significant experience with JavaScript and my introduction to p5.js.

I received 100% for this project. I cannot release the source code as it was a graded project.

![](/itp1-bradlazaruk-1.png)

ITP1 Project Screenshot