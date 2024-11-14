Laptop Price Prediction

Table of Contents

1. Introduction
2. Project Objective
3. Features
4. Dataset
5. Modeling and Algorithm
6. Website Integration
7. Performance Evaluation
8. Contact

-------------------------------

-> Introduction

The Laptop Price Prediction project is a machine learning solution that predicts laptop prices based on a range of configurations. The model is designed to assist users—especially students and budget-conscious buyers—in making informed decisions when comparing laptop prices with desired specifications.

-> Project Objective

This project addresses a real-world problem by helping users quickly and accurately estimate laptop prices across different brands and configurations. Users can compare prices and features conveniently on a single platform.

-> Features

The model predicts prices based on the following key features:

1. Brand: Type of laptop manufacturer.

2. RAM: Amount of RAM.

3. Weight: Weight of the laptop.

4. Touchscreen: Availability of touchscreen.

5. IPS Display: Presence of an IPS screen.

6. Screen Size: Physical size of the display.

7. Resolution: Screen resolution.

8. CPU: Type of processor.

9. HDD: Hard disk drive capacity.

10. SSD: Solid-state drive capacity.

11. GPU: Graphics processing unit.

12. Operating System: Installed operating system.


-> Dataset

The dataset used includes a wide range of laptops and their respective configurations. Prices in the dataset reflect current market values, which enable accurate model training and validation.

1. Source: https://github.com/campusx-official/laptop-price-predictor-regression-project/blob/main/laptop_data.csv

2. Size: (1303, 12)


-> Modeling and Algorithm

This project uses the Random Forest Regression algorithm, selected for its robustness and capability to handle various features effectively.

1. Algorithm: Random Forest Regression

2. Model Score: R2 Score 0.8873402378382488, MAE 0.15860130110457718

3. Accuracy: The model achieves minimal error, with approximate differences of only a few thousand compared to actual prices (e.g., if predicted price is INR 74,000, actual might be INR 78,000).


-> Website Integration

A user-friendly web interface has been created for this model:

1. Features: Allows users to input laptop specifications and receive an approximate price.

2. Functionality: Displays real-time predictions that users can compare with prices on major platforms such as Amazon and Flipkart.

3. Platform: Built using Streamlit.


-> Performance Evaluation

The model’s performance is validated against actual prices:

1. Prediction Comparison: Example predictions show minimal error, consistently staying within a small margin of actual market prices.


-> Prerequisites

1. Python >= 3.8.20

2. Libraries: scikit-learn, pandas, numpy, streamlit, seaborn, etc.


-> Contact

Navdeep Kaur Sokhi
LinkedIn- https://www.linkedin.com/in/navdeep-kaur-sokhi-05b024252/