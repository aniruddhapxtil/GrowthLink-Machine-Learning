# GrowthLink-Machine-Learning
Repo for all the task of Internship 
# Movie Genre Classification from Plot Descriptions

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0%2B-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A machine learning project that classifies movies into genres based on their plot descriptions using various NLP techniques and classification algorithms.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Project Overview

This project aims to develop a machine learning model that can accurately predict a movie's genre based solely on its plot description. The system processes raw text data through NLP techniques, converts it into numerical features, and evaluates multiple classification algorithms to determine the best approach.

Key components:
- Text preprocessing and cleaning
- TF-IDF feature extraction
- Multiple classifier evaluation
- Model interpretation and analysis

## Dataset

The dataset consists of movie entries in the following format:
1 ::: Oscar et la dame rose (2009) ::: drama ::: Listening in to a conversation between his doctor and parents...



## Features

- **Text Processing**:
  - Special character removal
  - Lemmatization
  - Stopword removal
  - N-gram generation

- **Machine Learning Models**:
  - Naive Bayes
  - Logistic Regression
  - Support Vector Machines
  - Random Forest

- **Evaluation Metrics**:
  - Accuracy
  - F1-score
  - Confusion matrices
  - Cross-validation results

- **Visualizations**:
  - Genre distribution
  - Feature importance
  - Confusion matrices

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/movie-genre-classification.git
cd movie-genre-classification
