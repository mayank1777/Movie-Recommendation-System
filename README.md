## Movie Recommendation System

This project implements an advanced recommendation system for movies using a unique combination of Reduced Singular Value Decomposition (SVD) and K-means clustering. The system is designed to analyze user preferences based on movie genres, providing more accurate and personalized movie suggestions.

## Features
- `Data Preprocessing`: Standardizes movie IDs and aligns them across datasets to ensure consistent and accurate data handling.
- `Exploratory Data Analysis (EDA)`: Provides insights into user preferences and data sparsity, helping guide the modeling strategy.
- `SVD and K-Means Clustering`: Utilizes SVD for dimensionality reduction, capturing essential latent factors of user preferences, followed by K-means clustering to group users into clusters based on these preferences.

## Novelty
- `Enhanced Metric System`: Integrates multiple evaluation metrics like MAE, RMSE, and MAPE, weighted to balance different error characteristics for a comprehensive performance assessment.
- `Diverse Movie Recommendations`: Implements a selection strategy that ensures variety by incorporating top-rated movies across different genres.
- `IDF in Similarity Calculation`: Applies Inverse Document Frequency (IDF) in the similarity calculation to enhance the accuracy of user preference predictions.

## Requirements
- Python 3.8+
- Libraries: NumPy, Pandas, SciPy, Scikit-Learn


## Contributing

Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

## Authors
Mayank Sharma, Aasmaan Gupta, Nimish Gaur 
International Institude of Information Technology, Bangalore



