Image Forgery Detection System
Overview

Python TensorFlow Keras CNN Error Level Analysis Flask

This project is an AI-based image forgery detection system designed to identify manipulated digital images using deep learning and forensic analysis techniques. It focuses on detecting common tampering methods such as copy-move forgery, image splicing, and retouching, while also highlighting altered regions for better interpretability.

The system combines Convolutional Neural Networks (CNN) with Error Level Analysis (ELA) to provide accurate classification and visual evidence of image manipulation.

Screenshots

(Add screenshots of uploaded image results, heatmaps, and UI if available)

Main Interface
Forgery Detection Output
Tampered Region Visualization

Features
Core Functionality

Deep learning-based image forgery classification

Error Level Analysis for manipulation detection

Localization of tampered regions

Support for multiple forgery types

Fast and automated image authenticity checking

Simple and intuitive user interface

Application Workflow

User uploads an image

Image undergoes preprocessing and ELA transformation

CNN model analyzes authenticity

Forgery type is predicted

Manipulated regions are highlighted

Technologies Used
Machine Learning & AI

Python

TensorFlow

Keras

Convolutional Neural Networks (CNN)

Error Level Analysis (ELA)

Backend

Flask

NumPy

OpenCV

Frontend / Interface

PyQt or Web Interface (HTML, CSS, JavaScript)

Getting Started
Prerequisites

Python 3.8+

pip

Installation

Clone the repository:

git clone https://github.com/your-username/image-forgery-detection-system.git
cd image-forgery-detection-system


Install dependencies:

pip install -r requirements.txt

Running the Application
python app.py


Upload an image and view forgery detection results.

Project Structure
image-forgery-detection-system/
│
├── dataset/
├── models/
├── preprocessing/
├── scripts/
├── app.py
├── requirements.txt
└── README.md

Use Cases

Digital forensics investigations

Fake image detection on social platforms

Media authenticity verification

Cybercrime analysis

Academic research

Future Enhancements

Deepfake image and video detection

Real-time camera input analysis

Cloud-based deployment

Mobile application integration

Improved explainable AI visualizations

Author

Diya Shetty
BE CSE Student | AI & Full Stack Developer

This project was adapted, implemented, and enhanced for academic and learning purposes.

Contributing

Contributions are welcome.

Fork the repository

Create a feature branch

Commit your changes

Submit a pull request
