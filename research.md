---
layout: default
title: Research
---

Research
=========

Random Forest and Tree Approximation
---------

This project is advised by <a href="http://faculty.bscb.cornell.edu/~hooker/">Prof. Hooker</a> and is still ongoing. The original question derives from some clinical issue of developing an adaptive depression diagnosis method. Decision trees were first implemented for their intrinsic intepretibility, but turned out to be unsatisfying for their inevitable sensitivity introduced by outliers during training processes. Our solution is to combine the interpretibility of decision trees and the robustness of random forests together to build a model attaining the balance among specificity, sensitivity and interpretibility.

So far I have done the key theoretical analysis of finding the assymptotic relation between the tree building procedure and its associated confidence level. Simulations are still running to conclude the final performance. 


Multivariate Time Series Classification by Dynamic Time Warping 
---------

This project is a joint work with Skyler Seto and Wenyu Zhang. Our interest of time series classification originated from the fashion of smartphones and their accelerometers, whose most typical usages nowadays relate to human activity monitoring and notifications, e.g. calories burnt, running distances, heart rates. 

The essential question lying underneath is to properly classify time series readings to their activities. For instance, it will be more informative to accurately estimate the calorie consumption if we can identify a moving person to be jogging, biking or skiing. Classic machine learning schemes follow the feature extraction -> classification procedure. Hundreds of features will be generated and later put into any classifiers like trees or SVMs to reproduce models. They have achieved high accuracy, whereas at the same time lack the reasoning of feature selection. 

We intended to try the algorithm, time series warping, on this question due to its ability to directly adjust and compare time series. It is theoretically fast, and easier to interpret. Relevant codes in Python can be found <a href="https://github.com/skyler120/TSClass">here</a> on GitHub. 


Bayesian 3D Reconstruction
----------

This project was a joint work with <a href="https://www.linkedin.com/in/chenchengcai">Chencheng Cai</a> advised by Dr. Ke Deng during my visit at Yau Mathematics Science Center. It attempted to fulfill large scale crowd monitoring through a novel Bayesian approach. Previous reseaches had been done on the video from a single surveillance camera. After feature extraction and regression they would give a vaguely estimate of the size of the crowd in the scene. We tried to adapt the setting to be multi-camera and use the images from various aspects to get a more accurate counting method. The key idea was to first segment the scene as a 2D grid on the level ground, then utilize Markov Chain Monte Carlo to sample the height distribution with the videos of those multiple cameras. 

The work was temporarily suspended after our visit ended.

Protein Image Processing
----------

This was a supportive work for the <a href="http://life.tsinghua.edu.cn/english/faculty/faculty/658.html">Yu Li Lab</a> at Tsinghua. In the lab there were massive images of various proteins of which we could see their tube-shaped structures, and there had been no handy image processing software to measure the lengths of these tubes and to summarize their distributions. I coded a light tool in C++ with OpenCV package and a little innovation to help them deal with this problem. A probabilistic algorithm was invented to detect the boundary and in advance to see whether a pixel was within a tube. If so, it would grow along a geometric central path to detect and segment a complete tube. Relevent code in C++ can be found <a href="https://github.com/siriuz42/ProteinCount">here</a> on GitHub.






