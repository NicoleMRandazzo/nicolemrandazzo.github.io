---
title: Coding Project - Statistics Analysis
layout: product
description_markdown: >-
  Conducting a statistical analysis on data acquired from BME students. 
date: 2019-03-18 13:20:50 +0100
text-button: This could be useful. Can I get it?
image: /images/templates/assignments/sp1.png
---
<div style="max-width: 1000px; margin: 0 auto; padding: 20px;">
  <img src="{{site.baseurl}}/images/templates/assignments/sp1.png" style="display: block; margin: 0 auto; width: 100%; max-width: 600px;" />
  <h3>Class: Class: BME 335: Engineering Probability/Statistics</h3>
  <h3>Semester: Semester: Spring 2025</h3>
  <h3>Skills: Skills: RStudio</h3>
  
  <p>
    &emsp;The objective of this project was to gain hands-on experience applying statistical techniques in RStudio to analyze physiological data. Our group of three selected a dataset from an experimental study on BME students, which included variables such as caffeine consumption, gender, weight, height, and systolic blood pressure measured before and after occlusion. We conducted five statistical tests to explore relationships among these factors. 
  </p>

  <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin: 20px 0;">
    <img src="{{site.baseurl}}/images/templates/sp2.png" style="width: 300px; height: auto;" />
    <img src="{{site.baseurl}}/images/templates/sp3.png" style="width: 300px; height: auto;" />
  </div>

  <p>
    &emsp;One of the statistical tests we conducted was a Welch’s t-test on the systolic blood pressure of students who had consumed caffeine in the past hour and those who had not. The above two graphs show the distribution of students in these two groups. With an alpha value of 0.05 and a p-value of 0.02331, we rejected the null hypothesis of no difference and concluded that there is a significant difference in mean systolic blood pressure in people who consumed caffeine in the past hour and people who did not consume caffeine in the past hour. 
  </p>
   
  <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin: 20px 0;">
    <img src="{{site.baseurl}}/images/templates/assignments/sp1.png" style="width: 300px; height: auto;" />
    <img src="{{site.baseurl}}/images/templates/sp5.png" style="width: 300px; height: auto;" />
  </div>

  <p>
    &emsp;Another test that we performed was a Fisher’s Exact Test that examined the association between sex and recent caffeine consumption. The above plot helps visualize the data, and the results of the test (p-value of 0.3403) mean that we fail to reject the null hypothesis, suggesting no significant relationship between sex and the likelihood of caffeine consumption in the past hour. The other test looked at the mean systolic blood pressure before and after occlusion, the mean systolic blood pressure compared to the known mean of 120 mmHg, and the correlation between weight and blood pressure. This project provided valuable practice in statistical reasoning and data visualization, strengthening my ability to interpret real-world biomedical data using RStudio. 
  </p>
