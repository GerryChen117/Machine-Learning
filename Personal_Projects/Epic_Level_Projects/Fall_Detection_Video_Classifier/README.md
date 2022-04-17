# Project Overview

## Context
For Canadians, falls are a leading cause of injury-related hospitalizations for those aged 65 or older. Not only do they lead to negative physical consequences such as broken or fractured bones, they also pose a risk to the individual's mental health. In fact, statistics indicate that 20 to 30 percent of seniors fall each year, where each fall harms not only the injured individual, but affects family, friends, care providers, and the health care system. 

This project focuses on detecting falls from a video dataset with a high degree of accuracy. Further extensions to this project are to detect discrepancies in more complex models, such as identifying movement disorders and gait symptoms.

## Work Done 
A ConvLSTM2D was constructed using Keras to analyze video data and train a classification model. The two types of videos are labelled: 'fall' or 'adl' (activities of daily living). The video dataset was split into training, validation, and test sets. A final test accuracy of 90.71% was achieved. 

## References
**The dataset used for this model comes from:** 

Bogdan Kwolek, Michal Kepski, Human fall detection on embedded platform using depth maps and wireless accelerometer, Computer Methods and Programs in Biomedicine, Volume 117, Issue 3, December 2014, Pages 489-501, ISSN 0169-2607 [Link](http://home.agh.edu.pl/~bkw/research/pdf/2014/KwolekKepski_CMBP2014.pdf)