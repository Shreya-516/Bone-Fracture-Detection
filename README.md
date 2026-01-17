# Bone Fracture Detection using ResNet-18 with Nature-Inspired Pruning

## Overview
This project implements a robust and efficient **bone fracture detection system** using deep learning. The model is based on **ResNet-18** and enhanced using **nature-inspired pruning** optimized with **Cuckoo Search**, providing high accuracy and interpretable results.

The system can classify X-ray images of bones to detect fractures and highlight key areas in images using explainable AI techniques.

---

## Features
- **ResNet-18 based classification:** Backbone CNN architecture for feature extraction.
- **Nature-Inspired Pruning:** Reduces model complexity while maintaining high accuracy.
- **Cuckoo Search Optimization:** Optimizes pruning parameters for improved performance.
- **Explainable AI:** Grad-CAM++ and Integrated Gradients visualizations highlight important regions in X-ray images.
- **High Accuracy:** Optimized for reliable fracture detection in orthopedic imaging.

---

## Dataset
- X-ray images of bones (preprocessed for training and testing).
- Images are resized and normalized before feeding into the network.
- Train-test split: 80%-20%.
