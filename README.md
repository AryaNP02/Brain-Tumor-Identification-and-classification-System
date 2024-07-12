# Brain Tumor Identification and Classification System

## Overview
The "Brain Tumor Identification and Classification System" aims to provide an advanced solution for accurately identifying and classifying brain tumors using various deep learning models. This project leverages state-of-the-art neural network architectures to achieve high accuracy in tumor detection and classification from medical imaging data.

In addition to model development, I have also defined a user-friendly web application interface to facilitate easy access and utilization of the brain tumor identification and classification system.

## Models and Performance Metrics

| Model Name     | Train Accuracy (%) | Test Accuracy (%) | Train Loss | Test Loss |
|----------------|--------------------|-------------------|------------|-----------|
| Reference CNN  | 97.73              | 88.99             | 0.0505     | 0.4324    |
| DenseNet 121   | 99.66              | 96.02             | 0.0140     | 0.1415    |
| ResNet         | 95.97              | 93.01             | 0.1688     | 0.2309    |
| MobileNetV2    | 94.54              | 92.32             | 0.1972     | 0.2748    |
| EfficientNet   | 90.52              | 90.52             | 0.3054     | 0.3054    |

## Brain Classification Classes
The brain classification classes used in this system include:
- glioma_tumor
- meningioma_tumor
- no_tumor
- pituitary_tumor

## Dataset Used
The dataset used for training and testing this model is available on [Kaggle](https://www.kaggle.com/datasetname). This dataset is well-known in the field of medical imaging and provides comprehensive MRI scans for brain tumor identification and classification tasks.


## How to Use
1. **Clone the Repository**
    ```bash
    git clone https://github.com/AryaNP02/Brain-Tumor-Identification-and-classification-System.git
    cd Brain-Tumor-Identification-and-classification-System
    ```

2. **Install the Requirements**
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Web Application**
    - Launch the web application by running `python hello.py` and access it through a web browser.

4. **Select a Model**
    - Choose from the available models to perform brain tumor identification and classification.

5. **Input Data**
    - Upload MRI images or use provided test data to classify brain tumors into different classes.


