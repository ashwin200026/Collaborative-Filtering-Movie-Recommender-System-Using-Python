
## Collaborative Filtering Movie Recommender System Using Python (Non-Negative Matrix Factorization)

This repository contains a Collaborative Filtering Movie Recommender System using Python (Non-Negative Matrix Factorization).

Methodology

Non-Negative Matrix Factorization (NMF) is a collaborative filtering method that can be used to build recommender systems. It works by decomposing the user-item interaction matrix into two lower-dimensional matrices: a user factor matrix and an item factor matrix. The user factor matrix represents the user's preferences for different latent factors, while the item factor matrix represents the item's characteristics with respect to the same latent factors.

To train an NMF recommender system, we first need to collect a dataset of user-item interactions. This dataset can be in the form of ratings, views, purchases, or other types of interactions. Once we have the dataset, we can use an NMF algorithm to decompose the user-item interaction matrix into the user factor matrix and the item factor matrix.

Once the model is trained, we can use it to generate recommendations for users by multiplying the user factor matrix and the item factor matrix together. This will produce a predicted rating matrix, which we can then use to recommend items to users with the highest predicted ratings.

Advantages of NMF

* NMF is a simple and efficient algorithm that can be easily implemented.
* NMF is interpretable, meaning that we can use the user factor matrix and the item factor matrix to understand the user's preferences and the item's characteristics.
* NMF is robust to noise and missing data.

Comprehensive Data Visualization

Comprehensive data visualization is the process of using visual representations to communicate complex data in a way that is easy to understand and interpret. It is a powerful tool that can be used to identify trends, patterns, and relationships in data, and to communicate insights to others.

There are many different data visualization techniques that can be used, and the best approach will depend on the specific data and the audience. Some common data visualization techniques include:

In addition to these basic techniques, there are many other data visualization techniques that can be used to communicate more complex data. For example, treemaps can be used to visualize hierarchical data, and force-directed graphs can be used to visualize network data.

When choosing a data visualization technique, it is important to consider the following factors:

* **The audience:** This visualization was to understand and gain insights from the ml-100k dataset 
* **The data:**
The MovieLens 100K dataset is a collection of 100,000 movie ratings from 943 users on 1,682 movies. The dataset was collected in 1998 and is one of the most popular datasets for evaluating recommender systems.

The dataset contains the following information for each rating:

User ID
Movie ID
Rating (1 to 5 stars)
Timestamp
The dataset also includes a demographics file for each user, which contains the following information:

Age
Gender
Occupation
ZIP code
The MovieLens 100K dataset is a valuable resource for researchers and developers who are working on recommender systems. It can be used to evaluate the performance of different recommender algorithms and to develop new and innovative recommender systems.

Here are some examples of how the MovieLens 100K dataset can be used:

To evaluate the performance of a new recommender algorithm by comparing its predictions to the actual ratings in the dataset.
To develop a recommender system that can recommend movies to users based on their demographics and ratings.
To study the behavior of users and how they rate movies.
To develop a recommender system that can be used to recommend other types of items, such as books, music, or products.
The MovieLens 100K dataset is a freely available dataset that can be downloaded from the GroupLens website.

###Requirements:

Python 3.6+
NumPy
Pandas
Scikit-learn

Python Packages Used

The following Python packages are used in the code:

* **pandas (pd)**: A Python library for data analysis and manipulation.
* **numpy (np)**: A Python library for scientific computing.
* **sklearn.preprocessing.LabelEncoder**: A scikit-learn class for encoding categorical labels into numerical values.
* **sklearn.model_selection.KFold**: A scikit-learn class for implementing k-fold cross-validation.
* **matplotlib.pyplot (plt)**: A Python library for creating and plotting graphs.
* **time**: A Python library for time handling.
* **math**: A Python library for mathematical operations.

These packages are commonly used for machine learning and data science

To use the recommender system:

Clone this repository to your local machine.
Install the required dependencies.
Run the train.py script to train the recommender system on the dataset of movie ratings.
Run the recommend.py script to generate recommendations for a given user.

Conclusion:

This Collaborative Filtering Movie Recommender System is a simple but effective way to generate personalized movie recommendations for users. It can be used to build a recommendation engine for a variety of applications, such as streaming services, social media platforms, and e-commerce websites.
