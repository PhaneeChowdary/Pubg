# PUBG Finish Placement Prediction

This project explores the **PUBG Finish Placement Prediction** dataset from Kaggle and implements a data preprocessing and feature optimization pipeline to reduce dataset size while preserving relevant information. The goal is to support model training for predicting a player's final placement in PUBG matches.

## Project Highlights

- **Dataset**: [Kaggle PUBG Finish Placement Prediction](https://www.kaggle.com/c/pubg-finish-placement-prediction/data)
- **Primary Objective**: Predict final placement of players in a match.
- **Tech Stack**: Python, Pandas, NumPy, Matplotlib, Scikit-learn

## Features

- Automated memory reduction by:
  - Iterating over columns
  - Identifying numeric types
  - Downcasting to smallest suitable data types
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering for modeling
- Baseline model setup and evaluation (can be extended)


## To run this project on your local machine

1. Clone the repository:
   ```bash
   git clone https://github.com/PhaneeChowdary/Pubg.git
   cd Pubg
   ```
2. pip install -r requirements.txt
3. Download the dataset
  ```
  import opendatasets as od
  od.download('https://www.kaggle.com/c/pubg-finish-placement-prediction/data')
  ```
## Thank you
