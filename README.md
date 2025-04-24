# TCV-Project
# 🥑 Avocado Ripeness Classification using Machine Learning

This project presents a machine learning-based solution for classifying avocado ripeness stages using image processing. It aims to provide a non-destructive, scalable, and efficient alternative to traditional ripeness assessment methods in the agricultural supply chain.

## 📌 Overview

Accurate ripeness detection is essential for minimizing food waste, optimizing supply chain decisions, and improving consumer satisfaction. Traditional methods like visual inspection and firmness tests are subjective and inefficient. This project combines **image preprocessing techniques** with **machine learning algorithms** to build an **automated avocado ripeness classifier**.

## 📷 Dataset

### 1. Self-Collected Dataset
- 📍 Location: Ayer Keroh, Malacca, Malaysia
- 📱 Captured using: Redmi Note 13 Pro 5G
- 📅 Dates: Dec 10–20, 2024
- 📸 Categories: Unripe, Breaking, Ripe
- 📐 Image size: Cropped to 512×512 pixels

### 2. Public Dataset
- 🗃️ Source: [Mendeley Data – Hass Avocado Ripening Dataset](https://data.mendeley.com/datasets/3xd9n945v8/1)
- 📦 Total Images: 14,710
- 🏷️ Stages: Underripe (1) to Overripe (5)
- ⚙️ Split: 70% training, 30% testing

## 🛠️ Preprocessing Techniques
- Background removal (GrabCut + thresholding)
- Image enhancement (contrast, brightness)
- Image sharpening (custom kernel)
- Color feature extraction (histograms)
- Texture feature extraction (grayscale patterns)

## 🧠 Machine Learning Models
Three models were trained and tested:
- **Random Forest (RF)**
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**

All models were evaluated with and without preprocessing.
