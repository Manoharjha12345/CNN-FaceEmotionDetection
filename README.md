#  Facial Emotion Detection using Convolutional Neural Network (CNN)

A Deep Learning web application that detects human facial emotions from uploaded facial images using a **Convolutional Neural Network (CNN)**. The application is built with **TensorFlow/Keras** and deployed using **Flask**.

---

##  Project Overview

Facial Emotion Detection is a Computer Vision application that classifies facial expressions into different emotions using a Convolutional Neural Network (CNN).

The user uploads an image through the Flask web interface. The uploaded image is preprocessed and passed to the trained CNN model, which predicts the facial emotion along with a confidence score.

---

##  Features

- Upload facial images through a web interface
- CNN-based emotion classification
- Predicts seven facial emotions
- Displays prediction confidence
- User-friendly Flask application
- Fast and accurate predictions

---

##  Emotion Classes

The CNN model predicts the following emotions:

-  Angry
-  Disgust
-  Fear
-  Happy
-  Neutral
-  Sad
-  Surprise

---

##  Technologies Used

- Python
- TensorFlow
- Keras
- Convolutional Neural Networks (CNN)
- Flask
- NumPy
- HTML
- CSS
- Jupyter Notebook

---

##  Project Structure

```
Facial-Emotion-Detection/
│── main.py
│── face.ipynb
│── facial_emotion_detection_model.h5
│── templates/
│    └── index.html
│── static/
│    └── uploads/
│── images/
│── requirements.txt
│── README.md
```

---

##  CNN Model Workflow

1. Upload a facial image.
2. Resize image to **48×48 pixels**.
3. Convert image to grayscale.
4. Normalize pixel values.
5. Feed the image into the trained CNN.
6. CNN extracts facial features using convolution layers.
7. Fully connected layers classify the emotion.
8. Display the predicted emotion and confidence score.

---

##  CNN Architecture

- Input Layer (48×48 Grayscale Image)
- Convolution Layer
- ReLU Activation
- Max Pooling Layer
- Convolution Layer
- ReLU Activation
- Max Pooling Layer
- Flatten Layer
- Dense Layer
- Dropout Layer
- Output Layer (Softmax)

---

##  Installation

```bash
git clone https://github.com/Manoharjha12345/Facial-Emotion-Detection.git
```

```bash
cd Facial-Emotion-Detection
```

```bash
pip install -r requirements.txt
```

---

##  Run the Application

```bash
python main.py
```





GitHub: https://github.com/Manoharjha12345
