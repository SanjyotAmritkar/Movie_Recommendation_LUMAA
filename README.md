# Movie_Recommendation_LUMAA
AI/Machine Learning Intern Challenge: Simple Content-Based Recommendation

## Dataset
This recommendation system uses the IMDb Top 250 Movies dataset, which contains information about movies like their names, genres, ratings, and more.
Steps to load the dataset:
1. Download the CSV file from the provided Kaggle link : https://www.kaggle.com/datasets/rajugc/imdb-top-250-movies-dataset
2. Upload the CSV file to your working environment (e.g., Google Colab or local directory).

# Setup Instructions

## Python Version
- Python 3.7 or higher

# Install Dependencies
You can install all the required dependencies using the following command:

pip install -r requirements.txt
Here’s the list of dependencies you can include in the requirements.txt:

pandas
scikit-learn
nltk
joblib

# Running the Code
Option 1: Running the Notebook (Recommended for Google Colab or Jupyter)
Open the Jupyter notebook (or Google Colab).
Run the cells in order. The notebook will guide you through loading the dataset, preprocessing the text, vectorizing it using TF-IDF, and recommending movies based on a user query.

Option 2: Running the Python Script
If you want to run the Python script (recommend_movies.py), follow these steps:

Run the following command in the terminal:
python recommend_movies.py "I love thrilling action movies set in space, with a comedic twist."
Replace the text in quotes with your preferred movie description.

# Example Results
Here’s a sample query and the output you can expect from the recommendation system.

Input Query: "I love thrilling action movies set in space, with a comedic twist."

Output (Top 5 Recommendations):

| Name                        | Rating |
|-----------------------------|--------|
| Alien                       | 8.5    |
| The Shawshank Redemption    | 9.3    |
| Cinema Paradiso             | 8.5    |
| Lawrence of Arabia          | 8.3    |
| Finding Nemo                | 8.2    |

