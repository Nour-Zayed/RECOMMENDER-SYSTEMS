# 📌 Udemy Courses Recommender System
This project aims to build a content-based recommendation system that suggests similar Udemy courses based on a given course title. The system leverages natural language processing (NLP) techniques and cosine similarity to find the most relevant courses based on text data.

# 🧠 Objective
Help learners discover new courses that are similar to ones they’ve already taken or are interested in.

The system takes a course title as input and returns a list of the most similar course titles.

# 🗂️ Dataset
The dataset includes around 3000+ Udemy courses, stored in CSV format.

Key columns used:

title – course title (main focus of similarity)

subject – subject area of the course

price – price of the course

num_subscribers – number of enrolled students

level – course difficulty level

rating – average course rating

# 🔧 Workflow 

Data Cleaning & Preprocessing
Remove missing or duplicate rows
Convert all text to lowercase
Remove stopwords and special characters using neattext
Vectorization
Use CountVectorizer to transform course titles into numerical vectors (Bag-of-Words)
Similarity Calculation
Compute pairwise cosine similarity between all course vectors
د
Recommendation System
Accept a course title from the user
Return the top 10 most similar course titles based on cosine similarity

