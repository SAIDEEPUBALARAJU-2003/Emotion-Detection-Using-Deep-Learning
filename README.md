# Emotion Detection Using Deep Learning

## Overview

Emotion Detection Using Deep Learning is a real-time facial emotion recognition system that detects human emotions from images, videos, or a live webcam feed. The application uses deep learning and computer vision techniques to classify facial expressions into different emotional states such as Happy, Sad, Angry, Fear, Surprise, Neutral, and Disgust.

This project demonstrates the practical application of Convolutional Neural Networks (CNNs) for facial expression recognition and provides a simple web interface for users to upload images or use a webcam for real-time emotion detection.

---

## Features

- Real-time emotion detection using webcam
- Image upload for emotion prediction
- Video upload for emotion recognition
- Deep Learning-based emotion classification
- User-friendly web interface
- Fast and accurate facial emotion detection

---

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Flask
- HTML
- CSS
- JavaScript

---

## Project Structure

```
Emotion-Detection-Using-Deep-Learning/
│
├── emotion_app/
│   ├── static/
│   ├── templates/
│   ├── app.py
│   ├── detect.py
│   ├── model/
│   └── utils/
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Dataset

The model is trained using a facial expression dataset containing images of different emotions.

### Emotion Classes

- Angry
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Surprise

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/SAIDEEPUBALARAJU-2003/Emotion-Detection-Using-Deep-Learning.git
```

### Navigate to the Project Folder

```bash
cd Emotion-Detection-Using-Deep-Learning
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## How to Run

Run the application:

```bash
python app.py
```

or if your main file is inside a folder:

```bash
python emotion_app/app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## Working

1. Capture an image using a webcam or upload an image/video.
2. Detect the face using OpenCV.
3. Preprocess the detected face.
4. Pass the image to the trained CNN model.
5. Predict the facial emotion.
6. Display the predicted emotion on the screen.

---

## Applications

- Human-Computer Interaction
- Smart Surveillance
- Healthcare Monitoring
- Online Education
- Customer Sentiment Analysis
- Mental Health Support
- Entertainment Systems

---

## Future Enhancements

- Higher accuracy using advanced CNN architectures
- Support for multiple face detection
- Mobile application integration
- Cloud deployment
- Emotion analytics dashboard
- Real-time attendance with emotion tracking

---

## Results

The system successfully detects facial emotions in real time and classifies them into one of the predefined emotion categories. The application demonstrates the effectiveness of deep learning techniques for facial expression recognition.

---

## Author

**Saideepu Balaraju**
