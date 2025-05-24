# 📚 Book Recommendation System

A machine learning-based system that recommends books to users based on popularity, user behavior, and content similarity. Built using collaborative filtering, content-based filtering, and hybrid approaches.

🔗 **Dataset Source:** [Book-Crossing Dataset](http://www2.informatik.uni-freiburg.de/~cziegler/BX/)

---

## 🧹 Data Cleaning & Preprocessing

The dataset includes **Books**, **Users**, and **Ratings** tables. Key steps:
- Removed nulls, invalid years, and duplicate entries.
- Standardized ISBN formats and separated user locations into City, State, Country.
- Cleaned and validated ratings using book availability.

---

## 🤖 Recommendation Approaches

### 1. 🔥 Popularity-Based
- Top-rated books overall, by region, author, or year.

### 2. 🧮 Weighted Average Rating
- Combines volume and quality of ratings using:

### 3. 👥 Collaborative Filtering
- User-item similarity using cosine distance.

### 4. 📈 Correlation-Based
- Pearson correlation between user-book ratings.

### 5. 📍 Nearest Neighbors
- Trained using a sparse matrix on user-book ratings.

### 6. 🧠 Content-Based Filtering
- TF-IDF vectorization of book titles (unigrams & bigrams).

### 7. 🔀 Hybrid Model
- Combines collaborative and content-based methods using percentile weighting.

---

## 🛠 Libraries Used

- `pandas`, `numpy`, `scipy`
- `sklearn`
- `matplotlib`, `seaborn`
- Jupyter Notebook / IPython
