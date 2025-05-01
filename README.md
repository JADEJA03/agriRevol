# Weed Detection in Groundnut Fields using YOLOv8

This repository contains training notebooks and datasets for detecting and classifying weeds in groundnut farms using YOLOv8 object detection models.

## 📁 Datasets
- `data_try_1/`: 300 manually labeled images (100 each for groundnut, long weed, and short weed)
- `data_try_2/`: 1200 labeled images, with long and short weed classes further broken into weed species

## 🧠 YOLOv8 Models
Trained models:
- YOLOv8n, YOLOv8s, YOLOv8m on both datasets
- Cross-dataset tests (e.g., `data_try_2` trained on `data_try_1`)

## 📒 Notebooks
- Located in the `notebooks/` directory
- Each notebook corresponds to a specific model and dataset

## 📊 Metrics
Evaluation metrics include:
- Precision
- Recall
- mAP50
- mAP50-95

## 🚀 How to Run
Install dependencies (see requirements in notebooks), then run the training notebooks via Jupyter or Colab.

---


