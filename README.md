# 🌸 Iris Flower Classification

This project uses the **Iris Flower Dataset** to build a machine learning model that classifies iris flowers into three species:  
- *Iris-setosa*  
- *Iris-versicolor*  
- *Iris-virginica*

The classification is based on four features:
1. Sepal Length
2. Sepal Width
3. Petal Length
4. Petal Width

---

## 📂 Dataset
The dataset used is **`IRIS_01.csv`**, which contains:
- 150 rows (samples)
- 5 columns (4 features + 1 target `species`)

It is a clean and well-known dataset often used for beginner-level ML tasks.

---

## 🛠️ Requirements
Make sure you have Python 3.x installed and the following libraries:

```bash
pip install pandas matplotlib seaborn scikit-learn

🚀 How to Run

Clone this repository or download the project files.

Place the dataset file IRIS_01.csv in the same directory as the notebook.

Open the Jupyter Notebook:

jupyter notebook IRIS FLOWER CLASSIFICATION.ipynb


Run the cells step-by-step to:

Load and explore the dataset

Visualize the features

Train and test the model

Evaluate model performance

📊 Project Workflow

Data Loading & Exploration

View sample rows, dataset info, and statistical summary.

Data Visualization

Pairplot of features colored by species

Correlation heatmap

Boxplots of each feature by species

Data Preprocessing

Encode target labels (species)

Split dataset into training (80%) and testing (20%) sets

Model Training

Random Forest Classifier

Model Evaluation

Accuracy score

Classification report (Precision, Recall, F1-score)

Confusion matrix

📈 Model Performance

Using a Random Forest Classifier:

Accuracy: ~100% (varies slightly due to random splits)

Excellent classification for all three species.

📷 Visualizations

Pairplot: Shows how features separate the species

Heatmap: Displays correlation between features

Boxplots: Shows feature distribution for each species

📌 Future Improvements

Try other models (Logistic Regression, SVM, KNN)

Deploy the model as a web app using Streamlit or Flask

Add functionality for user input to classify custom flower measurements

📜 License

This project is open-source and free to use for educational purposes.

👩‍💻 Author

Muskan Trivedi