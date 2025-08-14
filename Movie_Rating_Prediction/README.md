# 🎬 Movie Rating Prediction with Python

## 📌 Project Overview
This project predicts the **IMDb rating** of a movie based on features such as **genre, director, and actors** using machine learning regression techniques.  
We analyze historical movie data, perform preprocessing & feature engineering, and build models to estimate movie ratings.

## 📂 Dataset
- **Name:** IMDb Movies India
- **Columns:**
  - `Name` — Movie title
  - `Year` — Release year
  - `Duration` — Movie duration
  - `Genre` — Movie genres
  - `Rating` — IMDb rating (target)
  - `Votes` — Number of votes
  - `Director` — Director name
  - `Actor 1`, `Actor 2`, `Actor 3` — Lead actors

> **Note:** The dataset is encoded in `latin1` due to special characters.

## ⚙️ Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Jupyter Notebook**
- **Machine Learning Models:**
  - Random Forest Regressor
  - Ridge Regression

## 📊 Workflow
1. **Data Loading & Cleaning**
   - Handle special encoding (`latin1`)
   - Extract numeric year from text
   - Convert duration to minutes
   - Combine cast & director info into a single feature
   - Clean and split genres

2. **Exploratory Data Analysis (EDA)**
   - Rating distribution
   - Votes vs rating
   - Most common genres

3. **Feature Engineering**
   - TF-IDF for cast/director names
   - CountVectorizer for genres
   - Scaling for numeric features

4. **Model Building**
   - Random Forest Regressor (baseline)
   - Ridge Regression (comparison)
   - Cross-validation

5. **Evaluation Metrics**
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Squared Error)
   - R² Score

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/movie-rating-prediction.git
   cd movie-rating-prediction

Run the Jupyter Notebook:
jupyter notebook movie_rating_prediction.ipynb

📈 Results
Random Forest provided better performance compared to Ridge Regression.

Top features affecting ratings include:

Certain popular directors & actors

High vote counts

Specific genres (Drama, Action, Romance)

📌 Next Steps
Hyperparameter tuning with GridSearchCV

Add more features like budget, language, country

Try deep learning models for text features

📜 License
This project is open-source under the MIT License.
