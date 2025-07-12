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

The core of this project is a **UNet** model defined in `unet.py`, trained on labeled satellite imagery to identify flood zones. The trained weights are stored in `segmentation_model.pth`.

---

## 📊 Dataset Details

The dataset is stored in the `dataset/` directory and includes:
- `Image/` — Satellite images (pre- and post-disaster)
- `Mask/` — Corresponding segmentation masks (binary or multiclass)
- `metadata.csv` — Supplementary metadata for analysis

---

## 🔧 Scripts Breakdown

- `utils.py` — Preprocessing utilities, visualization, and mask/image handling
- `detect_chages.py` — Compares pre- and post-event images to analyze damage
- `instace_segmentation.py` — Performs instance-level segmentation of flooded regions

---

## 🛠️ Setup Instructions

Make sure you have **Python 3.10+** installed.

### 1️⃣ Install Dependencies

Install all required libraries using:

```bash
pip install -r requirements.txt

python app.py
