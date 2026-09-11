# concept-bottleneck-models-cub
**Concept-based Explainable Artificial Intelligence (C-XAI) for Image Classification under noisy annotations: A Study on Concept Bottleneck Models**

This repository contains the Google Colab notebook used to investigate Concept Bottleneck Models (CBMs) and its 3 training paradigms on the **CUB-200-2011** fine-grained bird classification dataset.

## Experiments:
The notebook includes:
- Independent, Sequential, and Joint CBM training pipelines,
- ResNet-50 as the concept-prediction backbone,
- MLP and Decision Tree as label heads for downstream label prediction,
- Class-wise concept denoising using K-Means clustering and majority-vote approach,
- Multiple denoising configurations: `k = {1, 2, 4, 6, 8, 10}` in addition to No Denoising(ND).
- Concept-level and label-level evaluation, including Accuracy, Macro Precision, Macro Recall, Macro F1-score,
- Experimental result visualisation,
- Test-time intervention experiments.

## Dataset:
Experiments are conducted on **CUB-200-2011**, containing 200 bird species with image-level semantic attribute annotations.
--- Number of concepts(Attribute / concept annotations): 312
--- Number of classes: 200
--- Total images: 11788

## Usage:
The notebook is designed to run in **Google Colab**.

## Author:
Shakiba Farjood
Master's Degree in Computer Science – Artificial Intelligence
University of Padova
