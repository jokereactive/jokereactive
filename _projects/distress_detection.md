---
layout: page_project
name: Distress Detection
title: Distress Detection
intro: based on Speech
teamsize: 2
teammembers: Anil Sharma, PhD Candidate IIIT-Delhi
guide: Dr. Sanjit Kaul
projectimage: sample.png
_url: 
weight: 2
id: distressdetection
images:
 - image_id: image1.PNG
 - image_id: image2.PNG
reference: http://sarthakahuja.org/public/docs/report_dd.pdf
code: 
category: Research
database: 
demo: 
special: Elevator Pitch, First Prize at Research Showcase'14
technology: Machine Learning, Android, PHP, Matlab, Signal Processing
period: Aug'14-present
excerpt: In this project we used audio data to detect distress in the ambient surroundings (Screams) by using trained SVMs. I worked on this project for a year and coded multiple implementations, on android and matlab. I implemented various additional features such as silence removal and spectral-feature computation. I also implemented the dashboard used to monitor the entire system in real time and push our updated application to volunteer devices. 
---
In this project we used audio data to detect distress in the ambient surroundings (Screams) by using trained SVMs. I worked on this project for a year and coded multiple implementations, on android and matlab. My work also involved testing the algorithm performance, collecting data, testing classifiers and designing the monitoring dashboard. Our proposed system leverages the microphone sensor of a smartphone that continuously listens to the environmental context audio. The accuracy of audio based systems drop in the presence of environmental noise. We use Mel-Frequency Cepstral Coefficients (MFCC) and spectral features to represent the features of the distress and other context audio samples. We proposed a multi-stage supervised learning framework that is trained to detect screaming and crying, which are known vocal expression of fear circumstance. The learning framework contains Scream Detection and Environment Rejection algorithms that use Support Vector Machines (SVM) which are tuned to achieve high confidence of distress in the test audio. 

We demonstrated the effect of various environmental context on distress detection at different SNR(s). Our framework adapts itself to a context to achieve a desirable detection rate and False Alarm Rate (FAR) trade-off using different point(s) of operation. We also proposed two adaptive ‘point of operation’ selection techniques to select best point of operation in real-time. The accuracy gets affected due to both false alarms from environment context audio and also when SNR of the distress signal is low. To evaluate our algorithm we had volunteers use our application for a month and provide us real time data which was monitored on the dashboard I designed. We also made our own application update system to push the updated application to all volunteers. We achieved an accuracy of 93.1% with an error rate of less than 1.5%. It all culminated in us winning the ‘Elevator Pitch” competition for the Best Poster and Demo at the Research Showcase’15 (IIIT-Delhi). 