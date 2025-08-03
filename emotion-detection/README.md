# Emotion Detection (CNN + Haar Cascade)

This project detects human emotions from images using:
- **FER2013 dataset** for training a CNN model.
- **Haar Cascade** for face detection on new images.
- **Keras + TensorFlow** for model training.
- **OpenCV** for image preprocessing and face detection.

## Features
- Train a CNN on grayscale 48x48 face images.
- Detect faces in new images and predict emotions:
  - Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral.

## How to Use
1. Clone this repository.
2. Make sure `haarcascade_frontalface_default.xml` is in the project folder.
3. Open the Jupyter notebook:
4. Run all cells. Replace the `img = cv2.imread('smiling-face.jpg')` line with your own image.

## Requirements
- Python 3.x
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib

## Dataset
The dataset used in this project is **FER2013**.  
You can download it from Kaggle:

[Kaggle FER2013 Dataset](https://www.kaggle.com/datasets/msambare/fer2013)

After downloading:
1. Extract the file.
2. Copy `fer2013.csv` into the `data` folder of this project:


