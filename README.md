# Sign Language Detection System

## Overview
This project is a **Sign Language Detection System** that utilizes the **TensorFlow Object Detection API** and machine learning algorithms. The system is manually trained with hand gestures to recognize signs and convert them into text output, making it highly beneficial for individuals who communicate using sign language.

## Features
- Detects and recognizes hand gestures in real time.
- Uses **TensorFlow Object Detection API** for training and detection.
- Converts detected gestures into corresponding text output.
- Helps non-verbal individuals communicate more easily.

## Project Structure
├── Logs/train # Training logs ├── MP_Data # Data collected for training ├── pycache # Compiled Python files ├── image/ # Folder containing trained images ├── README.md # Project documentation ├── app.py # Main application script ├── colledtdata.py # Script to collect training data ├── data.py # Data processing script ├── function.py # Helper functions ├── model.h5 # Trained machine learning model ├── model.json # Model architecture in JSON format ├── trainmodel.py # Script to train the model using recorded images

bash
Copy
Edit

## Installation
1. Clone the repository:
   ```bash
   git clone <your-repository-link>
   cd <your-repository-name>
2. Install required dependencies:
   ```bash
   pip istall -r requirements.txt

Ensure you have TensorFlow, OpenCV, and other dependencies installed.
## Usage
1. Collect Training Data:
   ```bash
   python collectdata.py
   #This script records images for training.
2. Train the model:
   ```bash
   python trainmodel.py
   #This script trains the model using recorded images.
3. Run the Application:
   ```bash
   python app.py
   #This script starts the sign language detection system.

Contributing: 
Feel free to fork this repository and contribute by submitting pull requests.







