# Fraudulent Insurance Claim Detection

## Objective:
The main objective of this project is to develop a robust classification model capable of identifying fraudulent vehicle insurance claims from genuine ones.

## About the Dataset:
The dataset comprises information collected from various sources, including census bureaus, to analyze patterns in insurance claims. It consists of 38 features, including the target variable indicating the authenticity of the claim.

## Project Overview:
The project commenced with data collection from multiple sources, followed by extensive data validation and insertion into a SQLite database. The data was then segregated into valid and fraudulent categories based on predefined schema rules. Key steps involved in the project lifecycle include data preprocessing (addressing imbalanced datasets using Imblearn's Random Oversampler), clustering using K-means, model selection (evaluating multiple models and choosing the top performers based on accuracy and AUC scores), model building (utilizing XGBoost and SVC algorithms), hyperparameter optimization (using GridSearchCV), and ultimately deploying the models on Google Cloud Platform (GCP), Amazon Web Service (AWS), or Hiroku Platform. Extensive API testing using Postman and comprehensive logging at each stage ensured project transparency and traceability. The codebase adheres to object-oriented programming principles.


## Project Architecture:

![Project Architecture](https://user-images.githubusercontent.com/75041273/129022437-05b6056a-8943-47d3-a4a3-da17acfbb9e3.png)

## Installation Guide:
The project is developed using Python 3.9 or above. If you don't have Python installed, you can download it from the [official website](https://www.python.org/downloads/). For users with older Python versions, upgrading is possible using the pip package manager. To install all necessary packages and libraries, follow these steps after cloning the repository:

##### 1. Create a virtual environment using the following command:
```bash
conda create -n myenv python=3.7
```
#### 2. Activate the virtual environment with:
```
conda activate myenv
```
#### 3. Install required packages using:
```
pip install -r requirements.txt
```
#### 4. Finally, execute the following command in cmd or Anaconda prompt:
```
Code
python main.py
```
Ensure that the directory is set to the root folder of the project.
