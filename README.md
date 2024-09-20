# Real Estate Price Prediction Project 🏠

## Demo Video 🎥

Watch the demo video for an overview of the Real Estate Price Prediction project:

[Download Demo Video included in repository]

## Project Screenshot

[Project Screenshot](model/Project_Screenshot.png)

---
## Introduction

This project involves creating a Machine Learning model to predict real estate prices in Bangalore, India. I also developed a single-page website to provide a front-end interface for accessing model’s predictions.

## Data Science Concepts Utilized

- Data Loading and Cleaning
- Outlier Detection and Removal
- Feature Engineering
- Dimensionality Reduction
- GridSearchCV for Hyperparameter Tuning
- K-Fold Cross Validation

## Technologies and Tools

- **Python**
- **Numpy** and **Pandas** for Data Cleaning
- **Matplotlib** for Data Visualization
- **Sklearn** for Model Building
- **Jupyter Notebook**
- **Python Flask** for HTTP Server
- **HTML/CSS/JavaScript** for UI

## Project Steps

1. **Import the Required Libraries**
2. **Load the Data**
3. **Understand the Data**
   - Drop unnecessary columns
4. **Data Cleaning**
   - Check for NA values
   - Verify unique values of each column
   - Ensure values are correct (e.g., a 23 BHK home with 2000 sq. ft. size is incorrect)
   - Feature Engineering
   - Dimensionality Reduction
   - Outlier Removal using Domain Knowledge (e.g., 2 BHK price < 3 BHK price, size per BHK >= 300 sq. ft.)
   - Outlier Removal using Standard Deviation and Mean
   - One Hot Encoding
5. **Build Machine Learning Model**
6. **Test the Model**
7. **Export the Model**
8. **Export Any Other Important Information**

## Dataset Reference

- **Bengaluru House Price Data**

The dataset is available in this repository as `Bengaluru_House_Data.csv`.

---
