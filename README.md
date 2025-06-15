📘 Book Recommendation System using KNN
This project implements a Book Recommendation System using the Book-Crossings dataset and the K-Nearest Neighbors (KNN) algorithm with cosine similarity to recommend books similar to a given one.

🚀 Features:-
📚 Recommends similar books based on user ratings.
🧠 Uses unsupervised ML (KNN with cosine similarity).
⚡ Handles sparse data efficiently using csr_matrix.
✅ Passes the freeCodeCamp built-in test case for:
  "Where the Heart Is (Oprah's Book Club (Paperback))"

🧰 Tech Stack:-
Tool	Purpose
Python	Programming Language
Pandas	Data Analysis
Scikit-learn	KNN Model
SciPy	Sparse Matrix Handling
Google Colab	Cloud-based Jupyter Notebook

📂 Dataset:-
Book-Crossings Dataset
Provided via freeCodeCamp.

Files used:-
BX-Books.csv
BX-Book-Ratings.csv

📊 How it works:-
Load & Clean Data (Books + Ratings)
Merge ratings with books using ISBN
Filter:
  Users with ≥ 200 ratings
  Books with ≥ 100 ratings
Create a book-user matrix
Convert to sparse matrix
Fit a Nearest Neighbors model using cosine similarity
Recommend top 5 similar books

🔗 FCC Project Link:-https://colab.research.google.com/github/freeCodeCamp/boilerplate-book-recommendation-engine/blob/master/fcc_book_recommendation_knn.ipynb
