# AI-Based Cotton Leaf Disease Detection and Treatment Recommendation System

## Project Brief
This project proposes an Android application that uses a deep-learning image-classification model to help identify selected cotton leaf conditions from a photograph. A user will capture a leaf image or select one from the phone gallery. The app will display a predicted class, a confidence score, and general disease information with prevention/treatment guidance based on reliable agricultural sources.

The app is intended as a preliminary decision-support tool, not a confirmed diagnosis or a replacement for an agricultural expert.

## Planned Classes
Initial candidate classes (to be finalized after checking the chosen dataset):
- Healthy Cotton Leaf
- Cotton Leaf Curl Virus
- Bacterial Blight
- Alternaria Leaf Spot
- Cercospora Leaf Spot

Only classes with sufficient, clearly labelled images will be included in the final model.

## Planned Features
- Capture a cotton leaf photo or select one from gallery
- Classify selected cotton leaf conditions with a trained model
- Show predicted class and model confidence
- Display reviewed symptom, prevention, and treatment information
- Optional scan history

## Technologies
- Python, TensorFlow/Keras
- CNN / transfer learning (for example, EfficientNetB0)
- Kotlin and Android Studio
- OpenCV or Pillow for image handling
- FastAPI if a backend API is used
- Git and GitHub

## Repository Status
This repository contains starter documentation. The model and Android app are planned work and have not been implemented yet.

## Dataset
See [`dataset/README.md`](dataset/README.md) for candidate sources and checks to complete before training.

## Safety Note
A model prediction can be wrong, especially for poor-quality images or symptoms that look similar. Treatment information should be verified with trusted agricultural sources and local agricultural experts. Do not use the app as the sole basis for pesticide selection or dosage.
