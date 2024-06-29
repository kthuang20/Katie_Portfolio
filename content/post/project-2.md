---
date: 2024-04-27
description: "A CNN that predicts whether if a compound if a good drug candidate for prevent antibiotic resistance based on its chemical structure."
featured_image: "/images/antibiotic_resistance.jpg"
tags: ["antibiotic resistance", "cheminformatics", "drug discovery", "machine learning"]
title: "Accelerating Targeted Drug Discovery Against Antibiotic Resistance with CNNs"
---

In this project, I tackled the pressing issue of antibiotic resistance by leveraging Convolutional Neural Networks (CNNs) to predict the efficacy of potential drug candidates in inhibiting β-lactamase, a key enzyme involved in antibiotic resistance. Using the ChEMBL dataset, I sourced canonical smiles of compounds known to interact with β-lactamase, which were then transformed into 2D images using RDKit for CNN input. By assigning labels based on pChEMBL values, compounds were categorized as either active (effective at inhibiting β-lactamase) or inactive. The dataset was meticulously split into training, validation, and testing sets to optimize CNN hyperparameters and evaluate model performance. Impressively, the CNN consistently achieved over 90% accuracy, precision, and recall across all datasets, suggesting that using compound chemical structures is a promising approach for predicting antibiotic resistance prevention. This work not only demonstrates the potential of CNNs in accelerating the discovery of β-lactamase inhibitors but also holds promise in combating antibiotic resistance on a broader scale. Dive into the code notebook to explore the CNN architecture and delve deeper into the methodology behind this impactful research.

Links to Jupyter notebook and source code:
* [Google Colab](https://colab.research.google.com/gist/kthuang20/64c59b559422625b438bd10f45051a09/beta-lactamase-cnn.ipynb)
* [GitHub Repository](https://github.com/kthuang20/BetaLactamaseCNN/blob/main/Beta_Lactamase_CNN.ipynb)