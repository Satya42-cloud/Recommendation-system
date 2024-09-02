# Recommendation-system

## Anime Recommendation System Using Cosine Similarity

### Objective
The objective of this assignment is to implement a recommendation system for anime using cosine similarity. The system aims to recommend similar anime based on features such as genres and user ratings from a given anime dataset.

### Dataset
#### Dataset Description:
- Unique ID: Identifier for each anime.
- Title: Name of the anime.
- Broadcast Type: Type of anime broadcast (e.g., TV, OVA).
- Genre: Categories or genres of the anime.
- Number of Episodes: Total episodes of the anime.
- Average Rating: User rating average for the anime.
- Community Members: Number of community members for each anime.
  
### Data Preprocessing
#### Load Data:
- Load the dataset into a suitable data structure, such as a pandas DataFrame.
#### Handle Missing Values:
- Address any missing values in the dataset through imputation or removal.
#### Explore Dataset:
- Examine the dataset to understand its structure, attributes, and distribution of data.
  
### Feature Extraction
#### Feature Selection:
- Choose relevant features for computing similarity, including genres and user ratings.
#### Categorical to Numerical:
- Convert categorical features into numerical representations if necessary (e.g., one-hot encoding for genres).
#### Normalization:
- Normalize numerical features to ensure consistent scaling across the dataset.

### Recommendation System
#### Cosine Similarity Function:
- Design a function to compute cosine similarity between anime based on selected features.
#### Recommendation Engine:
- Implement a recommendation engine to suggest similar anime based on cosine similarity scores.
#### Threshold Adjustment:
- Experiment with different similarity score thresholds to adjust the size and relevance of the recommendation list.

### Evaluation
#### Train-Test Split:
- Split the dataset into training and testing sets for model validation.
#### Performance Metrics:
- Evaluate the recommendation system using metrics such as precision, recall, and F1-score.
#### Performance Analysis:
- Analyze the performance of the recommendation system to identify strengths and areas for improvement.
