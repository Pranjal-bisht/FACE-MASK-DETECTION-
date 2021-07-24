# FACE-MASK-DETECTION-

Real time face-mask detection using Deep Learning and OpenCV

# About Project

This project uses a Deep Neural Network, more specifically a Convolutional Neural Network, to differentiate between images of people with and without masks. The CNN manages to get an accuracy of 98.2% on the training set and 97.3% on the test set. Then the stored weights of this CNN are used to classify as mask or no mask, in real time, using OpenCV. With the webcam capturing the video, the frames are preprocessed and and fed to the model to accomplish this task. The model works efficiently with no apparent lag time between wearing/removing mask and display of prediction.

**The model is capable of predicting multiple faces with or without masks at the same time.**
**WITHOUT MASK**
![img_nomask](https://user-images.githubusercontent.com/58468853/126859175-aa504288-d1f9-4a09-bede-1e5ec7661cd1.PNG)
**WITH MASK**
![img_mask](https://user-images.githubusercontent.com/58468853/126859177-cc25866b-e200-4aef-b0c6-67be18c00735.PNG)

The data used can be downloaded through this [link](https://data-flair.training/blogs/download-face-mask-data/). 
There are 1314 training images and 194 test images divided into two catgories, with and without mask.
