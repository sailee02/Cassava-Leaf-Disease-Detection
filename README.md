# Cassava Leaf Disease Detection

## Overview

This project implements a novel deep learning approach for detecting diseases in cassava leaves. Using a modified convolutional neural network (CNN) architecture, we achieve high accuracy in classifying various cassava leaf diseases, aiding farmers and researchers in early detection and management.

## Key Features

- Custom CNN architecture with parallel pathways
- Utilizes 1x1 and 3x3 convolutions, max pooling, and global average pooling
- Achieves 98.54% training accuracy, 97.84% validation accuracy, and 98.08% testing accuracy
- Outperforms several pre-trained models in disease classification

## Dataset

The dataset comprises 11,414 images from a Kaggle competition, divided into:

- Training set
- Validation set
- Test set

Images are standardized to 800x600 pixels in JPG format, covering five classes:

1. Cassava Mosaic Disease
2. Cassava Brown Streak Disease
3. Cassava Green Mottle
4. Cassava Bacterial Blight
5. Healthy Cassava Plants

## Model Architecture

Our novel CNN architecture includes:

- Parallel pathways for multi-scale feature learning
- Combination of 1x1 and 3x3 convolutions
- Max pooling layers
- Global average pooling

This design allows for effective capture of both local and global information in leaf images.

## Performance

Our model outperforms several pre-trained networks:

- Training accuracy: 98.54%
- Validation accuracy: 97.84%
- Testing accuracy: 98.08%

## Citation

If you use this work in your research, please cite our paper:
A. Pai, A. Raotole, S. Shirodkar, S. Bose and M. H. Kolekar, "From Pixels to Prognosis: Exploring Convolutional Neural Networks for Cassava Leaf Disease Diagnosis," 2023 OITS International Conference on Information Technology (OCIT), Raipur, India, 2023, pp. 168-173, doi: 10.1109/OCIT59427.2023.10430882. keywords: {Training;Crops;Medical diagnosis;Convolutional neural networks;Prognostics and health management;Diseases;Testing;Cassava leaf disease;Deep learning;Convolutional neural network;Crop management},

---
