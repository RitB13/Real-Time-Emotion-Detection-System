# Real-Time-Emotion-Detection-System
This project implements a real-time emotion detection system using Deep Learning techniques, leveraging a Convolutional Neural Network (CNN) and the FER-2013 dataset to classify facial expressions into seven emotion categories: happy, sad, anger, fear, disgust, surprise, and neutral.

The system uses OpenCV for real-time face detection via webcam and TensorFlow and Keras for deep learning model development. This application can detect emotions from live video input and display the detected emotion in real-time.

## Dataset
The model is trained on the FER-2013 dataset, which consists of 35,887 grayscale images of size 48x48 pixels, each labeled with one of the seven emotions.
Note: Due to GitHub's file size limitations, the dataset is available via Google Drive. Please download the dataset from the following link:

- Download FER-2013 Dataset [https://drive.google.com/file/d/1yCxHw7aOAPYTVz9VKm2Yax1sxLLtJgWk/view?usp=sharing]

Once downloaded, unzip the file in the project directory.

## Dependencies
This project is implemented using Python 3.x and requires several Python libraries for functionality. Install the following dependencies:
1. Python 3.x
2. OpenCV for face detection
3. TensorFlow, TFlearn, Keras for deep learning model training
4. Matplotlib and NumPy for data visualization and manipulation

## Setup Instructions
1. Download the dataset using the link provided above.
2. Unzip the data.zip file in the project directory.
3. Place the FER-2013 dataset in the project folder.
4. Ensure all dependencies are installed by running the commands listed above.

## Running the System
1. Open your terminal and navigate to the project directory.
2. Run the model by executing the following command:
'''python kerasmodel.py --mode display'''
3. The webcam will open, and the model will detect your facial expression in real-time, displaying the detected emotion.

## Command Line Options:
- --mode display: This mode will show the emotion detected in real-time via the webcam.

## Key Components
- CNN Model: The model is built using Keras and TensorFlow. It classifies emotions by learning from the FER-2013 dataset.
- Face Detection: The system uses Haar Cascade for real-time face detection.
- Real-time Interface: The webcam feed is processed live, providing instant emotion detection.
