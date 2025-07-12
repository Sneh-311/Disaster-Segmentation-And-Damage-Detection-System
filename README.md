# 🌊 Disaster Segmentation and Damage Detection System

A deep learning-powered solution for detecting and analyzing flooded regions from satellite imagery. This project leverages a UNet architecture for semantic segmentation, integrates instance-level analysis, and visualizes results through an interactive Flask web application.

---

## 🗂️ Project Overview

This system helps in:
- Identifying flood-affected areas from satellite images using UNet
- Detecting changes over time to analyze flood impact
- Performing instance segmentation to isolate multiple affected regions
- Visualizing all outputs through a clean Flask-based web interface

---

## 🏗️ Directory Structure

project/
├── app.py # Flask server entry point
├── detect_chages.py # Change detection logic
├── floods_project.ipynb # Experimentation notebook
├── instace_segmentation.py # Instance segmentation logic
├── segmentation_model.pth # Pre-trained UNet model weights
├── unet.py # UNet model definition
├── utils.py # Helper utilities
├── dataset/
│ ├── Image/ # Raw satellite images
│ ├── Mask/ # Corresponding segmentation masks
│ └── metadata.csv # Metadata for analysis
├── static/ # Static assets for Flask
└── templates/ # HTML templates

---

## 🚀 Key Features

✅ Flood segmentation with UNet  
✅ Instance-level segmentation  
✅ Temporal change detection  
✅ Web-based result visualization  
✅ Well-structured dataset of satellite images and masks  

---

## 🧠 Model Architecture

The backbone of this project is a **UNet** architecture defined in `unet.py`. It has been trained on annotated satellite data to segment flooded areas. The trained weights are stored in `segmentation_model.pth`.

---

## 🛠️ Setup Instructions

### 🔧 Prerequisites

Ensure you have **Python 3.10+** installed. Then install the following packages:




