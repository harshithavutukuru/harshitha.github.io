---
title: "CerebroVision"
excerpt: "Brain Tumor Identification <br/><img src='/images/brain_tumor_1.jpg'>"
collection: portfolio
---

The project titled CerebroVision: Advanced CNN Diagnostics for Brain Tumor Identification focuses on enhancing the accuracy of brain tumor detection using deep learning techniques, specifically Convolutional Neural Networks (CNNs). The primary goal is to develop a model that can classify MRI images as either healthy or tumor-affected, potentially improving early detection and treatment outcomes.

Key Highlights:
Project Objective: Use CNNs to achieve high diagnostic accuracy in detecting brain tumors, minimizing false positives and negatives, and supporting early-stage detection.
Data: The project uses the Brain Tumor Dataset from Kaggle, consisting of 4,602 MRI images divided into brain tumor and healthy categories.
Development Tools: The models are built using Python, TensorFlow, Keras, Scikit-learn, and visualized using Matplotlib, Seaborn, and Weights & Biases (wandb).
Models: The project evaluates multiple models including pretrained networks (ResNet50 and VGG19) and custom CNN architectures like HALNet, SMVNet, and JAPNet. Custom models HALNet-1 and HALNet-2 achieved the highest accuracy rates (99.08% and 99.88%) and were particularly effective in reducing overfitting and improving classification.
Evaluation Metrics: Metrics such as accuracy, AUC (Area Under the Curve), precision, recall, and confusion matrices were used to assess performance. Custom models outperformed standard pretrained models.
Conclusion: The project successfully demonstrated that custom CNNs, tailored for medical imaging tasks, can achieve superior performance over traditional pretrained models, offering promising results for real-world medical diagnostic applications.
This project showcases the power of deep learning in medical diagnostics, highlighting the potential of custom architectures in detecting brain tumors more accurately than standard models. 
