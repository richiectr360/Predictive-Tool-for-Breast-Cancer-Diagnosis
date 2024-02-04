# Predictive Tool for Breast Cancer Diagnosis

## Overview

The Breast Cancer Diagnosis application is an AI-driven tool developed to aid medical professionals in identifying breast cancer. Leveraging a set of measurements, the application predicts whether a breast mass is benign or malignant. It visually presents the input data through a radar chart and showcases the predicted diagnosis along with the associated probability of being benign or malignant. The application allows manual input of measurements or can be connected to a cytology lab to directly retrieve data from a machine. It's important to note that the app itself does not include the functionality to connect to the laboratory machine.

This app originated as a machine learning exercise using the publicly available dataset [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data). It's crucial to understand that this dataset may not be reliable, as the project was specifically designed for educational purposes in the realm of machine learning, not for professional use.


## Installation

To run the Cell Image Analyzer locally, ensure you have Python 3.6 or a higher version installed. Subsequently, install the required packages by executing the following command:

```bash
pip install -r requirements.txt
```

This command installs all the necessary dependencies, including Streamlit, OpenCV, and scikit-image.

## Usage
To initiate the app, run the following command:

```bash
streamlit run app.py
```

This action opens the app in your default web browser. From there, you can upload an image of cells for analysis and customize the analysis settings. Once you are content with the results, export the measurements to a CSV file for further analysis.
