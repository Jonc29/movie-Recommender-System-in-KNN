# 🎬 Movie Recommender System (KNN)

A simple **Movie Recommender System** built using the **K-Nearest Neighbors (KNN)** algorithm in Python.  
It suggests movies based on similarity in features, helping users discover new titles related to their favorites.  

---

## 📌 Features
-  Recommends similar movies based on a selected title  
-  Uses **KNN algorithm** for finding nearest neighbors  
-  Works entirely offline with a prepared dataset  
-  Implemented in **Jupyter Notebook** for easy experimentation  
-  Beginner-friendly Python code  

---

## 📂 Project Structure
movie-recommender-system/
│
├── Movie_Recommender_KNN.ipynb # Main Jupyter Notebook
├── movies.csv # Dataset file
├── requirements.txt # Dependencies
└── README.md # Project description

---


---

##  Installation & Setup
1. **Clone this repository**:
git clone https://github.com/yourusername/movie-recommender-system.git
cd movie-recommender-system

#### Open Jupyter Notebook:
jupyter notebook

#### Run the notebook:
Open Movie_Recommender_KNN.ipynb and run the cells in order.

## How It Works

The dataset is loaded and preprocessed.

Movie features are converted into numerical vectors.

KNN algorithm finds the closest movies to the selected one.

Top N similar movies are displayed as recommendations.

## Example Output

Input: "The Dark Knight"
Output:

1. Batman Begins  
2. The Dark Knight Rises  
3. Inception  
4. Interstellar  
5. Man of Steel  

## Technologies Used

##### Python

Pandas & NumPy
matplotlib
seaborn
scipy
scipy
fuzzywuzzy
sklearn

model = NearestNeighbors(n_neighbors = 20,
                                 metric = 'cosine',
                                 algorithm = 'brute')
PCA
StandardScaler

Jupyter Notebook

📜 License

This project is open-source and available under the MIT License.


If you want, I can also give you a **requirements.txt** file for your project so it installs perfectly when others clone it. That will make your GitHub repo more professional.
