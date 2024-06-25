# Weather Clustering using PCA and K-means

This project explores weather data clustering using Principal Component Analysis (PCA) for dimensionality reduction and K-means clustering for pattern recognition. The goal is to identify distinct weather patterns across various locations and seasons based on multiple weather attributes.

## Overview

The dataset used in this project consists of synthetic weather-related features collected at different times and locations. These features include temperature, humidity, wind speed, precipitation, cloud cover, atmospheric pressure, UV index, visibility, season, location type, and weather type (e.g., rainy, cloudy, sunny).

### Notebook Breakdown

- **Setup**: Imports necessary libraries and initializes data loading.
  
- **Exploratory Data Analysis (EDA)**:
  - Provides insights into the dataset's structure, distributions, and relationships between weather features.
  
- **Analysis**:
  - **Preprocessing**: Encodes categorical variables and scales numerical features for PCA and clustering.
  - **Dimensionality Reduction**: Applies PCA to reduce feature dimensions for improved clustering efficiency.
  - **Clustering**: Utilizes K-means clustering to identify and analyze distinct weather clusters based on PCA-transformed data.
  - **Evaluation**: Evaluates clustering results using visualization techniques and cluster metrics.
  
- **Conclusion**:
  - Summarizes findings from the analysis, highlighting insights into weather patterns and the effectiveness of PCA and K-means clustering.
  - Suggests potential areas for further exploration or improvement.

## Files Included

- **Notebook**: `weather_clustering.ipynb` - Contains the Python code, analysis, and visualizations.
- **Dataset**: `weather_classification_data.csv` - Synthetic dataset of weather attributes.

## Usage

1. **Environment Setup**:
   - Ensure Python environment is set up with necessary libraries (scikit-learn, pandas, matplotlib, seaborn).

2. **Data Loading**:
   - Load the dataset `weather_classification_data.csv` into your working environment.

3. **Notebook Execution**:
   - Open and execute `weather_clustering.ipynb` in Jupyter Notebook or any compatible environment.

4. **Exploration and Analysis**:
   - Follow along with the notebook sections to explore EDA, preprocessing, PCA, and K-means clustering steps.
   - Analyze clustering results and visualize weather patterns identified by the model.

## Requirements

- Python 3.x
- Jupyter Notebook or JupyterLab
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Acknowledgments

- This project utilizes a synthetic weather dataset sourced from [Kaggle](https://www.kaggle.com/datasets/nikhil7280/weather-type-classification/code).
- Credits to the creators of scikit-learn, pandas, and other open-source libraries used in the analysis.