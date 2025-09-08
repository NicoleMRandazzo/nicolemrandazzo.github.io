---
title: Blood Flow Project - Evaluation of Blockage Size and Length in the Internal Carotid Artery
layout: product
description_markdown: >-
  Modeling fluid flow parameters in an unblocked and blocked carotid artery.  
date: 2020-01-27 12:09:50 +0100
text-button: Cool! Give me this template, please!
image: /images/templates/free-pdf-storyboards/ca1.png
---
<div style="max-width: 1000px; margin: 0 auto; padding: 20px;">
  <img src="{{site.baseurl}}/images/templates/free-pdf-storyboards/ca1.png" style="display: block; margin: 0 auto; width: 100%; max-width: 600px;" />
  <h3>Class: BME 214L: Computational Fundamentals of BME Design</h3>
  <h3>Semester: Fall 2024</h3>
  <h3>Skills: SolidWorks, Fluid Flow simulation, technical memorandum writing</h3>
  
  <p>
    &emsp;The objective of this project was to write a technical memorandum in response to a biomedical engineering prompt focused on vascular health. Specifically, our team was tasked with evaluating blood flow in the carotid artery bifurcation using simulated data to determine which combinations of blockage diameter and length would require surgical repair or stenting. To approach this, our team of three decided to analyze shear stress, velocity, and mass flow rate in the artery.  
  </p>

  <img src="{{site.baseurl}}/images/templates/ca2.png" style="display: block; margin: 0 auto; width: 100%; max-width: 600px;" />

  <p>
    &emsp;To begin, we modeled a simplified bifurcated carotid artery in SolidWorks. We created two models: one without a blockage (a healthy artery) and one with a blockage. Using SolidWorks’ Fluid Flow simulation, we analyzed how variations in blockage geometry affected the maximum shear stress, maximum velocity, and mass flow rate out of the artery. We reviewed several scientific papers and studies to determine the cutoff values of each parameter that would indicate concern. In our model, the blockage starts approximately 0.01 m from the lower end of the internal carotid artery. The graph above illustrates the relationship between the length and diameter of the blockage and the velocity in the internal carotid artery. 
  </p>
   
  <img src="{{site.baseurl}}/images/templates/ca5v2.png" style="display: block; margin: 0 auto; width: 100%; max-width: 600px;" />

  <p>
    &emsp;Based on these thresholds, we adjusted the blockage dimensions to determine when immediate intervention would be required. Our findings revealed that maximum shear stress reaches its critical value before velocity or mass flow rate, making it the limiting factor in our analysis. Our results suggest that surgical intervention should be considered when there is an artery diameter of less than 3.75 mm. This level of narrowing correlates with a high shear stress value that can increase the occurrence of plaque rupture. More severe blockages would further compromise mass flow rate, potentially impairing nutrient transport to the brain. The above image compares the shear stress for normal geometry and cutoff geometry. To generalize these results, we proposed that a reduction of the internal carotid artery’s diameter to 75% or less of the normal size requires surgical intervention.
  </p>
