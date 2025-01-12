# US Accident Analysis and Visualization

## Overview
This project focuses on analyzing and visualizing US accident data by leveraging key attributes such as city, start time, geographical coordinates, temperature, and weather conditions. The goal is to uncover insights about accident patterns and predict the likelihood of accidents using various machine learning models.

## Key Features
- **Data Analysis**:
  - **City-wise Analysis**: Identifying trends and distributions of accidents across different cities.
  - **Start Time Analysis**: Examining accident patterns based on the time of occurrence.
  - **Geographical Analysis**: Insights derived from start latitude and longitude.
  - **Temperature-wise Analysis**: Studying the impact of temperature on accident frequency.
  - **Weather-wise Analysis**: Understanding how different weather conditions affect accidents.
- **Machine Learning Models**:
  - Random Forest Classifier
  - K-Nearest Neighbors (KNN)
  - Voting Classifier
  - AdaBoost Classifier

## Dataset
The dataset includes the following key attributes:
- **City**: Location of the accident.
- **Start Time**: Timestamp indicating when the accident occurred.
- **Start Latitude and Longitude**: Geographic coordinates of the accident.
- **Temperature**: Temperature at the time of the accident.
- **Weather Condition**: Weather description during the accident.

## Analysis and Insights
1. **City-wise Accident Analysis**:
   - Visualized the distribution of accidents across various cities to identify high-risk areas.
   - Used bar charts and heatmaps for a comprehensive city-level understanding.

2. **Start Time Analysis**:
   - Analyzed trends based on the time of day, days of the week, and months.
   - Identified peak hours and days with higher accident rates.

3. **Geographical Analysis**:
   - Mapped accidents using latitude and longitude coordinates.
   - Created scatter plots to highlight accident-prone regions.

4. **Temperature-wise Analysis**:
   - Correlated accident frequency with temperature variations.
   - Explored how extreme temperatures influence accident occurrences.

5. **Weather-wise Analysis**:
   - Analyzed the impact of different weather conditions on accident likelihood.
   - Studied patterns during rain, snow, fog, and clear weather conditions.

## Machine Learning Workflow
1. **Data Preprocessing**:
   - Handling missing values.
   - Encoding categorical features.
   - Scaling numerical features.
2. **Feature Engineering**:
   - Extracting time-based features from start time (e.g., hour, day of the week).
   - Categorizing weather conditions.
3. **Model Training and Evaluation**:
   - Splitting the dataset into training and testing sets.
   - Training and evaluating the following models:
     - **Random Forest Classifier**: Ensemble method leveraging decision trees.
     - **K-Nearest Neighbors (KNN)**: Instance-based learning algorithm.
     - **Voting Classifier**: Combines predictions from multiple models.
     - **AdaBoost Classifier**: Boosting algorithm to improve weak learners.
   - Model performance is assessed using metrics like accuracy, precision, recall, and F1-score.

## Tools and Libraries
- **Python**: Primary programming language.
- **Data Analysis**: Pandas, NumPy.
- **Data Visualization**: Matplotlib, Seaborn, Plotly.
- **Machine Learning**: scikit-learn.








