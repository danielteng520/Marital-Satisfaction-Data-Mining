# Marital Satisfaction Data Mining Project

This repository contains the group project for **TDS 3301: Data Mining**. The study examines various factors influencing marital satisfaction across a diverse sample of individuals from multiple countries. By applying data mining techniques, we identified key predictors of marital satisfaction and explored patterns through clustering, classification, and association rule mining.

## Project Overview
The project investigates marital satisfaction and its key determinants across different demographics and relationship variables. Using a dataset of self-reported marital satisfaction from 7,178 individuals across 33 countries, this study aims to uncover patterns and relationships that can guide interventions and improve relationship outcomes.

## Dataset
Unfortunately, the dataset could not be included in this repository as it could not be located on my local machine. I apologize for any inconvenience this may cause. The dataset consisted of:
- **7,178 participants** from 33 countries.
- **Variables**: Demographic data, family characteristics, education, economic status, religious affiliation, and level of collectivism.
- **Assessment Categories**: Three primary categories for marital satisfaction (MS1, MS2, MS3).

## Key Steps and Findings
### 1. Data Cleaning and Preprocessing
- **Data Binning**: Variables for marital satisfaction were categorized into ‘low’, ‘moderate’, and ‘high’ satisfaction levels for simplified analysis.
- **Handling Inconsistencies**: Addressed empty or irrelevant values, ensuring only meaningful data remained.

### 2. Exploratory Data Analysis (EDA)
- Analyzed variables like age distribution, gender ratio, and marriage duration.
- Examined the relationship between marital satisfaction and factors such as the number of children, economic status, and educational level.

### 3. Feature Selection
- **Boruta Algorithm**: Employed to select the most relevant features for modeling marital satisfaction. Key features included country, love-related variables, self-esteem, and overall happiness.

### 4. Pattern Discovery
- **Classification Models**: Compared performance of Naive Bayes, K-Nearest Neighbors (KNN), Random Forest, Support Vector Machine (SVM), and Neural Network models. Neural Network and KNN models provided the best predictive accuracy.
- **Association Rule Mining**: Used the Apriori algorithm to uncover associations between relationship factors and satisfaction levels.

### 5. Clustering Analysis
- **K-Means Clustering**: Applied to identify clusters within the dataset based on marital satisfaction factors.
- **Silhouette Score and WCSS**: Used to evaluate clustering quality and determine the optimal number of clusters.

## Results
- **Model Performance**: Neural Network achieved the highest accuracy for MS1, KNN for MS2, and both KNN and Random Forest were effective for MS3.
- **Association Patterns**: High satisfaction was associated with mutual respect, engagement in activities together, and emotional fulfillment.

## Future Work
- Expanding the dataset, exploring additional cultural contexts, and incorporating qualitative analysis to better understand marital satisfaction factors.

## License
This project is for educational purposes as part of coursework for TDS 3301.
