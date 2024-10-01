# Movie Recommendation System

This project implements a movie recommendation system using collaborative filtering. It utilizes user ratings to suggest movies based on similarity.

## Requirements

Make sure you have the following Python libraries installed:

- pandas
- numpy
- scikit-learn
- scipy

You can install them using pip: pip install pandas numpy scikit-learn scipy

## Dataset

The project uses the MovieLens dataset for ratings and movie information. Download the small version of the dataset and place it in a directory named `ml-latest-small`.

## Data Preparation

The data is loaded and pre-processed to create a user-item matrix, which is used for making recommendations. The matrix is filtered to include only movies with a sufficient number of ratings and users with a significant number of votes.

## Movie Recommender Function

The core of the project is the movie recommendation function, which takes a movie title and the number of recommendations as input. It finds similar movies based on user ratings and returns a list of recommended titles along with their similarity distances.

## Example Usage

To get recommendations for a movie, simply call the movie recommendation function with the desired movie title and the number of recommendations. For example, if you input "Fight Club," the system will return a list of similar movies.

## Output

The output includes a list of recommended movies and their similarity distances. This helps users discover films that are similar to their preferences.

## Conclusion

This project demonstrates how to create a simple movie recommendation system using collaborative filtering and the k-nearest neighbors algorithm. Feel free to modify and enhance the functionality!
