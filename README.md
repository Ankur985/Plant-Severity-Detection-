# Plant Severity Detection

In this Project, I Am Working on Crop Image Segmentation for disease severity Detection. Given the pictures of infected leaves, detect the severity of the disease in them by segmenting the diseased leaves.
parts from the image and analysing them.

---

## Overview
- Detecting and managing plant diseases is crucial for sustainable agriculture, as it helps prevent crop damage, reduces unnecessary pesticide use, and supports food security. While traditional methods are labour-intensive and subjective, automated systems using deep learning and computer vision offer promising alternatives. However, these technologies face challenges like handling noisy image backgrounds and selecting the right features for accurate disease assessment.
  
---

## Problem Statement
- Given the pictures of infected leaves, detect the severity of the disease in them by segmenting the diseased leaves.
parts from the image and analysing them.

---

## Methodology Adopted
- Imposing the dataset of infected leaves from Kaggle.
- Segmenting the diseased part only from the whole image
- Converting the RGB image to HSL
- Extracting the 'S' channel and converting it into its binary image equivalent
- Separating the individual components of the disease and finding their respective averages using component labelling

---

## Existing Concepts and Algorithms Used
The model is built using a stack of LSTMs with dropout layers to prevent overfitting. The architecture is as follows:
- **Color Vegetation Indices**: Detecting vegetation by distinguishing weeds from crops, and color vegetation indices (CVIs)  
- **Component Labelling**: A technique used to identify and label distinct, connected regions or components within a binary image or a segmented image.
- **Breadth First Search on a grid of pixels**: Breadth-First Search (BFS) is a fundamental algorithm used in image processing to explore and analyse grids or matrices of pixels.

---

## Dataset
- The dataset of images has been taken from Kaggle, where the images of the leaves have been captured on a white background.


