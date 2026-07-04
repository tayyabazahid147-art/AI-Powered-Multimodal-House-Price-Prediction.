# AI-Powered-Multimodal-House-Price-Prediction.
An AI-powered house price prediction system built using machine learning and Gradio.


A multimodal deep learning system that predicts house prices by combining **house images** and **property information**. The model integrates computer vision with structured data to produce accurate real estate price predictions through an interactive Gradio web application.

---

## Project Overview

Traditional house price prediction models rely only on numerical features. This project improves prediction by combining:

- 🖼 House exterior images
- 📍 City location
- 🛏 Bedrooms
- 🛁 Bathrooms
- 📐 Square footage
- 🏠 Other property attributes

using a multimodal deep learning architecture.

---

## Features

- Multimodal Deep Learning
- Image + Tabular Data Fusion
- EfficientNetB0 Feature Extraction
- Multi-Layer Perceptron (MLP)
- Interactive Gradio Interface
- Real-time House Price Prediction

---

## Technologies Used

- Python
- TensorFlow
- Keras
- EfficientNetB0
- NumPy
- Pandas
- Scikit-learn
- Gradio
- Google Colab

---

## Model Architecture

Image Input
↓
EfficientNetB0

Tabular Input
↓
MLP Network

Feature Fusion
↓
Dense Layers
↓
Predicted House Price

---

## Dataset

Southern California Housing (SoCal2)

Inputs:
- House Image
- City
- Bedrooms
- Bathrooms
- Square Footage

Output:
- Predicted House Price

---

## Gradio Interface

The model is deployed using **Gradio**, allowing users to upload a house image, enter property details, and receive an instant house price prediction.

---

## Results

- Successfully combined image and structured data.
- Learned multimodal representations using deep learning.
- Built an interactive AI application using Gradio.

---

## Future Improvements

- Improve prediction accuracy
- Deploy on Hugging Face Spaces
- Experiment with Vision Transformers (ViT)
- Add more property features
- Train on larger datasets

---

## Repository Structure

```
AI-Powered-Multimodal-House-Price-Prediction
│
├── AI_project_colab_file.ipynb
├── README.md
├── requirements.txt
├── images/
│     ├── interface.png
│     ├── prediction.png
│     └── architecture.png
```

---

## Author

**Tayyaba Zahid**

BS Robotics & Intelligent Systems

Bahria University
