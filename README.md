# Animal_Detector
# Project Overview

This project is a machine learning-based image classifier that predicts the composition of animals in a given image. The model is trained to recognize five animals—Panda, Zebra, Monkey, Tiger, and Elephant—and outputs the exact percentage of each animal detected in an image.

The project demonstrates skills in:

Machine learning model development using Teachable Machine

Client-side inference with TensorFlow.js

Web deployment using AWS S3 Static Website Hosting

Frontend development with HTML, CSS, and JavaScript

# Features

Upload an image of animals directly through the browser.

Click Detect to run the model and see predictions.

Displays confidence percentages for each animal class.

Responsive UI with a loading spinner while predictions are computed.

Fully hosted in the cloud—no backend server required.

# Technologies Used

Teachable Machine – For training the ML model.

TensorFlow.js – For running the model in-browser.

AWS S3 – Hosting the static website and model files.

HTML, CSS, JavaScript – Frontend interface.

# How It Works

Model Loading: The website loads the ML model and metadata from the Animal_Detector folder.

Image Upload: The user selects an image file (.jpg, .jpeg, .png, etc.).

Prediction: Clicking Detect runs the model on the uploaded image.

Output: The page displays the confidence percentage for each animal class.

# Future Improvements

-Expand the model to detect additional animals.

-Add batch image processing to analyze multiple images simultaneously.

-Implement a progressive web app (PWA) for offline use.

-Integrate more advanced visualization for prediction results (e.g., bar charts or heatmaps).
