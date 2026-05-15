# Task-2-Muhammad-Rizwan-Babar
📊 Decodelabs Task 2 – Iris Classification using KNN
This project is part of the Decodelabs AI/ML tasks submission.
It demonstrates a complete Machine Learning workflow using the famous Iris dataset, applying the K-Nearest Neighbors (KNN) classification algorithm to predict flower species.

🎯 Objective

To build a machine learning model that:

Loads and explores the Iris dataset
Splits data into training and testing sets
Trains a KNN classifier
Makes predictions
Evaluates model performance
Visualizes data
📂 Dataset Information

The Iris dataset contains 150 samples with 4 features:

Sepal Length (cm)
Sepal Width (cm)
Petal Length (cm)
Petal Width (cm)
🌸 Target Classes:
Setosa
Versicolor
Virginica
⚙️ Technologies Used
Python 🐍
Pandas
NumPy
Matplotlib
Scikit-learn (sklearn)
🧠 Machine Learning Model

We used:

KNeighborsClassifier (KNN)

KNN is a simple and powerful supervised learning algorithm that classifies data based on nearest neighbors.

🚀 Project Workflow
1️⃣ Import Libraries

Used essential ML and data science libraries.

2️⃣ Load Dataset
from sklearn.datasets import load_iris
3️⃣ Explore Data

Checked:

Feature names
Target labels
Dataset shape
4️⃣ Train-Test Split

Split data into:

Training set: 120 samples
Testing set: 30 samples
5️⃣ Model Training

Trained KNN classifier on training data.

6️⃣ Predictions

Model predicts flower classes on test data.

7️⃣ Evaluation

Model performance:

Accuracy: 100%
Confusion Matrix
Classification Report
📊 Results
✅ Accuracy
1.0 (100%)
📌 Confusion Matrix
[[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]
📌 Classification Report

All classes achieved perfect precision, recall, and F1-score.

📈 Visualization

The dataset is visualized using a scatter plot:

X-axis → Sepal Length
Y-axis → Sepal Width
Color → Flower Class

This helps understand data distribution visually.

📁 Project Structure
decodelabs_tasks/
│
├── task2_iris_classification/
│   ├── Decode Lab Task 2.ipynb
│   ├── README.md
│
└── task1/
▶️ How to Run This Project
Step 1: Install dependencies
pip install pandas numpy matplotlib scikit-learn
Step 2: Run Jupyter Notebook
jupyter notebook
Step 3: Open file
Decode Lab Task 2.ipynb
👨‍💻 Author

Rizwan Babar
