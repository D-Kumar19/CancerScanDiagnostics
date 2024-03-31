# Cancer Scan Diagnostics: Renal Cell Carcinoma Detection 🎗️

## Overview

This repository contains the culmination of research and development efforts aimed at improving the early detection and diagnosis of Renal Cell Carcinoma (RCC) through advanced machine learning techniques applied to MRI and CT scan images. Utilizing a dataset of over 5,000 images, this project demonstrates the potential of image processing in medical diagnostics, achieving up to 97% accuracy in identifying cancerous anomalies.

### Abstract

Renal Cell Carcinoma (RCC), or Kidney Cancer, ranks among the top ten most prevalent cancers worldwide, leading to significant morbidity and mortality each year. Early detection is critical, as the 5-year survival rate drastically falls from 93% in localized stages to 15% when metastasized. This thesis explores the application of machine learning models, including Convolutional Neural Networks (CNNs), Support Vector Machines (SVMs), and Transformers, to enhance the accuracy and efficiency of RCC detection in medical imaging.

## Key Contributions

- **Dataset Preparation**: Selected and preprocessed a high-quality dataset of kidney MRI and CT scan images using OpenCV for noise reduction, edge detection, and data augmentation.
- **Model Development**: Trained and evaluated multiple machine learning models, with the Support Vector Machine (SVM) model demonstrating exceptional accuracy (97%) and efficiency.
- **Innovative Techniques**: Employed cutting-edge methods, including Transformers and CNNs, to compare model performances comprehensively.
- **Practical Application**: Developed a user-friendly web interface for real-time cancer scan diagnostics, enabling rapid and accurate RCC detection.

## Model Performance

The following chart showcases the comparative accuracy and efficiency of the evaluated models:

| Model         | Accuracy | Precision | Recall | F1 Score | Computational Requirement |
|---------------|----------|-----------|--------|----------|---------------------------|
| ANN           | 63.54%   | 63.53%    | 66.90% | -        | Moderate                  |
| **SVM**       | **96.79%**   | **97.00%**    | **97.00%** | **97.00%**  | Low                      |
| CNN (VGG16)   | 93.17%   | 96.36%    | 90.00% | -        | High                      |
| Transformers  | 96.58%   | 93.72%    | 100.00%| 96.76%   | Very High                 |

SVM emerged as the most efficient and accurate model, offering a promising solution for RCC detection.

## Web Interface for Scan Analysis

A PHP-based web application was developed to demonstrate the SVM model's practical utility. Users can upload scans to receive immediate diagnostics indicating the presence of RCC, alongside health advice or physician recommendations.

## Reflections and Future Work

This thesis contributes significantly to the field of medical diagnostics, particularly in the early detection of RCC. Future research avenues include exploring multi-class classification problems, expanding the dataset scope, and integrating the developed models into healthcare systems for real-world validation.

## Contributions

I welcome contributions to this project! If you have suggestions, improvements, or want to contribute in any way, please refer to me directly for further discussion and guidelines on how you can become a part of this evolving project.

## How to Use

Please refer to the attached file for detailed instructions on dataset preparation, model training, and web interface deployment.
