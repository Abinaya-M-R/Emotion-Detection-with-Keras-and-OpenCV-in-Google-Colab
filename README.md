#  Emotion Detection Using Keras and OpenCV

## About the Code

This project performs facial emotion detection in images using deep learning and computer vision. The script uses a pre-trained model to predict emotions and OpenCV to detect faces in images. It's designed to run efficiently in Google Colab or any Python environment.


## Code Breakdown

### 1. **Importing Libraries**

The script begins by importing necessary libraries such as Keras for deep learning, OpenCV for image processing and face detection, NumPy for data handling, and Colab utilities for uploading and displaying images.


### 2. **Loading the Pre-trained Model**

A pre-trained deep learning model (mini\_XCEPTION trained on FER2013) is loaded. This model is capable of recognizing seven basic human emotions based on facial expressions.


### 3. **Emotion Labels**

A list of seven emotion labels is defined to interpret the model's output. These labels are: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.


### 4. **Face Detection**

The script uses OpenCV’s Haar Cascade Classifier to locate faces in the input image. This method scans the image and returns coordinates for detected face regions.


### 5. **Emotion Detection Function**

A custom function is defined to:

* Convert the image to grayscale.
* Detect faces in the image.
* Extract and preprocess each face region.
* Use the model to predict the emotion.
* Draw rectangles around faces and annotate them with the predicted emotion label.

### 6. **Image Upload and Processing**

Users can upload image files. For each uploaded image, the script detects faces and displays the image with emotion labels overlaid on detected faces.

## Summary

This code offers a simple, effective way to detect emotions from facial expressions using machine learning and image processing. It's ideal for students, researchers, and developers interested in emotion recognition systems.


