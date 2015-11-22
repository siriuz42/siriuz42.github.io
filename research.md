---
layout: default
title: Research
---

Research
=========

Random Forest and Tree Approximation
---------

This project is advised by <a href="http://faculty.bscb.cornell.edu/~hooker/">Prof. Hooker</a> and is still ongoing. The original question derives from a clinical issue of developing an adaptive depression diagnosis method. Decision trees were first implemented for their intrinsic intepretibility, but turned out to be unsatisfying for its inevitable sensitivity caused by outliers during training processes. Our solution is to combine the interpretibility of decision trees and the robustness of random forests to build a model obtaining the balance among specificity, sensitivity and interpretibility.

So far I have done the key theoretical analysis of finding the assymptotic relation between the tree building procedure and its associated confidence level. Simulations are still running to conclude the final performance.

Multivariate Time Series Classification by Dynamic Time Warping 
---------

This project is a joint work with Skyler Seto and Wenyu Zhang. Our interest of time series classification originated from the fashion of smartphones and their gravitaional sensors, whose most typical usages nowadays relate to human body monitoring and notifications, e.g. calories burnt, running distances, heart rates. 

The essential question lying behind is to properly classify time series readings to their activities. For instance, it will be quite informative to estimate the calorie consumption if we can identify a moving person to be jogging, biking or skiing. Classic machine learning schemes follow the feature extraction -> classification procedure. Hundreds of features will be generated and later put into any classifiers like trees or SVMs to provide models. They have achieved high accuracy, while at the same time lack the reasoning of feature selection. 

We intended to try this algorithm, time series warping, on this question due to its ability to directly adjust and compare time series. It is theoretically fast, and easier to interpret. 

Bayesian 3D Reconstruction
----------

This project was advised by Dr. Ke Deng during my visit at Yau Mathematics Science Center. 





