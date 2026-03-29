# Analysis of Mineral Water Chemistry

## Overview
This project analyzes a dataset on the chemical composition of different mineral waters. Each sample is described by both **qualitative variables** (name, country, type) and **quantitative variables** (concentrations of minerals like calcium, magnesium, sodium, potassium, sulfates, nitrates, bicarbonates, and chlorides).

The main goal is to **understand the structure of the data**, identify relationships between chemical variables, and group the waters based on their characteristics.

## Steps of the Analysis

### 1. Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing  
- Visualization of distributions, correlations, and outliers  
- Analysis of variability and scale of chemical concentrations  

### 2. Principal Component Analysis (PCA)
- Dimensionality reduction to summarize chemical variability  
- Interpretation of principal components  
- Visualization of individuals (waters) and variables on correlation circles  
- Identification of key chemical signatures (mineralization types and nitrate-specific variation)  

### 3. Clustering
- **K-means clustering** to segment waters into homogeneous groups  
- **Hierarchical Agglomerative Clustering (HAC)** to confirm cluster structure  
- Use of the **elbow method** to determine the optimal number of clusters  
- Visualization of clusters on the PCA planes  

## Results
- PCA showed that **3 principal components capture over 85% of the variance**.  
- Three main chemical families were identified:  
  1. Low-mineralization waters  
  2. Sulfated-calcium waters  
  3. Bicarbonate-sodium waters  
- Clustering confirmed these groupings, allowing a clear classification of mineral waters based on their chemical composition.

  
## Conclusion

This project demonstrates how chemical data of mineral waters can be analyzed using PCA and clustering to reveal meaningful patterns. The combination of dimensionality reduction and clustering allows clear identification of chemical signatures and classification of waters into distinct groups.

---

## Author

**Ahmed Souleymane Sow**  
Master’s Student in Data Science  
African Institute for Mathematical Sciences (AIMS), Senegal  
