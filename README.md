# covid19-face-mask-detection-with-deep-learning
# COVID-19-Face-Mask-Detector-with-OpenCV-TensorFlow-and-Deep Learning


The objective of this project is to detect the face of a person whether the person wears a mask or not with regard to the current pandemic situation . 

So we will build my model from scratch as we will take 500 images of people wearing masks and 500 images of people not wearing masks .
We will build a model with the help of deep learning , tensorflow, so that the model will train on the datasets and will give good accuracy by detecting the face of the person and then the model will classify it properly . 

We will build the whole model in two phases .

Phase 1 - Train Face Mask Detector 
Phase 2 - Apply Face Mask Detector 

Objective of both phases : 

First we will train our model then used for detections Training: Here we’ll focus on loading our face mask detection dataset from disk, training a model (using Keras/TensorFlow) on this dataset, and then serializing the face mask detector to disk Deployment: Once the face mask detector is trained, we can then move on to loading the mask detector, performing face detection, and then classifying each face as with_mask or without_mask . 





In order to train a custom face mask detector, we need to break our project into two distinct phases, each with its own respective sub-steps (as shown by Figure 1 above):

Training: Here we’ll focus on loading our face mask detection dataset from disk, training a model (using Keras/TensorFlow) on this dataset, and then serializing the face mask detector to disk
Deployment: Once the face mask detector is trained, we can then move on to loading the mask detector, performing face detection, and then classifying each face as
 with_mask
 or
 Without_mask
Our COVID-19 face mask detection dataset

