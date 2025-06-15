# 📘 Book Recommendation System using KNN

This project implements a Book Recommendation System using the Book-Crossings dataset and the K-Nearest Neighbors (KNN) algorithm with cosine similarity to recommend books similar to a given one.

## 🚀 Features
- 📚 Recommends similar books based on user ratings  
- 🧠 Uses unsupervised ML (KNN with cosine similarity)  
- ⚡ Handles sparse data efficiently using `csr_matrix`  
- ✅ Passes the freeCodeCamp built-in test case for:  
  `"Where the Heart Is (Oprah's Book Club (Paperback))"`

## 🧰 Tech Stack
| Tool          | Purpose                          |
|---------------|----------------------------------|
| Python        | Programming Language             |
| Pandas        | Data Analysis                    |
| Scikit-learn  | KNN Model                        |
| SciPy         | Sparse Matrix Handling           |
| Google Colab  | Cloud-based Jupyter Notebook     |

## 📂 Dataset
- 📁 Book-Crossings Dataset  
- 📌 Provided via freeCodeCamp

### Files used:
- `BX-Books.csv`  
- `BX-Book-Ratings.csv`  

## 📊 How it works
1. Load & clean data (Books + Ratings)  
2. Merge ratings with books using ISBN  
3. Filter:  
   - Users with ≥ 200 ratings  
   - Books with ≥ 100 ratings  
4. Create a book-user matrix  
5. Convert to sparse matrix  
6. Fit a Nearest Neighbors model using cosine similarity  
7. Recommend top 5 similar books  

## 🔗 Project Link
[📎 Click here to open in Google Colab](https://colab.research.google.com/drive/19q5C5Y97E8wG8IEt4r66ZpfBe2xQYh9m?usp=sharing)
