# IndianTrafficSignPrediction
This project involves developing a web-based application for predicting Indian traffic signs using a Convolutional Neural Network (CNN) model, integrated with the Flask framework. The primary objective is to create a user-friendly interface for traffic sign recognition, aiding drivers and learners in understanding and adhering to road safety regulations.

Key Features:
1. Deep Learning Model:
Built using a CNN architecture.
Trained on a dataset of Indian traffic signs to achieve high accuracy in classification.
Model capable of identifying and predicting various traffic signs (e.g., Stop, Speed Limit, No Parking).

2. Flask Framework:
Lightweight web framework used for integrating the model with a web application.
Enables users to upload traffic sign images for real-time prediction.

3. Web Interface:
Simple and intuitive design for user interaction.
File upload option to allow users to input traffic sign images.
Display of the predicted traffic sign with its description.

4. Technologies Used:
Backend: Flask framework for handling HTTP requests and interfacing with the CNN model.
Frontend: HTML for a responsive and clean user interface.
Model Training: TensorFlow/Keras for building and training the CNN model.

Implementation Steps:
1. Data Preparation:
Collected a dataset of Indian traffic signs and preprocessed images (resizing, normalization).
Split the dataset into training and validation sets.

2. Flask Integration:
Saved the trained model as a .h5 file.
Created a Flask app to load the model and handle image uploads.
Deployed the app to provide real-time predictions.

Applications:
Assists drivers and learners in recognizing and understanding traffic signs.
Educational tool for training purposes in driving schools.
