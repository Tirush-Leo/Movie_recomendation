# 🎬 Movie Recommendation System  

This project is a **content-based movie recommendation system** built using **Python** and **Machine Learning** techniques. It recommends movies similar to a user’s input movie by analyzing textual features such as genres, keywords, cast, and crew.  

## 🚀 Features  
- Content-based filtering using **TF-IDF Vectorization**  
- **Cosine Similarity** to compute movie similarity scores  
- User-friendly input: Enter any movie name and get recommendations  
- Works with a dataset of movies (CSV format)  

## 🛠️ Technologies Used  
- **Python 3**  
- **Pandas, NumPy** – Data handling  
- **Scikit-learn** – TF-IDF Vectorizer, Cosine Similarity  
- **Difflib** – Handling close matches in user input  

## 📂 Dataset  
The system uses a **movies dataset (`movies.csv`)** containing metadata such as:  
- Movie titles  
- Genres  
- Keywords  
- Cast & Crew information  

*(You can replace or extend the dataset with your own for better results.)*  

## ⚙️ How It Works  
1. Load and preprocess the dataset  
2. Convert text features into **TF-IDF vectors**  
3. Calculate similarity between all movies using **Cosine Similarity**  
4. Take user input (movie name)  
5. Recommend top N most similar movies  

## ▶️ Usage  
Clone the repository:  
```bash
git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system
```

Install dependencies:  
```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook or Python script:  
```bash
jupyter notebook Project_18_Movie_Recommendation_System_using_Machine_Learning_with_Python.ipynb
```

Example input/output:  
```
Enter your favorite movie: Avatar  
Recommended Movies:  
1. John Carter  
2. Guardians of the Galaxy  
3. Star Trek  
4. The Avengers  
5. The Matrix  
```

## 📊 Future Enhancements  
- Add a **hybrid recommendation system** (content + collaborative filtering)  
- Build a **web app** using Flask/Django/Streamlit  
- Deploy model with **Heroku/Render/Streamlit Cloud**  
