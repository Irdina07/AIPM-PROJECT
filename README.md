# AI PROJECT MANAGEMENT-PROJECT 20%
# AI-Based Image Recognition System for Detecting Plant Leaf Diseases 🌿 🔍

This project utilizes Deep Learning to detect and classify diseases in plant leaves. It is designed to provide rapid diagnostics for common pathologies in Peppers, Potatoes, and Tomatoes using Convolutional Neural Networks (CNN).

## 📌 Project Overview
The system analyzes digital images of plant leaves to identify symptoms of infection that may be difficult for the human eye to distinguish early on. This tool aims to assist in precision agriculture and crop management.

## 📂 Project Structure
The repository is organized to separate the core logic from the training data:

```text
├── dataset/                        # Sample images of plant leaves
│   ├── Pepper__bell___Bacterial_spot/
│   ├── Pepper__bell___healthy/
│   ├── Potato___Early_blight/
│   ├── Potato___Late_blight/
│   ├── Potato___healthy/
│   ├── Tomato__Bacterial_spot/
│   ├── Tomato__Early_blight/
│   ├── Tomato__Late_blight/
│   └── Tomato__healthy/
├── app.py                          # Main application execution script
├── class_indices.json              # Mapping of disease labels to model indices
├── Plant Disease Detection.ipynb   # Jupyter Notebook containing training logic
└── plant_model.keras               # The trained Deep Learning model (HDF5 format)
