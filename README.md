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

📊 Dataset Details

The dataset resides in the dataset/ folder and includes:

Image/ — Satellite images (pre- and post-disaster)

Mask/ — Annotated flood regions in binary/multiclass format

metadata.csv — Additional information to support analysis

---

🔧 Scripts Breakdown
utils.py: Contains preprocessing, overlay, and visualization helpers

detect_chages.py: Implements comparison of before/after images for damage assessment

instace_segmentation.py: Runs instance-level segmentation on affected areas

---

## 🛠️ Setup Instructions

Ensure you have **Python 3.10+** installed. 

### 1️⃣ Install Dependencies

Make sure all required libraries are installed:

```bash
pip install -r requirements.txt




