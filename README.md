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

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/dry-bean-classification.git
```
2. Install the required dependencies:

pip install pandas scikit-learn matplotlib seaborn

3. Download the dataset (Dry_Bean_Dataset.xlsx) and place it in the project directory.

## Usage
```
•	Open the Jupyter Notebook or Python script for the classification algorithms.

•	Run the code cells or execute the script to perform the following steps:

•	Load the dataset.

•	Explore the dataset by displaying general information, class distribution, and statistical summary.

•	Check for null values in the dataset.

•	Split the dataset into training and testing sets.

•	Scale the features using standardization.

•	Train and evaluate the Random Forest, SVM, and Decision Tree classifiers.

•	Generate classification output files for each model.

•	Visualize the confusion matrix for model evaluation.
```

## Results

The project evaluates the performance of three classification algorithms on the Dry Bean Dataset: Random Forest, SVM, and Decision Tree. The evaluation metrics include precision, recall, F1-score, and accuracy.

Here are the results obtained:

|Methods | Accuracy |	Precison | Recall |	F1-scores|
|--------| ---------| ---------| -------| ---------|
|RFC	   | 92.54	  |  92.59	 | 92.54	| 92.56	   |
|SVM	   | 93.33	  |  93.43	 | 93.38	| 93.40	   |
|DTC	   | 89.27	  |  89.31	 | 89,27	| 92.5	   |

![image](https://github.com/AnasSohailZafar/-Data-Science-Project-Classification-of-Dry-Bean-Dataset/assets/123377727/c48253d2-b51d-481d-95bf-6cd0188e0e3b)

Confusion matrix for Random Forest Classifier:

![image](https://github.com/AnasSohailZafar/-Data-Science-Project-Classification-of-Dry-Bean-Dataset/assets/123377727/6fb5d8af-b7ad-4c19-b203-23bf66eb513e)

Confusion Matrix for SVM:

![image](https://github.com/AnasSohailZafar/-Data-Science-Project-Classification-of-Dry-Bean-Dataset/assets/123377727/afff7ff6-86f2-44f1-bafc-f06a0fce4382)



## Contributing

Contributions to this project are welcome. If you would like to contribute, please follow these steps:

1.	Fork the repository.

2.	Create a new branch.

3.	Make your enhancements or bug fixes.

4.	Create a pull request with a descriptive title and explanation of your changes.

## License

This project is licensed under the MIT License.

## Contact Information

For any questions or suggestions, please feel free to reach out :

Name:     Anas Sohail Zafar

Email:    anassohailzafar@gmail.com

GitHub:   [github.com/AnasSohailZafar](https://github.com/AnasSohailZafar)

Linkedin: www.linkedin.com/in/anas-sohail-zafar123
