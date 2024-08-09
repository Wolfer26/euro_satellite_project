# Satellite Image Classification using CNN

This project focuses on classifying satellite images into various land cover types using a Convolutional Neural Network (CNN). The dataset used is the EuroSAT RGB dataset, which contains satellite images from the Sentinel-2 satellite, categorized into ten distinct land cover classes.

## Project Overview

The objective of this project is to develop a machine learning model capable of identifying and classifying different types of land cover such as forests, highways, residential areas, etc., from satellite images. This is achieved through data preprocessing, model construction, training, evaluation, and result visualization.

## Repository Structure

notebooks: Contains the Jupyter notebook `satellite_image_classification.ipynb` with all the code used in the project.
scripts: (Optional) Python scripts for running the code outside of Jupyter (if applicable).
data: A few sample images or references (Note: The full dataset should not be included due to size constraints).
images: Contains images for visualizations like training plots.
README.md: This file, providing an overview of the project.
requirements.txt: A list of Python dependencies required to run the project.
satellite_image_classifier.h5: The saved trained model (optional, depending on file size and GitHub storage limits).

### Prerequisites

Before running the project, ensure you have Python 3.11 installed.

## Results
The model achieved an accuracy of 87.41% on the test set.
