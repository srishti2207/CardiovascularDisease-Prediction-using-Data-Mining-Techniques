# Cardiovascular Disease Prediction Project

This project focuses on predicting cardiovascular disease (CVD) using various machine learning classifiers. The dataset contains medical information including age, gender, height, weight, blood pressure, cholesterol, glucose levels, smoking habits, alcohol consumption, physical activity, and cardiovascular disease diagnosis.

## Project Structure

- **Data Loading and Exploration**: Loading the dataset and performing initial exploration to understand the data distribution and identify any missing or duplicate values.
- **Data Preprocessing**: Handling missing values, encoding categorical features, and scaling numerical features.
- **Model Training and Evaluation**: Training various machine learning models and evaluating their performance using metrics such as accuracy, precision, recall, and F1-score.
- **Hyperparameter Tuning**: Using GridSearchCV to find the optimal hyperparameters for the models.

## Installation

To run this project, you need to have the following Python packages installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Open the Jupyter Notebook (`CVD_Project.ipynb`) using Jupyter Notebook or Jupyter Lab.
4. Run the cells sequentially to execute the code.

## Data

The dataset used in this project is assumed to be stored in a file named `cardio_train.csv` within the project directory. The dataset includes the following columns:

- `id`: Identifier of the record
- `age`: Age of the person
- `gender`: Gender of the person (1: Female, 2: Male)
- `height`: Height of the person (in cm)
- `weight`: Weight of the person (in kg)
- `ap_hi`: Systolic blood pressure
- `ap_lo`: Diastolic blood pressure
- `cholesterol`: Cholesterol level (1: normal, 2: above normal, 3: well above normal)
- `gluc`: Glucose level (1: normal, 2: above normal, 3: well above normal)
- `smoke`: Smoking status (0: no, 1: yes)
- `alco`: Alcohol intake (0: no, 1: yes)
- `active`: Physical activity (0: no, 1: yes)
- `cardio`: Presence or absence of cardiovascular disease (0: no, 1: yes)

## Results

The notebook evaluates multiple machine learning models, including:

- Support Vector Classifier (SVC)
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Random Forest Classifier
- Logistic Regression
- Multilayer Perceptron (MLP) Classifier

The performance of each model is assessed using metrics such as accuracy, precision, recall, and F1-score.

