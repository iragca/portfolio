---
tags:
  - Plant Pathology
  - Deep Learning
  - Convolutional Neural Networks
  - Image Classification
  - Python
  - Coursework
---

<div style="display: flex;">

<img align="left" height="120" width="120" src="https://pub-2605a5350a664b7cad96b61a19778380.r2.dev/megaplant/logo.png" />

<div>
A consolidated leaf-image dataset designed to support plant disease classification models that generalize across diverse environmental conditions, from controlled laboratory settings to highly variable in-field scenarios. MegaPlant integrates multiple publicly available datasets and standardizes them into a unified taxonomy of healthy and diseased leaf categories, enabling robust training across modalities.
</div>
</div>

[Website :material-web:](https://iragca.github.io/DS413-final-project/){ .md-button }
[GitHub :simple-github:](https://github.com/iragca/DS413-final-project/){ .md-button }

=== "Paper"

    <embed src="https://pub-2605a5350a664b7cad96b61a19778380.r2.dev/megaplant/megaplant.pdf"
    type="application/pdf"
    width="100%"
    height="800px"
    />

=== "Website"

    <img src="https://pub-2605a5350a664b7cad96b61a19778380.r2.dev/megaplant/website.png">

=== "Jupyter Notebook"

    <img src="https://pub-2605a5350a664b7cad96b61a19778380.r2.dev/megaplant/jp-nb.png">

## Methodology

- Aggregated datasets from [Kaggle](https://www.kaggle.com/datasets) and official repositories, totaling nearly 60,000 plant images
- Used [PyTorch](https://pytorch.org/) in building a convolutional network
- Focuses only on disease detection and symptom identification

## Metrics

- Average increase of 8% in classification accuracy relative to foundational datasets
- 95.12% accuracy in classifying plant disease
