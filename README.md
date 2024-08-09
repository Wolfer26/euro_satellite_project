# Satellite Image Classification using CNN

This project focuses on classifying satellite images into various land cover types using a Convolutional Neural Network (CNN). The dataset used is the EuroSAT RGB dataset, which contains satellite images from the Sentinel-2 satellite, categorized into ten distinct land cover classes.

## Project Overview

The objective of this project is to develop a machine learning model capable of identifying and classifying different types of land cover such as forests, highways, residential areas, etc., from satellite images. This is achieved through data preprocessing, model construction, training, evaluation, and result visualization.

## Repository Structure

notebooks: Contains the Jupyter notebook `Eurosat_project.ipynb` with all the code used in the project.
scripts: (Optional) Python scripts for running the code outside of Jupyter (if applicable).
data: A few sample images or references (Note: The full dataset should not be included due to size constraints).
images: Contains images for visualizations like training plots.
README.md: This file, providing an overview of the project.
requirements.txt: A list of Python dependencies required to run the project.
satellite_image_classifier.h5: The saved trained model (optional, depending on file size and GitHub storage limits).

### Prerequisites

Before running the project, ensure you have Python 3.11 installed.

## Dataset
The EuroSAT RGB dataset, used in this project, is available for download here 'https://zenodo.org/records/7711810#.ZAm3k-zMKEA'. The dataset consists of 27,000 images categorized into ten different land cover classes:


1. AnnualCrop
2. Forest
3. HerbaceousVegetation
4. Highway
5. Industrial
6. Pasture
7. PermanentCrop
8. Residential
9. River
10. SeaLake

## Model Architecture
The CNN model built for this project consists of the following layers:

Conv2D Layers: Three convolutional layers, each followed by ReLU activation and MaxPooling.
Flatten Layer: Converts the 2D matrix data into a vector to feed into the dense layers.
Dense Layers: Two dense layers with the final layer using a softmax activation function for classification.
Dropout Layer: A dropout layer is included to prevent overfitting.

## Training Results
The model was trained over 15 epochs with the following results:

Test Accuracy: 87.41%
Test Loss: 0.3795

## Conclusion

This project demonstrates the application of CNNs in satellite image classification. The model achieves high accuracy on the test set and shows good generalization capabilities. Future work could involve experimenting with deeper architectures, data augmentation, and transfer learning to further improve performance.

## License
This project is licensed under the MIT License.
