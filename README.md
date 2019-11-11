# Google Landmark Recognition 2019

## Context
Today, a great obstacle to landmark recognition research is the lack of large annotated datasets. In the Kagglecompetition, a largest worldwide dataset to date, to foster progress in the problem. This competition challenges Kagglers to build models that recognize the correct landmark (if any) in a dataset of challenging test images.

Many Data Scientists are familiar with image classification challenges like the ImageNet Large Scale Visual Recognition Challenge (ILSVRC), which aims to recognize 1K general object categories. Landmark recognition is a little different from that: it contains a much larger number of classes (there are more than 200K classes in this challenge), and the number of training examples per class may not be very large. Landmark recognition is challenging in its own way.

This is the second edition of this Google Landmark Recognition challenge. Compared to the first edition, the new dataset is more comprehensive and diverse. 

This challenge is organized in conjunction with the Landmark Retrieval Challenge (https://www.kaggle.com/c/landmark-retrieval-2019 ). In particular, note that the test set for both challenges is the same, to encourage participants to compete in both.

### Understanding the Data

The training set was constructed by clustering photos with respect to their geolocation and visual similarity using an algorithm. Matches between training images were established using local feature matching. Note that there may be multiple clusters per landmark, which typically correspond to different views or different parts of the landmark. To avoid bias, no computer vision algorithms were used for ground truth generation. Instead, we established ground truth correspondences between test images and landmarks using human annotators.

## Jupyter Notebook
In this Jupyter Notebook, I have tried to do an Extensive Exploratory Data Analysis of Google Landmark Recognition Challenge from Displaying various Landmarks to Famous Landmarks.