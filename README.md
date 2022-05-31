
# Movie Recommendation System
Recommendation system plays important role in Internet world and used in many applications. It is a basic algorithm whose aim is to provide the most relevant information to the users by discovering patterns in a dataset.
This engine makes suggestions by learning and understanding the patterns in your watch history (let’s say) and then applies those patterns and findings to make new suggestions.


## Types of Recommendation System
There are 3 types of recommendation systems.

1) Demographic Filtering: The recommendations are the same for every user. They are generalized, not personalized. These types of systems are behind sections like “Top Trending”.
2) Content-based Filtering: These suggest recommendations based on the item metadata (movie, product, song, etc). Here, the main idea is if a user likes an item, then the user will also like items similar to it.
3) Collaboration-based Filtering: These systems make recommendations by grouping the users with similar interests. For this system, metadata of the item is not required.

.

In this project, we are building a *Content-based recommendation* engine for movies.
## Methodology
For this recommendation system, we have used the KNN algorithm or k-Nearest Neighbour algorithm along with the Cosine-Similarity. And used Streamlit for GUI.

* K-Nearest Neighbour is one of the simplest Machine Learning algorithms based on Supervised Learning technique.This algorithm assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories.

* Cosine similarity measures the similarity between two vectors of an inner product space. It is measured by the cosine of the angle between two vectors and determines whether two vectors are pointing in roughly the same direction.

* Streamlit is an open source app framework in Python language. It helps us create web apps for data science and machine learning.

Using the Cosine function & K-Nearest Neighbor algorithm, we can determine how similar or different two sets of items are and use it to determine the classification.
As all the similar movies will be recommended by the similarity funcion.


## Tools Used
* Jupyter Notebook for Model Training.
* Streamlit(python framework)
* VS Code
* API- https://www.themoviedb.org/
* Dataset- https://www.kaggle.com/
## Working
1. Install the required libraries for this project.
2. The similarity.zip file from this repository should be unzipped so as to find the similarity for the choosen movie.
3. Run the app.py file and use the command- streamlit run app.py in the terminal.
4. It will open a local url on your browser as GUI.
5. Choose your preferred movie from the given dataset and click Recommend Me. This dataset consist of 5000 movies.
6. It will show the recommended movies along with their movie posters.

## Video of working of this project 
To watch the video os working of this project- 
https://www.loom.com/share/efe5bdf24623439198784cc4da369faf
