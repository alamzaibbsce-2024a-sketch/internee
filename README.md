# Learning Path Recommendation System

## Project Description

This project recommends personalized learning paths for interns based on their previous learning patterns.

The system uses collaborative filtering with Matrix Factorization to predict which learning modules are most suitable for each intern.

## Objective

The objective is to provide customized learning recommendations based on an intern's previous course interactions.

## Technologies Used

- Python
- Pandas
- Jupyter Notebook
- Scikit-Surprise
- SVD Matrix Factorization

## How It Works

1. Learning interaction data is created for different interns.
2. The data is converted into an intern-course rating matrix.
3. The SVD Matrix Factorization algorithm learns patterns from the data.
4. The model predicts ratings for learning modules.
5. The system recommends the top learning modules for each intern.

## Learning Modules

- Python
- Machine Learning
- Deep Learning
- SQL
- Data Science

## How to Run

1. Open `learning_path_recommendation.ipynb`.
2. Install the required libraries.
3. Run the notebook cells from top to bottom.
4. View the personalized learning recommendations.

## Project Structure

```text
Project-5-Learning-Path-Recommendation/
│
├── learning_path_recommendation.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── screenshot/
