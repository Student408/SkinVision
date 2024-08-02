# SkinVision
SkinVision: Deep Learning for Skin Cancer Identification
This project aims to detect and classify skin cancer using transfer learning and convolutional neural networks (CNN). It leverages the MobileNetV2 model for feature extraction and classification.

## Overview

Skin cancer is one of the most common types of cancer globally, and early detection plays a crucial role in its treatment. This project utilizes deep learning techniques to automate the process of skin cancer detection and classification.

## Features

- Utilizes transfer learning with MobileNetV2 for feature extraction
- Implements CNN for classification of skin cancer types
- Performs data augmentation to enhance model generalization
- Generates confusion matrix and ROC AUC curves for model evaluation
- Provides an interface for predicting skin cancer types from input images

## Additional Tools Used

- [Google Drive Zip File Extraction](https://github.com/Student408/Google-Drive-Zip-File-Extraction)
- [Image Dataset Splitter](https://github.com/Student408/Image-Dataset-Splitter)
- [Image Labeling](https://github.com/Student408/Image-labeling)

## Dataset

The dataset used for training and testing the model can be obtained from the [ISIC Challenge](https://challenge.isic-archive.com/data).

## Pre-processed dataset
You can download the pre-processed datasets and test/train .npy files by clicking the link below:

<a href="https://drive.google.com/drive/folders/1iOGMT4Ni147eaojIak33XPBieCgCP6n0?usp=sharing" target="_blank">
  <img src="https://upload.wikimedia.org/wikipedia/commons/1/12/Google_Drive_icon_%282020%29.svg" alt="Google Drive" width="40" height="40"/>
</a>

## Pre-requisites

1. Download the dataset from [ISIC Challenge](https://challenge.isic-archive.com/data).
2. Data segregation [notebook](https://github.com/wisdomml2020/skin_cancer_classification_transfer_learning).
3. [Image Labeling](https://github.com/Student408/Image-labeling) save it in .npy
4. Download the pre-trained MobileNetV2 model weights.

## Usage

To use the skin cancer detection and classification model:
1. Clone the repository to your local machine.
2. Install the necessary dependencies by running `pip install -r requirements.txt`.
3. Run the provided Jupyter Notebook or Python script to train and evaluate the model.
4. Utilize the trained model for predicting skin cancer types from input images.

### Running the Jupyter Notebook or Python Script

Run the provided Jupyter Notebook or Python script to:
- Train the model on the dataset.
- Evaluate the trained model's performance.
- Make predictions on new skin lesion images.

## Additional Resources

- [Keras ImageDataGenerator and Data Augmentation](https://pyimagesearch.com/2019/07/08/keras-imagedatagenerator-and-data-augmentation/)
- [Keras Applications](https://keras.io/api/applications/)

## Results

The trained model achieves an accuracy of 88% on the test dataset. Confusion matrices and ROC AUC curves are provided to evaluate the model's performance.

## Google Colab Notebook

<a href="https://colab.research.google.com/github/Student408/SkinVision/blob/main/SkinVision%20Deep%20Learning%20for%20Skin%20Cancer%20Identification.ipynb" target="_blank">
  <img align="left" alt="Colab" title="Open in Colab" src="https://colab.research.google.com/assets/colab-badge.svg" />
</a> <br/>

## Contributing

Contributions to this project are welcome! If you have any suggestions, feature requests, or bug reports, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

