# 🎬 Collaborative Filtering with MovieLens Dataset

This Jupyter Notebook demonstrates a collaborative filtering-based movie recommendation system using the MovieLens dataset. The goal is to recommend movies to users based on their past ratings and similarities with other users.

## 🚀 How to Run

1. Clone this repository or download the files.
2. Make sure you have the required libraries installed:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Collaborative_Filtering.ipynb
   ```

## 📊 Dataset

This notebook uses the [MovieLens 30M dataset](https://grouplens.org/datasets/movielens/). It includes:
- `ratings.csv`: User ID, Movie ID, Rating, Timestamp
- `movies.csv`: Movie ID, Title, Genres

## 🧠 Techniques Used

- **User-User Collaborative Filtering** with Cosine Similarity
- **Pivot Tables** to create user-item matrices
- **Sparsity Handling** by filtering active users and popular movies
- **Top-N Recommendation Generation**

## 🖼️ Visualization

The notebook also includes:
- Rating distribution plots
- Similarity matrix

## 🧪 Example Output

![image](https://github.com/user-attachments/assets/ccf731a3-c1d0-4f25-bbb5-dcfcaa934c60)


## 📌 Notes

- This notebook does not use external recommendation libraries like Surprise or LightFM.
- The focus is on understanding core concepts behind collaborative filtering.
