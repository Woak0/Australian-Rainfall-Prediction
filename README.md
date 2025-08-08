# Australian Rainfall Prediction

# Predicting Rainfall in Australia: An End-to-End Machine Learning Project

This repository documents a comprehensive data science project focused on predicting whether it will rain the next day in Australia. The project follows a complete workflow from initial data exploration and preprocessing to building, evaluating, and selecting the best classification model.

### Project Objective
To develop a high-performing machine learning model capable of accurately predicting `RainTomorrow` based on a range of daily weather observations. This project was completed as part of a university data mining course and involved competing on a private Kaggle leaderboard.

### Key Skills & Technologies
- **Data Analysis & Preprocessing:** Python (Pandas, NumPy), KNIME, Exploratory Data Analysis (EDA), Binning, Normalization (Min-Max, Z-Score), Discretization, Binarization.
- **Machine Learning:** Scikit-learn, Classification, Model Evaluation, Hyperparameter Tuning.
- **Models Implemented:** Decision Tree, k-Nearest Neighbors (KNN), Random Forest, Support Vector Machine (SVM), Neural Networks.
- **Tools:** Jupyter Notebook, Git, GitHub, Kaggle.

---

### Project Structure & Workflow

This project is divided into two main phases, mirroring a real-world analytical process:

**Phase 1: Data Exploration & Preprocessing (`/01_Data_Exploration_and_Preprocessing`)**
This initial phase focused on understanding the dataset's structure, characteristics, and quality. Key tasks included:
- **Initial Data Exploration:** Identifying attribute types, calculating summary statistics (mean, median, variance), and visualizing distributions to understand the data's landscape.
- **Data Quality Assessment:** Using tools like KNIME and Python to identify outliers and interesting data clusters.
- **Rigorous Preprocessing:** Applying a suite of techniques to prepare the data for modeling, including equi-width/equi-depth binning on `Rainfall` and min-max/z-score normalization on `MaxTemp`.

**Phase 2: Predictive Modeling & Kaggle Competition (`/02_Predictive_Modeling`)**
Building on the cleaned data, this phase focused on developing and selecting the best classification model.
- **Model Development:** Trained and evaluated five different classification algorithms (Decision Tree, KNN, Random Forest, SVM, and Neural Networks).
- **Hyperparameter Tuning & Model Selection:** Systematically tested different model parameters and used cross-validation to select the most robust and accurate model.
- **Final Prediction:** Applied the final, optimized model to the `UnknownData.csv` dataset to generate predictions.
- **Kaggle Competition:** Submitted the predictions to a private Kaggle competition, achieving a final score of [Your Score, e.g., 0.865 accuracy].

---

### How to Navigate This Repository
- **Final Report:** For a complete narrative of the methodology, findings, and model performance, please see the PDF in the `/report` directory.
- **Python/KNIME Workflows:** The code and workflows for each phase are located in their respective numbered folders.
- **Data:** The datasets used for training and prediction are in the `/data` folder.

---

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.