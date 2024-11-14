# Food Recipe Rating Prediction

**Overview:** This project focuses on predicting the ratings of food recipes based on a dataset containing recipe names, reviews, and various features. By leveraging machine learning techniques, the aim is to develop a model that can accurately predict recipe ratings based on text reviews and other relevant attributes.

## Features
- **Comprehensive Dataset**: The dataset includes recipe names, reviews, and additional features that contribute to understanding and predicting ratings.
- **Exploratory Data Analysis (EDA)**: Initial analysis of the dataset to gain insights into the distribution of ratings and the impact of different features.
- **Feature Engineering**: Transformation of raw data into meaningful features to improve model performance.
- **Modeling and Evaluation**: Comparison of various models to identify the best-performing approach for predicting ratings.

## Approach
1. **Data Preprocessing**: Cleaned the dataset to handle missing values, normalize text reviews, and transform categorical features.
2. **Feature Engineering**: Extracted relevant features, such as word frequency in reviews, ingredient counts, and recipe length.
3. **Model Selection**: Tested multiple models, including linear regression, random forests, and gradient boosting, to find the most accurate prediction model.
4. **Evaluation**: Used metrics like RMSE and R-squared to evaluate and compare model performance.

## Screenshots
![image](https://github.com/user-attachments/assets/e67241ea-b315-40be-a357-52499a1d3682)
![image](https://github.com/user-attachments/assets/5b9c0ac5-cb53-4d9d-8ed8-7f6819f4ad2c)
![image](https://github.com/user-attachments/assets/734f2592-875a-4f5b-8e77-e2f53c593045)
![image](https://github.com/user-attachments/assets/4fe2a30e-8c84-4457-b651-16340b53e9eb)
![image](https://github.com/user-attachments/assets/2dade6b9-f8ef-428f-9dc7-13b30ed7df0e)
![image](https://github.com/user-attachments/assets/f539dc1e-34d5-4730-a2da-dc41fb65272e)
![image](https://github.com/user-attachments/assets/01973cce-bf54-4463-acbb-cc27f1aa2de3)

## Results
The model successfully predicts recipe ratings, with various models accuracies, providing valuable insights into customer preferences and recipe quality.
1. **Logistic Regression** : 0.778511
2. **Random Forest** : 0.775577
3. **KNN** : 0.737873
4. **SVM** : 0.784745
5. **XGBoost** : 0.777411

## Future Improvements
- **Advanced Text Analysis**: Implement natural language processing (NLP) techniques to further analyze review sentiments.
- **Additional Data**: Incorporate other data sources, such as user demographics, to enhance prediction accuracy.

## How to Use
1. **Clone the repository**:
   ```bash
   git clone <repository_url>
   cd food-recipe-rating
   ```
2. **Run the notebook**: Open the Jupyter notebook `kaggle notebook.ipynb` and execute the cells to view data analysis, feature engineering, model training, and evaluation.

---

This README file offers a comprehensive guide to the Food Recipe Rating Prediction project, covering its dataset, features, approach, and setup instructions, helping users and contributors seamlessly understand and engage with the predictive model development process.
