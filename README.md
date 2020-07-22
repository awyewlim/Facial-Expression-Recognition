# Facial Expression Recognition

This repository is to build and train a convolutional neural network (CNN) in [Keras](https://keras.io/) from scratch to recognize facial expressions. The data consists of 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

Dataset : FER 2013 dataset

## Key Concept

- Develop a facial expression recognition model in Keras
- Build and train a convolutional neural network (CNN)
- Deploy the trained model to a web interface with [Flask](https://flask.palletsprojects.com/en/1.1.x/)
- Apply the model to real-time video streams and image data

## Structure
- Explore dataset
- Generate Training and Validation Batches
- Create a Convolutional Neural Network (CNN) Model
- Represent Model as JSON String
- Create Flask App to Serve Predictions
- Design HTML Template for the Flask App
- Use Model to Recognize Facial Expressions in Videos

## Guide
- Set **Terminal** Path to '''cd \path\to\Project\'''
- Run 'python3 main.py'
