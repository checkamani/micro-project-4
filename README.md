# Micro-Project 4: Deep Learning Regression (MLP + LSTM)

This repository contains the full analysis and deep learning models for Micro-Project 4, predicting airline arrival delays using a 400,000 row sample from the original dataset.  
The project includes:
- A Deep Learning MLP regression model**
- A Recurrent Neural Network (LSTM) regression model**
- Training & validation loss curves
- Model evaluation using MAE, RMSE, and R²
- Final **Act** recommendations for operational decision-making

# Repository Structure

micro-project-4/

- Zeba_Micro-Project 4.ipynb      
Full Jupyter notebook with all steps

- README.md
Project overview and documentation

# Project Summary

This project builds two deep learning regression models to predict airline arrival delays:

1. MLP — Multi-Layer Perceptron (Deep Neural Network)

Fully connected feed-forward neural network

Strong performance on structured/tabular data

Provides the main baseline deep-learning model

2. LSTM — Recurrent Neural Network (RNN)

Demonstrates recurrent deep-learning modeling

Satisfies the Micro-Project 4 requirement:
“use deep learning regression techniques, including recurrent neural networks”

Reshapes tabular features into pseudo-sequences

# Methods & Workflow
— Load & sample the data (400,000 rows)
— Select numeric features only
— Standardize features (mean=0, std=1)
— Train MLP regression model
— Train LSTM regression model
— Evaluate models using MAE, RMSE, and R²
— Final ACT recommendations for operations

# How to Run
- Download the notebook:
Zeba_Micro-Project 4.ipynb
- Install required libraries:
tensorflow
numpy
pandas
scikit-learn
matplotlib

Place cleaned_flights.csv in the same directory as the notebook.
Run all cells in order.
