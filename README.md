﻿# Sign-language-detection
Overview

This project is a Sign Language Detection System that utilizes the TensorFlow Object Detection API and machine learning algorithms. The system is manually trained with hand gestures to recognize signs and convert them into text output, making it highly beneficial for individuals who communicate using sign language.

Features

Detects and recognizes hand gestures in real time.

Uses TensorFlow Object Detection API for training and detection.

Converts detected gestures into corresponding text output.

Helps non-verbal individuals communicate more easily.

Project Structure

├── Logs/train        # Training logs
├── MP_Data           # Data collected for training
├── __pycache__       # Compiled Python files
├── image/            # Folder containing trained images
├── README.md         # Project documentation
├── app.py            # Main application script
├── colledtdata.py    # Script to collect training data
├── data.py           # Data processing script
├── function.py       # Helper functions
├── model.h5          # Trained machine learning model
├── model.json        # Model architecture in JSON format
├── trainmodel.py     # Script to train the model using recorded images

Installation

Clone the repository:

git clone <your-repository-link>
cd <your-repository-name>

Install required dependencies:

pip install -r requirements.txt

Ensure you have TensorFlow, OpenCV, and other dependencies installed.

Usage

Collect Training Data

python colledtdata.py

This script records images for training.

Train the Model

python trainmodel.py

This script trains the model using recorded images.

Run the Application

python app.py

This script starts the sign language detection system.

Contributing

Feel free to fork this repository and contribute by submitting pull requests.
