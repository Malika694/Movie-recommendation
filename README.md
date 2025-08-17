# 🎬 Movie Recommendation System

This project is part of a machine learning , where the goal is to build a **movie recommendation system** using collaborative filtering on the **MovieLens 100K dataset**.

## 📌 Project Overview

* **Objective**: Recommend movies to users based on similarity with other users.
* **Dataset**: [MovieLens 100K](https://grouplens.org/datasets/movielens/100k/)
* **Approach**: Collaborative Filtering
* **Algorithm Used**: Cosine Similarity on User-Item Matrix

## 🛠️ Steps in the Project

1. **Download & Setup Dataset**

   * MovieLens 100K dataset downloaded and unzipped.

2. **Import Libraries**

   * pandas, seaborn, matplotlib
   * scikit-learn (cosine\_similarity)

3. **Load Dataset**

   * Ratings data (`user_id`, `item_id`, `rating`)
   * Movie metadata (`item_id`, `title`)

4. **Data Preprocessing**

   * Merge ratings with movie titles
   * Create **user-movie rating matrix**
   * Fill missing values with 0

5. **Similarity Computation**

   * Compute pairwise cosine similarity between users
   * Construct similarity matrix

6. **Recommendation Engine**

   * For a given user, recommend movies highly rated by similar users
   * Focuses on collaborative filtering approach

## 📊 Results

* The system successfully generates movie recommendations by analyzing user similarities.
* Demonstrates collaborative filtering in action.

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/movie-recommendation-system.git
   cd movie-recommendation-system
   ```

2. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook Task_5_Movie_Recommendation_System_Description.ipynb
   ```

## 📦 Requirements

* Python 3.8+
* pandas
* matplotlib
* seaborn
* scikit-learn

Install them via:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

## 📌 Future Improvements

* Implement **item-based collaborative filtering**.
* Add **content-based filtering** using movie genres.
* Try **hybrid recommendation systems**.
* Use **matrix factorization (SVD, ALS)** for scalability.

