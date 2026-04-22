# COVID-19 Data Analysis and Machine Learning Project

## 🎯 Overview
This project provides a comprehensive analysis of global COVID-19 trends. It covers the full lifecycle of a data project: from data ingestion and cleaning to summary statistics, interactive visualizations, and predictive machine learning models.

## 🚀 Features
* **Data Loading:** Efficiently handles `covid_19.csv` with flexible options for Colab environment or local storage.
* **Summary Statistics (Part A):** Generates tabular summaries of total cases, deaths, and population by continent.
* **Interactive Visualizations (Part B):** Creates distinct, color-consistent pie charts visualizing the global distribution of health metrics.
* **Machine Learning (Part C):** Implements a classification task to predict **high_fatality** status.
    * **Target Variable:** `high_fatality` (Case Fatality Rate above training-set median).
    * **Features:** Population, Cases, Recovered, Tests, Recovery Rate, and more.
    * **Models:** Benchmarking of Logistic Regression vs. HistGradientBoosting (Random Forest) classifiers.

## 📊 Evaluation & Results
The project provides full performance metrics, including Accuracy, F1-scores, and Classification Reports.
* **Visual Validation:** Includes Confusion Matrices to identify model bias and classification accuracy.

![Confusion Matrix Comparison]("CONFUSIONMATRIX.PNG")

## 📖 How to Use
1. **Upload to Colab:** Open the `.ipynb` file in Google Colab (**File → Upload notebook**).
2. **Data Preparation:** Ensure `covid_19.csv` is available in the `/content/` directory.
3. **Run All Cells:** Go to **Runtime → Run all** to execute the analysis and generate reports.

## 📂 Project Structure
* **Setup:** Library imports and environment configuration.
* **Part A (Load Data):** Initial ingestion and handling of `covid_19.csv`.
* **Part B (Summary):** Aggregation of statistics (Exports `continent_covid_summary.csv`).
* **Part C (Visuals):** Generation of geospatial pie charts (Exports `continent_pie_charts.png`).
* **Part D (ML):** Feature engineering, training, and confusion matrix visualization.

## 🛠 Technologies Used
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-learn
* **Visualizations:** Matplotlib, Seaborn
* **Strategic Frameworks:** ADKAR Change Management, Kotter’s 8-Step Model
