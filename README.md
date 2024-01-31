# Secure CAPTCHA Image Classifier 🤖🔍

## Overview
This project implements a Convolutional Neural Network (CNN) to classify CAPTCHA images. The code preprocesses images, applies Otsu's thresholding, and uses morphological transformations for character separation. The CNN model includes convolutional, batch normalization, dropout, and fully connected layers. Training, validation, and testing are performed on labeled datasets. Predictions are saved in a CSV file.

## Technologies Used
- Python 🐍
- TensorFlow, Keras 🧠
- NumPy, pandas 📊
- OpenCV, PIL 🖼️

## Usage
1. Install dependencies: `pip install -r requirements.txt`
2. Run the main script: `python image_classifier.py`

## Model Architecture
- Convolutional layers 🎛️
- Batch normalization 📊
- Dropout layers 🚀
- Fully connected layers 🔗

## Training
- 30 epochs 🕒
- Adam optimizer 🔄
- Sparse categorical crossentropy loss 📉
- Accuracy metrics 📈

## Prediction
- Test set predictions 🔮
- Save results in `submission12.csv` 📄

## Directory Structure
```
- /kaggle/input/fiu-cap5610-spring-2023
  - images/
    - (CAPTCHA images)
  - train.csv
  - test.csv
- image_classifier.py
- submission12.csv
- README.md
```

Feel free to explore and contribute! 🚀
