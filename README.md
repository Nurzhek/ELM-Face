# Face Verification with ResNet & ELM

This project implements a facial verification system using a hybrid approach combining a pretrained FaceNet-based model for feature extraction and an Extreme Learning Machine (ELM) for classification.

## 🔍 Overview

- **Dataset**: Labeled Faces in the Wild (LFW)
- **Model**: Feature extraction with InceptionResNet (FaceNet), classification with ELM
- **Face Detection**: Haar Cascade
- **Custom Image Support**: Upload and test your own face images
- **Live Prediction**: Real-time face classification using webcam

## 📦 Requirements

```bash
pip install scikit-learn opencv-python numpy matplotlib torchvision facenet-pytorch
```

## 🚀 Features

- Load and preprocess LFW dataset
- Extract embeddings using pretrained FaceNet (InceptionResNetV1)
- Train an ELM classifier on top of the embeddings
- Test on custom images or perform real-time classification via webcam

## 🛠️ Folder Structure

```
test/               # Folder for custom images
main.ipynb          # Jupyter notebook for end-to-end pipeline
```

## 📊 Results

The model achieved high accuracy on known LFW individuals and demonstrated effective recognition on custom and real-time data.

## 📸 Live Prediction

Make sure your webcam is enabled. The notebook supports real-time predictions using OpenCV.

---

## 📁 Sample Output

- Accuracy Score
- F1 Score
- Confusion Matrix
- Visualized Embeddings (PCA)

---

## 🙌 Acknowledgements

- [FaceNet](https://github.com/timesler/facenet-pytorch)
- [LFW Dataset](http://vis-www.cs.umass.edu/lfw/)

## 📬 Contact

Feel free to connect or ask questions on [LinkedIn](https://www.linkedin.com/in/Nurzhek).
