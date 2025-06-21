# Book Recommendation System (Unsupervised Learning)

For this project I build a book recommendation system ysing unsupervised machine learning techniques. This project was developed in **Python** using **Google Colab**.  I will be submitting this project for my **Machine Learning Fundamentals** course at Miami Dade College as part of my A.S. in Applied AI. 

## Overview

This system will recommend books to used by finding and analyzing similarities in user ratings.  It uses **cosine similarity** and a **user-item matrix** to predict which books a user might like based on the preferences of similar users.

## 🎯 Purpose

This project demonstrates my ability to design and implement recommendation algorithms, specifically using collaborative filtering and unsupervised machine learning techniques. It showcases my skills in data preprocessing, similarity computation, and delivering personalized recommendations based on user behavior.

## Files Required

To run the project, you'll need the following CSV files:

- `Books.csv` (available in repo via zip)
- `Users.csv`
- `Ratings.csv`

## How to Run

1. Open Python notebook file in **Google Colab**.
2. Upload the three CSV files listed above using the file upload panel in Colab.
3. Run all cells in sequence.

The notebook will:
- Clean and preprocess the data
- Build a user-book rating matrix
- Calculate cosine similarity between users
- Generate book recommendations for a selected user

The user we were tasked to find recommendations for at the end of the notebook intitally has zero book recommendations since there was very little data on them. They had only reviewed one took at the time of recommendation.  I made sure to fix this by writing the code that will force to system to fallback to displaying the most popular books within the dataset. So everyone gets a recommendation!

## 🛠 Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Surprise)
- Google Colab
- Unsupervised Learning
  - Cosine Similarity
  - Collaborative Filtering

## 👩‍💻 Author

**Ryanne Milligan**  

---

