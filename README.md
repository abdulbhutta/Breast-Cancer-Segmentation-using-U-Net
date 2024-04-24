# Breast Cancer Segmentation using U-Net
### Abdul Bhutta
### EE8204 - Neural Networks

This is a final project for EE8204 - Neural Networks

This project implements a U-Net model to detect and segment the tumour in the breast. 

Dataset: https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset

![alt text](https://github.com/abdulbhutta/Breast-Cancer-Segmentation-using-U-Net/blob/main/Image/output.png)

## Getting Started

Please look below on how to run the code or model!

### Prerequisites

Download or Clone this repo. Change Path Names to the where the models and dataset are downloaded,
Update
  ```sh
    dataset_path = 'Dataset_BUSI_with_GT-3/*/*.png'
  ```
  To
  ```sh
    dataset_path = <Your path location the dataset>
```

### Train/Run the Model

Below is an example of how you Train or Test your own model. You must change the path and import the libraries!

To Train: Go to the Train Section in the Notebook
NOT RECOMMENDED (MODELS HAVE ALREADY BEEN TRAINED)
DO NOT OVERWRITE THE MODEL WEIGHTS!

### To train the model, go to one of the "model" training section in the notebook
```sh
Run line 1 to 7
```

```sh
Run the specific section for the model training (Make sure the dataset path is updated)
```
### To Test or run inference: Go to the Testing Model on Test Data Section
To run the model, go to one of the "model" testing section of the notebook


* Update this
```sh
model.load_weights('/content/drive/MyDrive/model1_unet_binaryloss_128.h5')
```
to
```sh
model.load_weights(<Your path for the specific download model>)
```
```sh
Run the specific cell for the specific output you require, but make sure you run the and compile
the model at the start of each test section
```

