Use the following drive link to find the hdf5 file(plant_disease.h5): https://drive.google.com/file/d/1xA2RETh30mybyxxxlgo2y6EqGFhMkAV8/view?usp=sharing
Overview
This project is a Plant Disease Prediction System that integrates a machine learning (ML) model with a Flask-based backend and a frontend interface. The model predicts plant diseases from uploaded images using a pre-trained deep learning model and gives us an accuracy of 90%.
Features
Frontend: User-friendly interface for uploading images.
Backend (Flask API): Processes uploaded images, makes predictions, and returns results.
Machine Learning Model: A deep learning model trained to classify plant diseases.
Deployment-ready: Can be hosted on a cloud server or local machine.
/plant-disease-prediction
│── /static              # Static files (CSS, JavaScript, Images)
│── /templates
│   └── index.html       # Web UI for uploading images
│── plant_disease.h5     # Trained deep learning model
│── class_indices.pkl    # Class mapping of diseases
│── app.py               # Flask application (backend)
│── requirements.txt     # Required dependencies
│── ML model(trained)    # DenseNet pretrained model with 90% accuracy

Backend (Flask API)
How It Works:
The user uploads a plant image.
The image is resized, normalized, and passed to the model.
The model predicts the plant disease.
The API returns the predicted disease label.


Frontend
The frontend consists of an HTML form where users can upload images. It uses JavaScript to send the image to the Flask API and display results.

Model Details
Built using TensorFlow/Keras.
Pre-trained on a dataset of plant disease images using DenseNet121.
Saved in HDF5 format (plant_disease.h5).
Uses a 256x256 pixel input image size.

Future Improvements
Add more plant species and disease categories.
Improve accuracy with a larger dataset.
Develop a mobile app for easy disease detection.

Author
Auryn Leon DCosta
Contact: auryndcosta@gmail.com
GitHub: auryndcosta
