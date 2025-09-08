---
title: Circuit Project - ECG PCB and Circuit Design
layout: product
description_markdown: >-
  Designing a custom printed circuit board to measure an ECG signal. 
date: 2020-01-21 23:12:06 +0100
text-button: I need this template to write my script!
image: /images/templates/screenplay/CircuitMain.jpg
---
<div style="max-width: 1000px; margin: 0 auto; padding: 20px;">
  <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin: 20px 0;">
    <img src="{{site.baseurl}}/images/templates/screenplay/CircuitMain.jpg" style="width: 300px; height: auto;" />
    <img src="{{site.baseurl}}/images/templates/c10.png" style="width: 300px; height: auto;" />
  </div>
  <h3>Class: BME 214L: Computational Fundamentals of BME Design</h3>
  <h3>Semester: Fall 2024</h3>
  <h3>Skills: TinkerCad, Fusion 360, soldering, LabVIEW</h3>
  
  <p>
    &emsp;The goal of this project was to use TinkerCad and Fusion 360 to design and implement a biomedical circuit capable of capturing and processing electrocardiogram (ECG) signals. Our final ECG signal utilized three electrodes and was composed of several key components, such as a voltage follower to help power the circuit, an instrumentation amplifier to amplify the signal, a high-pass filter to eliminate DC content, and finally a low-pass filter to remove high-frequency noise. TinkerCad was used during this project to test our circuit configurations before we built them on an ElvisBoard. 	
  </p>

  <img src="{{site.baseurl}}/images/templates/c9.png" style="display: block; margin: 0 auto;   width: 100%; max-width: 600px;" />
  
  <p>
    &emsp;We began by prototyping individual circuit elements - voltage follower, high-pass filter, and low-pass filter - on the Elvis Board, validating each stage before integration. Once the core components were tested, we designed the full schematic on Fusion 360 (pictured above). After finalizing resistor and capacitor values, we converted the schematic into a compact PCB layout. Upon receiving the fabricated PCB, we soldered components incrementally, testing each stage to ensure signal integrity before proceeding.
  </p>
   
  <img src="{{site.baseurl}}/images/templates/c3.png" style="display: block; margin: 0 auto;   width: 100%; max-width: 600px;" />

  <p>
  &emsp;	To acquire the final ECG signal, we connected the circuit’s output to the ElvisBoard, which interfaced with LabVIEW for real-time signal visualization. The resulting signal (shown above) demonstrated successful signal acquisition. However, the signal would often get less defined when electrode wires were tangled or subjected to excessive movement. Minimizing exposed wire could significantly enhance signal stability and reduce noise. 
  </p>

