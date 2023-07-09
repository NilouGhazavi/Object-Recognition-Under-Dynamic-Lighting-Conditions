# Object Recognition Under Dynamic Lighting Conditions
 This repository contains the code and resources for a study focused on optimizing object recognition under dynamic lighting conditions. The goal of the project is to enhance the performance of convolutional neural network (CNN) models by accounting for variations in light intensity caused by shadows and sunlight.
## Summary
Object detection is a complex field within computer vision that has widespread applications. CNN models have proven effective in accurately identifying and classifying diverse image features. However, the performance of these models can be significantly impacted by dynamic lighting conditions. Real-world scenarios often involve varying light intensities due to shadows and sunlight, which can result in poor performance of CNN models.

The primary objective of this study is to optimize the ability of CNN models to detect and recognize objects accurately under a broad range of lighting conditions. To achieve this, a photoreceptor model layer was added as a front-end to a standard CNN model. This model imitates the behavior of retinal photoreceptors and dynamically adapts to fluctuations in light levels.

To evaluate the performance of the photoreceptor-inspired CNN model, a video stream was generated using a diverse range of images. Masks were created to simulate sudden changes in lighting conditions, such as those caused by shadows or variations in the intensity of the light source. These modified frames were incorporated into the video stream to introduce variations in lighting conditions.

The hypothesis is that the photoreceptor-inspired model can adjust for variations in light levels and achieve greater accuracy in object detection and recognition. The study used both the MNIST and CIFAR-10 datasets to evaluate the model's performance.
## Contents

This repository contains the following:

- `PRModel_MNIST.ipynb`: This notebook focuses on the evaluation of the photoreceptor model using the MNIST dataset. It contains code for training and evaluating the model on the MNIST dataset.

- `PRModel_CIFAR10.ipynb`: This notebook focuses on the evaluation of the photoreceptor model using the CIFAR-10 dataset. It contains code for training and evaluating the model on the CIFAR-10 dataset.

- Documentation and supplementary materials.

- Please refer to the notebooks and reports for a comprehensive understanding of the study, including the methodology, experimental setup, and analysis of the results.
