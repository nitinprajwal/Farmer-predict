# Farmer Predict

Farmer Predict is a machine learning project aimed at predicting suitable crops and their yields based on soil and environmental conditions. The project leverages a dataset containing information about Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH Value, and Rainfall to suggest the best crops to plant.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Data](#data)
- [Usage](#usage)
- [Installation](#installation)
- [Model Training](#model-training)
- [Prediction](#prediction)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project provides a tool for farmers to predict the most suitable crops and their expected yields based on specific soil and environmental conditions. The model is trained using a Linear Regression algorithm, which provides a balance of simplicity and effectiveness.

## Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA) with visualizations
- Correlation matrix for feature relationships
- Crop suggestion based on input conditions
- Model training and evaluation
- Prediction of crop yields

## Data

The dataset used in this project includes the following features:
- **Nitrogen (N)**
- **Phosphorus (P)**
- **Potassium (K)**
- **Temperature (°C)**
- **Humidity (%)**
- **pH Value**
- **Rainfall (mm)**
- **Crop**
- **Yield**

## Usage

To use this project, follow the steps below:

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/nit-farmer-predict.git
    cd nit-farmer-predict
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

### Model Training

To train the model, run the following command:
```sh
jupyter notebook nit_farmer_predict.ipynb
