# Tree-Detection

# 🌳 Tree Detection Project – Data Preparation

This repository contains a Jupyter Notebook (`DataSplit_Tree.ipynb`) that prepares annotated tree image data for object detection training. The goal is to enable accurate detection of trees in aerial/drone imagery using deep learning models like YOLOv8.

---

## 📄 Notebook: `DataSplit_Tree.ipynb`

This notebook performs the following:

- Loads annotated image data (in YOLO format)
- Splits the dataset into **training** and **validation** sets
- Organizes folder structure for model training (e.g., `/images/train`, `/images/val`, etc.)
- Validates that files are correctly split and available for model use

---

## 🧠 Annotation Tool: CVAT

- All images were manually annotated using **[CVAT](https://cvat.org/)** (Computer Vision Annotation Tool)
- Annotations were exported in **YOLO format**
- Each bounding box represents a single tree instance in the aerial imagery

---



