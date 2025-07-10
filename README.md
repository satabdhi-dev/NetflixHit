# 🎬 NetflixHit — Predicting Netflix Hit Titles Using Machine Learning

This project applies machine learning techniques to predict whether a Netflix title will become a **hit** or **non-hit** based on structured metadata such as IMDb rating, vote count, content type, and genres.

## 📌 Objective
To classify Netflix titles as "Hit" or "Non-Hit" using pre-release metadata, helping OTT platforms make better marketing and recommendation decisions.

## 📁 Project Structure
- `notebook/`: Contains the Colab notebook with the entire ML pipeline.
- `images/`: Stores all result visualizations (class distribution, PCA, confusion matrices).
- `data/`: Sample or full dataset used (CSV format).
- `README.md`: Project overview and summary.

## 🛠️ Techniques Used
- Data Cleaning and Feature Engineering
- Genre Parsing & One-Hot Encoding
- PCA for Dimensionality Reduction
- Classification Models:
  - Random Forest
  - Logistic Regression
  - SVM
  - KNN
- Evaluation Metrics:
  - Accuracy, Precision, Recall
  - Confusion Matrix Visualization

## 📊 Results
- Random Forest achieved ~88.9% accuracy.
- SVM had the best recall for identifying hits (~90%).

## 📈 Visuals
<p align="center">
  <img src="images/fig1_dataset_balance.png" width="400"/>
  <img src="images/fig2_pca_variance.png" width="400"/>
</p>

## 🚀 Future Improvements
- Add viewer sentiment or watch-time behavior data
- Explore deep learning methods
- Create an interactive dashboard

## 👩‍💻 Built With
- Python (pandas, scikit-learn, seaborn, matplotlib)
- Jupyter/Colab Notebook

---

**Author:** [Your Name Here]  
_Internship Project | 2025_
