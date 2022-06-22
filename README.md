# Naruto-Hand-Sign-Classification

This is a project based on the well-known famous Japanese Animated Series "Naruto" by Masashi Kishimoto. In the show, the ninjas weave various hand-signs combinations as a way to use their techniques referred to as jutsus. This project attempts to use Deep Learning and Computer Vision techniques to identify what handsign an individual has made. 

## Models

MobileNetV2, ResNet50, VGG16, and InceptionV3 models were chosen for the classification task. Out of the four models, VGG16 performed the best at an accuracy of **93.60%** for the test dataset as well as a minimum accuracy of **83.33%** for the live demo.

Architecture of the VGG16 model is shown below.

**![image](https://user-images.githubusercontent.com/74623611/174507226-39e2be13-ff11-4697-b0c2-f2b2a9123474.png)**

See links below for details of the four models.
1. [MobileNetV2](https://keras.io/api/applications/mobilenet/)
2. [ResNet50](https://www.tensorflow.org/api_docs/python/tf/keras/applications/resnet50/ResNet50)
3. [VGG16](https://keras.io/api/applications/vgg/)
4. [InceptionV3](https://keras.io/api/applications/inceptionv3/)

## Data

The data used in this project was manually collected and augmented by recording a video from a webcam utilizing OpenCV, following a number of data-augmentations such as flips and rotations to increase dataset size.


## Packages Used
The requirements for the project are as follows: <br>
1. Python=3.7.7
2. Tensorflow=2.8.0
3. OpenCV=4.6.0.66
4. Numpy=1.21.5
5. Pillow=9.1.0
6. Mediapipe=0.8.10

