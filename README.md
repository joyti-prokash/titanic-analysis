# Titanic Survival Prediction

## Project Overview
This project aims to predict the survival of passengers on the Titanic using machine learning techniques. The dataset is from [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic). The goal is to build a model that can classify passengers as survived or not based on features such as age, sex, class, fare, and family relationships.

## Dataset
- **Source:** Kaggle Titanic Dataset  
- **Number of rows:** 418  
- **Number of features:** 9 (after preprocessing)  
- **Target variable:** `Survived` (0 = No, 1 = Yes)

## Features Used
- `PassengerId` – Unique ID of each passenger  
- `Pclass` – Passenger class (1, 2, 3)  
- `Sex` – Gender (0 = Male, 1 = Female)  
- `Age` – Age of the passenger  
- `SibSp` – Number of siblings/spouses aboard  
- `Parch` – Number of parents/children aboard  
- `Fare` – Ticket fare  
- `Embarked_Q` – Embarked at Queenstown (binary dummy)  
- `Embarked_S` – Embarked at Southampton (binary dummy)

## Data Preprocessing
- Converted `Sex` to numeric (male = 0, female = 1)  
- Filled missing values in `Age` and `Fare` with the median  
- Dropped `Cabin`, `Name`, and `Ticket` columns due to high missing values or irrelevance  
- Created dummy variables for `Embarked`  

## Model
- **Algorithm:** Logistic Regression  
- **Train-Test Split:** 80% training, 20% testing  
- **Accuracy:** 100% on the test set (overfitting possible due to small dataset)

## Evaluation
- Confusion Matrix:

|       | Predicted No | Predicted Yes |
|-------|-------------|---------------|
| Actual No  | 50          | 0             |
| Actual Yes | 0           | 34            |

- Observations: The model achieved perfect accuracy, indicating a simple but strong predictive pattern in the dataset.

## How to Run
1. Clone the repository:  
   ```bash
   git clone # Titanic Survival Prediction

## Project Overview
This project aims to predict the survival of passengers on the Titanic using machine learning techniques. The dataset is from [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic). The goal is to build a model that can classify passengers as survived or not based on features such as age, sex, class, fare, and family relationships.

## Dataset
- **Source:** Kaggle Titanic Dataset  
- **Number of rows:** 418  
- **Number of features:** 9 (after preprocessing)  
- **Target variable:** `Survived` (0 = No, 1 = Yes)

## Features Used
- `PassengerId` – Unique ID of each passenger  
- `Pclass` – Passenger class (1, 2, 3)  
- `Sex` – Gender (0 = Male, 1 = Female)  
- `Age` – Age of the passenger  
- `SibSp` – Number of siblings/spouses aboard  
- `Parch` – Number of parents/children aboard  
- `Fare` – Ticket fare  
- `Embarked_Q` – Embarked at Queenstown (binary dummy)  
- `Embarked_S` – Embarked at Southampton (binary dummy)

## Data Preprocessing
- Converted `Sex` to numeric (male = 0, female = 1)  
- Filled missing values in `Age` and `Fare` with the median  
- Dropped `Cabin`, `Name`, and `Ticket` columns due to high missing values or irrelevance  
- Created dummy variables for `Embarked`  

## Model
- **Algorithm:** Logistic Regression  
- **Train-Test Split:** 80% training, 20% testing  
- **Accuracy:** 100% on the test set (overfitting possible due to small dataset)

## Evaluation
- Confusion Matrix:

|       | Predicted No | Predicted Yes |
|-------|-------------|---------------|
| Actual No  | 50          | 0             |
| Actual Yes | 0           | 34            |

- Observations: The model achieved perfect accuracy, indicating a simple but strong predictive pattern in the dataset.

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/joyti-prokash/Titanic-Survival-Prediction.git
