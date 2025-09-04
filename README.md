# Carrot-Images-Classification
This repository contains an image classification project focused on carrot quality detection. The model is built using MobileNetV2 as a feature extractor combined with a Multiclass Support Vector Machine (SVM) classifier.

### Project Overview ###

- **Objective:** Classify carrot images into multiple categories (broken, bruise, crack, furcate, malformation, and normal).
- **Feature Extraction:** Pretrained MobileNetV2 is used to extract deep features from carrot images.
- **Classification:** Extracted features are fed into a Multiclass SVM (One-vs-One and One-vs-Rest) to perform final classification.
- **Dataset:** Carrot images collected and labeled into six classes.
- **Environment:** Developed and trained using Google Colab.
