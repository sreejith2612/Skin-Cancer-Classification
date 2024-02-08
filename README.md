# Skin Cancer Detection System

## Abstract

Skin cancer is a significant health concern worldwide, with early detection being crucial for effective treatment. This repository presents a comprehensive system for skin cancer detection utilizing Convolutional Neural Networks (CNNs). The system comprises several modules, each contributing to different stages of the detection process.

## Modules

1. **Image Preprocessing Module**: Prepares raw skin images for CNN-based skin cancer detection by standardizing their size, normalizing pixel values, removing noise, and augmenting data to improve variability and enhance the model's ability to learn distinct features.

2. **Data Cleaning Module**: Ensures dataset quality by validating, correcting, and balancing the skin image dataset. It detects and rectifies missing or incorrect data, addresses outliers, verifies labels, and balances class distributions to optimize model training.

3. **Training CNN Module**: Constructs and trains a Convolutional Neural Network by designing its architecture, conducting model training with preprocessed data, tuning hyperparameters, and evaluating performance metrics to ensure optimal learning from the skin image dataset.

4. **Testing CNN Module**: Evaluates the trained CNN model's performance by applying it to unseen data, generating predictions, computing performance metrics, and providing visual insights such as confusion matrices or ROC curves to assess the model's accuracy and generalization.

5. **Detection Module**: Integrates the trained CNN model into an application or system, enabling real-time skin cancer detection from live camera feeds or uploaded images. It allows user feedback to continuously improve the model's performance and usability in a real-world setting.

![Alt text](https://github.com/sreejith2612/Skin-Cancer-Classification/blob/main/Web/img/image_2024-02-09_000611509.png)
![Alt text](https://github.com/sreejith2612/Skin-Cancer-Classification/blob/main/Web/img/image_2024-02-09_000953874.png)
