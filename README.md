# DL-Face-Counting-Challenge

### Problem Statement:

People detection and head counting is one of the classical albeit challenging computer vision application. For this problem, given a group selfie/photo, you are required to count the number of heads present in the picture. You are provided with a training set of images with coordinates of bounding box and head count for each image and need to predict the headcount for each image in the test set.
Evaluation Metric

The evaluation metric for this competition is RMSE (root mean squared error) over the head counts predicted for test images.


### Approach:

Used the exisitng Haar Cascade frontal face of open CV.
also, used deep learning to train the CNN model.

Got RMSE of 2.211
