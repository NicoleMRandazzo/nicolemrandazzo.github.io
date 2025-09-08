---
title: Coding Project - Predator-Prey Relation in the Gulf Of Mexico Following the 2010 Deepwater Horizon Oil Spill
layout: product
description_markdown: >-
  Simulating a scenario using cellular automation and the Python language
date: 2020-04-23 11:48:06 +0100
text-button: Let me try this!
image: /images/templates/jekyll/CP1.png
---
<div style="max-width: 1000px; margin: 0 auto; padding: 20px;">
  <img src="{{site.baseurl}}/images/templates/CP2.png" style="display: block; margin: 0 auto; width: 100%; max-width: 600px;" />
  <h3>Class: BME 303: Introduction to Computing</h3>
  <h3>Semester: Spring 2024</h3>
  <h3>Skills: Python</h3>
  
  <p>
    &emsp;The goal of this project was to use C++ or Python to simulate a real-world or imagined scenario through a cellular automaton. Our team of eight chose to model the ecological relationship between tiger sharks and green sea turtles in the Gulf of Mexico, specifically examining how their populations were affected by the 2010 Deepwater Horizon Oil Spill. We began by researching both species to determine key biological parameters, including population size, birth rate, and death rate. These metrics were integrated into our simulation to reflect realistic population dynamics.
  </p>

 <video autoplay muted loop playsinline style="width: 100%; max-width: 1000px; height: auto; display: block; margin: 0 auto;">
    <source src="{{site.baseurl}}/images/templates/CP1.mp4" type="video/mp4">
    Your browser does not support the video tag.
 </video>
  
  <p>
    &emsp;For our cellular automaton, we were required to define a mesh - or 2D matrix - where each cell represented a discrete agent occupying a 1 km x 1 km area. Agents could interact with adjacent cells, including diagonals, using a Moore radius of 1. Each cell could exist in one of three states:  water (blue), tiger sharks (grey), or green sea turtles (green). The simulation advanced in monthly time steps, running for 240 iterations to represent a 20-year span. We developed equations to model birth and death rates for both species, and visualized the results through mesh snapshots and a temporal evolution graph (pictured above). This illustrated how the oil spill disrupted population trends.
  </p>
   
  <img src="{{site.baseurl}}/images/templates/CP3.JPG" style="display: block; margin: 0 auto; width: 100%; max-width: 600px;" />
  
  <p>
  &emsp;After generating our baseline model, we explored how various factors  -  such as the volume of oil spilled, the cleanup duration, and the timing of the spill - impacted species survival. As shown in the above picture, these factors significantly influenced population outcomes. It is important to note that our model made simplifying assumptions, such as excluding interactions with other species and environmental variables. A more comprehensive simulation would require additional ecological data and could be adapted to study other disasters, such as wildfires. 
  </p>

Below is a photo of my team during the final presentation: 
<img src="{{site.baseurl}}/images/templates/CP4.JPG" style="display: block; margin: 0 auto; width: 100%; max-width: 600px;" />


