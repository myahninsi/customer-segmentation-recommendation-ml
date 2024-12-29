# E-commerce Customer Analysis and Recommendation System

## Project Overview
This project analyzes customer behavior data from an e-commerce platform to derive actionable insights and enhance the shopping experience. Key goals include customer segmentation, value prediction, and personalized product recommendations using machine learning.

### Key Contributions
- Customer Segmentation
  - Implemented a K-Means clustering model to group customers based on total spending and purchasing behavior.
  - Used the Elbow Method to determine the optimal number of clusters.
- Predictive Modeling
  - Developed a Random Forest regression model to predict total expenditure per customer, achieving an R-squared score of 0.76 and Mean Absolute Error (MAE) of 1983.46.
- Recommendation System
  - Built a collaborative filtering recommendation system that utilizes cosine similarity to identify similar customers and recommend top products based on shared purchasing patterns.

## Problem Statement
E-commerce platforms face challenges in understanding diverse customer behaviors and delivering personalized shopping experiences. This project focuses on:
- Grouping customers into meaningful segments
- Predicting customer expenditure for better resource allocation
- Recommending relevant products to improve customer satisfaction and retention

## Technologies and Skills
- Data Analysis
   - Exploratory Data Analysis (EDA) to understand patterns in customer behavior
- Clustering
   - K-Means clustering for segmentation
- Predictive Modeling
   - Random Forest regression for expenditure prediction
- Recommendation Systems
   - Collaborative filtering for personalized product suggestions
- Programming and Tools
   - Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Project Workflow
1. Data Loading and Preprocessing
   - Cleaned and prepared transaction data
   - Converted date columns and managed outliers using the Interquartile Range (IQR) method

2. Exploratory Data Analysis (EDA)
   - Conducted visualizations such as histograms, line charts, and bar graphs to uncover patterns
   - Identified key metrics like average order value (AOV) and top customers/products

3. Modeling and Prediction
   - Clustering: Applied K-Means to segment customers into distinct groups based on spending
   - Expenditure Prediction: Built a Random Forest regression model to forecast total customer expenditure with high accuracy

4. Recommendation System
   - Developed a collaborative filtering model leveraging cosine similarity to recommend top products for each customer based on similar purchasing behavior

## Results
- Identified distinct customer segments for targeted marketing strategies
- Predicted customer expenditure, aiding resource prioritization
- Recommended personalized products, enhancing user satisfaction and sales potential

## Future Enhancements
- Incorporate real-time recommendation capabilities
- Explore deep learning models for better recommendations
- Integrate additional customer demographic features for improved segmentation

## License
This project is licensed under the MIT License