# Global Quality of Life Analysis

**Tools:** R (tidyverse, ggplot2, FactoMineR, cluster, factoextra)
**Dataset:** 236 countries, 9 socioeconomic indicators (Kaggle)

## Overview
Analyzed global quality of life using PCA, discriminant analysis, 
multivariate regression, and clustering to identify the key drivers 
of national wellbeing.

## My Contributions
- Data cleaning: missing values, regex conversions, standardization
- Multivariate regression: forward/backward/stepwise selection (R² = 0.983)
- Clustering: full K-means and K-Medoids analysis, elbow method, 
  silhouette scoring (K-means score 0.38 vs K-Medoids 0.22)
- Report writing: synthesized all findings into policy-oriented narrative

## Key Findings
- Purchasing power, healthcare, and safety were the strongest 
  positive predictors of quality of life
- K-means clustering revealed 3 distinct country groups: 
  high-income nations, developing economies, and structurally 
  disadvantaged countries with extreme housing unaffordability
- Cost of living was statistically insignificant and excluded 
  from the final model

## Methods
- PCA (3 components explaining 67% of variance)
- LDA/QDA/Naive Bayes discriminant analysis
- Multivariate regression with stepwise selection
- K-means and K-Medoids clustering (K=3)
