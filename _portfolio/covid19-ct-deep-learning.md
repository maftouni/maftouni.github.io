---
layout: single
title: "Mask-Guided Attention Deep Learning Model for COVID-19 Diagnosis"
collection: portfolio
permalink: /portfolio/covid19-ct-deep-learning/
excerpt: "Deep learning model leveraging mask-guided attention on CT scans for COVID-19 classification, trained on an integrated multi-source medical imaging dataset."
date: 2021-06-01
tags:
  - deep-learning
  - medical-imaging
  - covid19
  - research
  - python

header:
  teaser: /images/covid_ct_project.png  # upload your own image here

image: /images/covid_ct_project.png
---

## Project overview

<p style="text-align: center;">
  <img src="/images/project2.png" 
       alt="COVID-19 CT Deep Learning Model"
       style="max-width: 70%; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.1);">
</p>

This research project focuses on developing a mask-guided attention deep learning model for
automated COVID-19 diagnosis using CT scan images. The model leverages lung masks to guide the
attention mechanism toward clinically relevant regions, allowing the classifier to focus on areas
most indicative of COVID-19 infection.

The project integrates CT scan datasets from multiple public sources, forming a unified and diverse
medical imaging dataset suitable for robust model training. This work was conducted as part of my Ph.D.
research at the SMART Laboratory under the guidance of Dr. James Kong.

## My role and tools

- **Role:** Model design, dataset integration, training pipeline development, evaluation, and manuscript preparation  
- **Tools:** Python, PyTorch, NumPy, OpenCV, Scikit-learn, Google Colab, CUDA  

## What the project shows

- How to build a deep learning classifier using CT scan images  
- How mask-guided attention improves diagnostic accuracy by highlighting clinically relevant regions  
- How to construct and clean a multi-source medical imaging dataset  
- How to evaluate model performance using accuracy, sensitivity, specificity, ROC curves, and Grad-CAM  
- How to structure a reproducible research pipeline in Python for medical imaging problems  
- How to prepare a research workflow that can be replicated and extended by other researchers  

## Links

- 📄 **Research Manuscript (Submitted):**  
  [A Mask-guided Attention Deep Learning Model for COVID-19 Diagnosis](https://www.researchgate.net/publication/352296409_A_Robust_Ensemble-Deep_Learning_Model_for_COVID-19_Diagnosis_based_on_an_Integrated_CT_Scan_Images_Database)

- 💻 **GitHub Repository:**  
  [Corona CT Classification – Source Code](https://github.com/maftouni/Corona_CT_Classification)
