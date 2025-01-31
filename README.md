📝 Handwriting Data to Detect Alzheimer's Disease
📌 Project Overview
This project explores the use of handwriting data to detect Alzheimer’s disease using machine learning techniques. By analyzing various handwriting features such as pressure, speed, and stroke characteristics, the model classifies individuals as either Alzheimer’s patients or healthy.

📂 Dataset
Source: The DARWIN dataset, publicly available on the UCI Machine Learning Repository.
Total Participants: 2,174 individuals.
Features: 452 handwriting-related attributes (e.g., speed, pressure, strokes, acceleration, and time duration).
Label: Binary classification (Healthy or Alzheimer’s patient).
🎯 Objectives
Develop a machine learning model to classify individuals based on handwriting analysis.
Improve early Alzheimer’s detection through handwriting-based cognitive assessment.
Potentially integrate the model into a mobile or web-based application for real-world screening.
🏗️ Project Workflow
Preprocessing & Data Cleaning

Handling missing values using KNN/MICE imputation.
Detecting & removing outliers using Z-score, IQR, Isolation Forest.
Feature extraction (e.g., velocity, pressure variability, entropy).
Scaling & normalization using Min-Max Scaling & Standardization.
Exploratory Data Analysis (EDA)

Correlation Matrix: Understand feature relationships.
Boxplots & Violin Plots: Identify data spread and outliers.
t-SNE/UMAP Visualization: Cluster Alzheimer’s vs. healthy individuals.
SHAP/LIME: Interpret model predictions.
Machine Learning Models

Supervised Learning: Logistic Regression, SVM, Decision Trees, Random Forest, Gradient Boosting (XGBoost), KNN, Neural Networks.
Unsupervised Learning: K-Means Clustering, PCA, Hierarchical Clustering.
Time-Series Analysis: Recurrent Neural Networks (RNN).
Anomaly Detection: Isolation Forests, Autoencoders.
📊 Results & Findings
Models were evaluated using accuracy, precision, recall, and F1-score.
Feature importance analysis showed pressure, stroke speed, and acceleration as key indicators.
Advanced methods like Graph Neural Networks and Contrastive Learning improved classification performance.
🚀 Future Enhancements
Deploy the model in a real-time application (mobile/web).
Collect more real-world handwriting samples for better generalization.
Explore deep learning architectures for improved accuracy.
🛠️ Setup & Installation
bash
Copy
Edit
# Clone the repository
git clone https://github.com/your-username/Handwriting-Alzheimers-Detection.git
cd Handwriting-Alzheimers-Detection

# Install dependencies
pip install -r requirements.txt

# Run the model
python main.py
📜 Citation
If you use this dataset or code in your research, please cite Francesco Fontanella (DARWIN dataset).
