# IndiSign Language Recognition

An AI-powered Indian Sign Language alphabet recognition system using Convolutional Neural Networks (CNNs), TensorFlow, Keras and Streamlit.

## Project Overview

This project recognizes static Indian Sign Language alphabet gestures from uploaded images. It uses a trained CNN model to classify hand gestures into their corresponding alphabet classes.

The application provides an interactive interface where users can upload an image and receive a predicted alphabet with a confidence score.

## Problem Statement

Communication can be challenging between sign language users and people who are unfamiliar with sign language. This project explores how computer vision and deep learning can help recognize static hand-sign alphabets from images.

## Objectives

- Build an image-based sign language alphabet recognition system.
- Preprocess and analyze hand-sign images.
- Develop and train a CNN classification model.
- Evaluate the model using standard classification metrics.
- Deploy the trained model through a Streamlit application.

## Dataset

- Total images: 4,972
- Number of classes: 24
- Image size: 64 × 64 pixels
- Image format: RGB
- Classes: A–I and K–Y (J and Z are not included).

## Technologies Used

- Python
- NumPy and Pandas
- Matplotlib and Seaborn
- TensorFlow and Keras
- Scikit-learn
- Pillow
- Streamlit
- Jupyter Notebook

## Model Architecture

The project uses a Convolutional Neural Network (CNN) with:

- Convolutional layers
- ReLU activation
- Max pooling
- Batch normalization
- Dropout
- Dense layers
- Softmax output layer

Data augmentation and regularization were also explored to improve model generalization.

## Model Performance

The baseline and improved CNN models achieved approximately 99.50% accuracy on the prepared test dataset.

Evaluation included:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

Note: Test performance on this dataset does not guarantee the same accuracy on unseen real-world images.

## Streamlit Application

The application allows users to:

1. Upload a hand-sign image.
2. View the uploaded image.
3. Get the predicted alphabet.
4. View the prediction confidence score.

## Run Locally

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

Open the local URL displayed in your terminal.

## Project Limitations

- Supports 24 static alphabet classes only.
- Does not include J and Z.
- Does not recognize continuous gestures or complete sentences.
- Performance may vary with lighting, background and hand positioning.
- Requires additional real-world testing.

## Future Enhancements

- Add more sign language classes.
- Support dynamic gesture recognition.
- Implement real-time webcam recognition.
- Improve generalization with diverse datasets.
- Deploy the application to a cloud platform.

## Conclusion

This project demonstrates the practical application of deep learning and computer vision for static Indian Sign Language alphabet recognition. The trained CNN model is integrated into a Streamlit web application to provide interactive image-based predictions.

**Project Type:** AI / Machine Learning Capstone Project  
**Domain:** Computer Vision and Deep Learning
