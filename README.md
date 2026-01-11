
---

# Surveillance and Monitoring System for Workplace Safety

## Overview

This project presents an **AI-based surveillance and monitoring system** designed to identify, classify, and report **workplace safety violations** using existing CCTV video feeds. The system leverages deep learning–based computer vision models to analyze video data and detect unsafe conditions and behaviors in real time.

The solution is implemented using a **modular, notebook-driven workflow**, where each safety category is handled independently and later combined into a unified pipeline.

---

## Key Safety Categories

* Personal Protective Equipment (PPE) Compliance
* Fire and Smoke Detection
* Pedestrian and Vehicle Safety
* Work at Height Monitoring
* Behavioural Safety and Unsafe Actions

---

## Project Structure

```
safety-surveillance/
├── notebooks/        # Training and inference notebooks
├── datasets/         # Processed datasets (YOLO format)
├── models/           # Trained model weights
├── videos/           # Input and demo videos
├── results/          # Output videos, images, and metrics
└── README.md
```

---

## Methodology

1. **Dataset Preparation**
   Multiple public datasets are collected, cleaned, and converted into YOLO format.

2. **Model Training**
   Each safety category is trained using a dedicated deep learning model (YOLO-based) within individual Jupyter notebooks.

3. **Inference and Evaluation**
   Trained models are evaluated on test videos to detect violations and generate annotated outputs.

4. **Final Integration**
   Multiple models are combined in a single pipeline to analyze video streams and report safety violations.

---

## Tools and Technologies

* Python
* Jupyter Notebook
* YOLO (Ultralytics)
* OpenCV
* PyTorch
* Google Colab / Kaggle (for GPU training)

---

## Results

The system successfully detects safety violations such as missing PPE, fire and smoke presence, unsafe pedestrian-vehicle interactions, and hazardous behaviors. Outputs include annotated videos, detection metrics, and visual evidence of violations.

---

## Use Cases

* Construction sites
* Industrial workplaces
* Manufacturing plants
* Warehouses and logistics hubs

---

## Conclusion

This project demonstrates the effectiveness of AI-driven video analytics in improving workplace safety by enabling continuous monitoring, early hazard detection, and data-driven safety compliance reporting.

---

