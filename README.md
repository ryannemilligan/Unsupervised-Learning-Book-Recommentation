# 📚 Book Recommendation System (Unsupervised Learning)

This is a collaborative filtering–based book recommendation system built using unsupervised machine learning techniques. The project was developed in **Python** using **Google Colab** as part of the **Machine Learning Fundamentals** course at *Miami Dade College*.

## 🧠 Overview

The system recommends books to users by analyzing similarities in user ratings. It uses **cosine similarity** and a **user-item matrix** to predict which books a user might like based on the preferences of similar users.

## 📂 Files Required

To run the project, you'll need the following CSV files:

- `Books.csv`
- `Users.csv`
- `Ratings.csv`

These files contain metadata about books, user IDs, and user ratings.

## 🚀 How to Run

1. Open the Python notebook in **Google Colab**.
2. Upload the three CSV files listed above using the file upload panel in Colab.
3. Run all cells in sequence.

The notebook will:
- Clean and preprocess the data
- Build a user-book rating matrix
- Calculate cosine similarity between users
- Generate book recommendations for a selected user

If no personalized recommendations can be made (e.g., the user has only rated one book), the system will fallback to displaying the most popular books.

## 🛠 Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Surprise)
- Google Colab
- Unsupervised Learning
  - Cosine Similarity
  - Collaborative Filtering

## 🎯 Purpose

This project demonstrates my ability to design and implement recommendation algorithms, specifically using collaborative filtering and unsupervised machine learning techniques. It showcases my skills in data preprocessing, similarity computation, and delivering personalized recommendations based on user behavior.

## 📝 Notes

- This is a small-scale system built for educational purposes and may not scale well to large production environments.
- The dataset used was pre-cleaned and limited in size for academic use.

## 📈 Future Improvements

- Integrate a content-based filtering hybrid
- Visualize similarity matrices and user clusters
- Use matrix factorization (e.g., SVD) for deeper collaborative insights

## 👩‍💻 Author

**Ryanne Milligan**  

---

