**Project README**

# Smoking-Related Cancers Segmentation Using U-Net

This project aims to develop an automated system for segmenting smoking-related cancers in medical images using the U-Net architecture. The system leverages deep learning techniques to accurately identify and localize cancerous regions, providing valuable support to medical professionals in diagnosing and treating smoking-related cancers.

![Cancer Segmentation](https://github.com/Abdokarawia/Smoking-Related-Cancers-Segmentation-Using-Unet/blob/main/img.png)

## Introduction

Smoking-related cancers, such as lung, throat, and mouth cancers, are a significant global health concern. Early detection and accurate segmentation of cancerous regions in medical images are critical for effective treatment planning and monitoring. However, manual segmentation by radiologists can be time-consuming and subject to human error.

This project presents a deep learning-based approach to automate the segmentation of smoking-related cancers. By leveraging the U-Net architecture, we can effectively train a model to identify and delineate cancerous regions in medical images. The resulting segmentation maps can assist medical professionals in making informed decisions regarding patient care.

## Motivation

The motivation behind this project is to improve the efficiency and accuracy of smoking-related cancer detection and segmentation. By automating the segmentation process, we aim to reduce the burden on radiologists and provide a reliable tool for assisting in diagnosis and treatment planning.

Furthermore, early detection and accurate segmentation of smoking-related cancers can significantly impact patient outcomes. With this project, we hope to contribute to the advancement of medical imaging technology and improve healthcare outcomes for individuals affected by smoking-related cancers.

## U-Net

The U-Net architecture is a widely used convolutional neural network (CNN) model for image segmentation tasks. It consists of an encoder-decoder structure with skip connections, enabling the model to capture both local and global information effectively. The U-Net architecture has shown excellent performance in various medical image segmentation tasks, making it suitable for our smoking-related cancer segmentation project.

![U-NET](https://github.com/Abdokarawia/Smoking-Related-Cancers-Segmentation-Using-Unet/blob/main/Unet.png)


## ConvNext

ConvNext is a custom network component developed as part of this project. It combines convolutional and residual blocks to enhance feature extraction capabilities and improve the overall performance of the U-Net model. By integrating ConvNext into the U-Net architecture, we aim to achieve better segmentation results for smoking-related cancers.

![ConvNext](https://github.com/Abdokarawia/Smoking-Related-Cancers-Segmentation-Using-Unet/blob/main/ConvNext.png)


## Results

The trained model achieved promising results in segmenting smoking-related cancers in medical images. The model was evaluated using various metrics, including Dice coefficient, Jaccard index, and accuracy. The segmentation performance demonstrates the potential of the proposed approach in accurately identifying and localizing cancerous regions.

![Results](https://github.com/Abdokarawia/Smoking-Related-Cancers-Segmentation-Using-Unet/blob/main/images/segmentation_results.jpg)

## Flutter App

To provide an intuitive and user-friendly interface for utilizing the trained model, we have developed a Flutter-based mobile application. The app allows users to upload medical images, apply the segmentation model, and visualize the segmented regions. This mobile app enables easy access to the segmentation functionality, facilitating the integration of the proposed system into clinical workflows.

![Flutter](https://github.com/Abdokarawia/Smoking-Related-Cancers-Segmentation-Using-Unet/blob/main/Cancerapy.png)
![Cancerapy 2](https://github.com/Abdokarawia/Smoking-Related-Cancers-Segmentation-Using-Unet/blob/main/Cancerapy%202.png)




