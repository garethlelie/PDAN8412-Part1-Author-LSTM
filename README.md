# PDAN8412/w - Part 1: Author Identification with LSTM

## Overview
This project builds an LSTM Recurrent Neural Network that predicts the most likely
author of a blog post based purely on writing style. Apache Spark is used for all
EDA steps and TensorFlow/Keras is used to build and train the model.

## Dataset
**Blog Authorship Corpus** - Schler et al. (2006)  
681,288 blog posts from 19,320 authors  
https://www.kaggle.com/datasets/rtatman/blog-authorship-corpus

> Dataset is not included in this repo due to file size (~850MB).
> Download from Kaggle and upload to your Colab session before running.

## Model Architecture
Embedding → LSTM → Dropout → Dense (Softmax)  
Improved model: Embedding → BiLSTM → LSTM → Dropout → Dense (Softmax)

## Tools Used
- Google Colab (Jupyter Notebook environment)
- Apache Spark (PySpark) - EDA
- TensorFlow / Keras - Model training
- Scikit-learn - Evaluation metrics

## Files
- `PDAN8412_Part1_Author_LSTM.ipynb` - Full analysis notebook
- `PDAN8412_Part1_Report.pdf` - Submission report

## Module
EMERIS - PDAN8412/w Programming for Data Analytics 2 (2026)
