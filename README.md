# Netflix Movies and TV Shows Analysis & Machine Learning

## 📌 Project Overview

This project explores Netflix Movies and TV Shows using Python, data visualization, and Machine Learning. It was developed in two stages as part of the Codomax Digital Internship.

- **Module 05:** Exploratory Data Analysis (EDA)
- **Module 06:** Machine Learning — Netflix content rating prediction

## 🎯 Objectives

- Analyze Movies and TV Shows on Netflix.
- Explore release-year trends, genres, ratings, and countries.
- Clean and prepare the dataset.
- Build a Random Forest classification model to predict content ratings.
- Evaluate model performance using accuracy, a classification report, and a confusion matrix.

## 🛠️ Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Google Colab
- GitHub

## 📂 Dataset

**Netflix Movies and TV Shows**

Source: [Kaggle Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

The dataset contains details such as title, type, release year, rating, duration, country, and genres.

## 📊 Module 05 — Exploratory Data Analysis

The analysis includes:

- Movies vs. TV Shows comparison
- Release-year trends
- Top genres
- Content rating distribution
- Country-wise content analysis

## 🤖 Module 06 — Machine Learning

A Random Forest classifier was trained to predict content rating using content type, release year, duration, and genre.

### Workflow

1. Prepare the dataset and select features.
2. Group rare rating categories to support stratified splitting.
3. Encode categorical features and scale the numerical feature.
4. Split the data into training and testing sets.
5. Train the Random Forest classifier.
6. Evaluate predictions using accuracy, a classification report, and a confusion matrix.
7. Test the model with a sample input.

### Initial Model Result

- **Model:** Random Forest Classifier
- **Test accuracy:** 46.68%
- **Sample prediction:** TV-MA for a sample movie input

The accuracy is a baseline result, not proof of strong predictive performance. Further improvements and comparison with simpler models may be useful.

## 📁 Project Notebooks

- **Module 05 — EDA:** `Codomax_Module_05_Netflix_Data_Analysis.ipynb`
- **Module 06 — Machine Learning:** `Codomax_Module_06_Netflix_ML_Project.ipynb`

## ▶️ How to Run

1. Download the required notebook from this repository.
2. Download `netflix_titles.csv` from the Kaggle dataset linked above.
3. Open the notebook in Google Colab.
4. Upload the CSV file and update its file path if necessary.
5. Run the cells in order.

## 📚 Learning Outcomes

- Data cleaning and preprocessing
- Exploratory Data Analysis
- Data visualization
- Feature encoding and preprocessing pipelines
- Classification with Scikit-learn
- Model evaluation and interpretation

## 🏁 Conclusion

This project combines exploratory data analysis with a baseline Machine Learning model to investigate Netflix content. It provided hands-on practice in Python, visualization, data preparation, classification, and model evaluation.

**Completed as part of the Codomax Digital Internship — Modules 05 and 06.**
