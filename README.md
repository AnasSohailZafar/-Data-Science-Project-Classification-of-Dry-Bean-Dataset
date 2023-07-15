# Data Science Project: Classification of Dry Bean Dataset
This project focuses on the classification of the Dry Bean Dataset using various machine learning algorithms such as Random Forest, Support Vector Machine (SVM), and Decision Tree. The objective is to predict the class of dry beans based on their physical attributes.

## Table of Contents

- [Introduction](#introduction)
- [Dataset Description and Exploration](#dataset-description-and-exploration)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact Information](#contact-information)

## Introduction

In this project, we explore the Dry Bean Dataset and apply different classification algorithms to predict the class of dry beans. The dataset contains 13 numerical attributes describing various physical characteristics of dry beans, such as area, perimeter, compactness, and more. The target variable is the class of the dry bean.

## Dataset Description and Exploration

- The dataset used in this project is provided in the file `Dry_Bean_Dataset.xlsx`.
- The dataset consists of 13 features and 1 target variable (Class).
- It contains a total of 13,611 instances.
- The classes in the dataset include DERMASON, SIRA, SEKER, HOROZ, CALI, BARBUNYA, and BOMBAY.

## Installation:

To run this project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/dry-bean-classification.git

2. Install the required dependencies:

pip install pandas scikit-learn matplotlib seaborn

3. Download the dataset (Dry_Bean_Dataset.xlsx) and place it in the project directory.

## Usage:

Open the Jupyter Notebook or Python script for the classification algorithms.
Run the code cells or execute the script to perform the following steps:
Load the dataset.
Explore the dataset by displaying general information, class distribution, and statistical summary.
Check for null values in the dataset.
Split the dataset into training and testing sets.
Scale the features using standardization.
Train and evaluate the Random Forest, SVM, and Decision Tree classifiers.
Generate classification output files for each model.
Visualize the confusion matrix for model evaluation.
