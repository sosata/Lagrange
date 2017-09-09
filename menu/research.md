---
layout: page
title: ""
---

## Education

I received my PhD in Computer Science (Computational Neuroscience) from Goethe-Universität Frankfurt, Germany, focusing on modeling the neurocomputational mechanisms of coordinated eye and head movements in primate brain. I used artificial neural networks and reinforcement learning to model [adaptive control of saccades](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002253) and to deal with [uncertainty in active vision](http://www.sciencedirect.com/science/article/pii/S0893608009001245?np=y). My current research at Northwestern University focuses on the application of machine learning and sensor technology to mental healthcare, where I use the sensor data collected from smartphones and wearable devices to infer information about different aspects of individuals' daily-life behaviors and their environments (see below).

## Current Research

### Life Sensing

Depression and anxiety are among major health concerns and a growing problem in the modern society. Smartphones and wearable devices, with the variety of sensors (e.g. GPS, accelerometer, and microphone) and other sources of information (e.g., call, sms, and games) can potentially act as bio-markers of depression and anxiety in daily life, providing an opportinuty to more closely investigate the life-long trajectory of these illnesses.

The goal of this project is to investigate if smartphone sensor data can be used to (1) distinguish between depressed and non-depressed individuals, (2) predict the severity of the disease, and (3) predict the future trajectory that the disease takes in an individual. We have been able to do this using GPS data in a [small study](http://www.jmir.org/2015/7/e175/), which was successfully replicated on an independent dataset [StudentLife](http://studentlife.cs.dartmouth.edu/). We are now collecting data from 240 individuals to extend our findings to other aspects of life including sleep, social interactions, and physical activity.

### Adversarial Activity Recognition

Current smartphone and wearable sensor technologies allow us to detect a person's physical activities such as walking, biking, or being still. In many circumstances, however, there are strong incentives for users to trick the activity trackers into detecting activities other than the ones they actually perform. For example, one can make their pedometer count steps by shaking their device (many more ways shown [here](http://www.unfitbits.com/)). In fact, current activity recognition technology is only reliable in normal conditions, and thus vulnerable to deceptive behavior. The aim of this project is to develop a methodology that enables smartphone-based activity recognition to overcome this limitation.

We have already conducted a [study](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0144795), in which we asked volunteers to deliberately make the activity tracker fail, and then used those data to re-adapt the tracker. We aim to extend our methodology to more challenging tasks as well as other modalities in future.

### Cross-Validation in Clinical Predictions

The application of machine learning in clinical predictions is rapidly growing. Examples range from using accelerometers to detect the severity of Parkinson's disease to [analyzing speech for predicting the onset of psychosis](http://www.nature.com/articles/npjschz201530). A crucial step in using machine learning is to properly evaluate their accuracy, and this is performed through various cross-validation methods.

In a recent study ([preprint](http://biorxiv.org/content/early/2016/06/19/059774)), we showed how a popular cross-validation method massively overestimates the prediction accuracy of the algorithms. We also performed a systematic review of the literature, and showed that about 45% of the studies using machine learning for clinical predictions have used the wrong method. The results will be published in _GigaScience_.