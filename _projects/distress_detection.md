---
layout: page_project
name: Distress Detection
title: Distress Detection
intro: 
teamsize: 2
teammembers: Anil Sharma, PhD Candidate IIIT-Delhi
guide: Dr. Sanjit Kaul
projectimage: dd.png
_url: 
weight: 5
id: distressdetection
images:
reference: http://sarthakahuja.org/public/docs/report_dd.pdf
code: 
slides: slides_dd.pdf
poster: 
category: Research
database: https://www.iiitd.edu.in/~anils/taslp/taslp_distress_detection.html
demo: 
special: Best Demo, Research Showcase'14, IIIT-Delhi
technology: Machine Learning, Android, PHP, Matlab, Signal Processing
period: Aug'14-May'15
excerpt: We investigate an unobtrusive and 24×7 human distress detection and signaling system, Always Alert, that requires the smartphone, and not its human owner, to be on alert. The system leverages the microphone sensor, at least one of which is available on every phone, and assumes the availability of a data network. We propose a novel two-stage supervised learning framework, using support vector machines (SVMs), that executes on a user’s smartphone and monitors natural vocal expressions of fear — screaming and crying in our study — when a human being is in harm’s way.
---
We investigate an unobtrusive and 24×7 human distress detection
and signaling system, <b>Always Alert</b>, that requires
the smartphone, and not its human owner, to be on alert.
The system leverages the microphone sensor, at least one of
which is available on every phone, and assumes the availability
of a data network. We propose a novel two-stage supervised
learning framework, using support vector machines
(SVMs), that executes on a user’s smartphone and monitors
natural vocal expressions of fear — screaming and crying in
our study — when a human being is in harm’s way. The challenge
is to achieve a high distress detection rate while ensuring
that the false alarm rate is a manageable overhead, while
a typical smartphone user goes about living life as usual. We
train the learning framework with carefully selected audio
fingerprints of distress and of varied environmental contexts.
The audio is used to tune the learning framework to obtain a
desirable distress detection rate and false alarm rate (FAR).
The ability of the proposed framework to detect distress in
rather challenging audio environments is demonstrated. 

I worked on this project for a year and coded multiple implementations, on android and matlab. My work also involved testing the algorithm performance, collecting data, testing classifiers and designing the monitoring dashboard. 

<img src="{{ site.projectimagesurl }}/distressdetection/app_sample.png">

We demonstrated the impact of environmental context on the detection rate and False Alarm Rate (FAR) trade-off using different point(s) of operation and made the system adaptive to these contexts through environment rejection. We also perform a detailed assesment of the power consumption of the application and optimize the application to run for longer periods through selective classification.
Our analysis is based on a user study conducted on 16 volunteers(250hrs data). We monitored the data collection through our dashboard and also identified large-scale and recurring distress patters through clustering and rule-mining. 

<div class="w3-content w3-display-container">
  <img class="mySlides" src="{{ site.projectimagesurl }}/distressdetection/screen1.png" style="width:100%">
  <img class="mySlides" src="{{ site.projectimagesurl }}/distressdetection/screen2.png" style="width:100%">
  <img class="mySlides" src="{{ site.projectimagesurl }}/distressdetection/screen3.png" style="width:100%">
</div>
<br>
Our final implementation achieved an accuracy of 93% with an error rate of 1.5%. Exploiting
the time contiguous nature of false alarms further
allows us to reduce the FAR. We show the feasibility of using
our framework anytime and anywhere by testing it over
many hours of audio fingerprints recorded by volunteers on
their smartphones, as they went about their daily routines.
We are able to achieve high distress detection rates at an average
overhead that is equivalent to about 1 facebook post
every 3 to 4 hours. 



