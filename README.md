# Predictive Tool for Breast Cancer Diagnosis

## Web app link

https://predictive-tool-for-breast-cancer-diagnosis.streamlit.app/

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

## Project Summary

**Description:**
- Developed a Breast Cancer Predictor application using machine learning and Streamlit.
- Utilized a public dataset for Breast Cancer Wisconsin (Diagnostic) Data Set for educational purposes.
- Cleaned and processed data, transforming it into a format suitable for analysis.
- Implemented a streamlined user interface with Streamlit, allowing for manual input of measurements or connection to a cytology lab for automated data retrieval.
- Created a radar chart visualization to represent cell nuclei measurements in terms of mean, standard error, and worst values.
- Integrated a machine learning model for predicting cell cluster types (benign or malicious) based on user-input measurements.
- Incorporated styling with CSS to enhance the visual appeal of the application.
- Ensured responsive design for user-friendly experience on different devices.

**Technologies Used:**
- Streamlit for developing the user interface.
- Python for coding the backend logic.
- Plotly for generating radar charts.
- Pandas for data manipulation.
- Pickle for model and scaler serialization.

**Impact:**
- Facilitated medical professionals in diagnosing breast cancer by providing predictive analysis based on cell nuclei measurements.
- Encouraged user interaction through an intuitive and visually appealing interface.
