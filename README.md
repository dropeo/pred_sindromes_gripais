🦠 Flu Syndrome Prediction — pred_sindromes_gripais
A machine learning project to predict flu syndrome occurrences in Brazil using a Support Vector Regression (SVR) model, built with Python and Jupyter Notebook.

📌 Overview
Flu syndromes (síndromes gripais) are a recurring public health concern in Brazil, with seasonal spikes that strain health systems. This project uses historical epidemiological data from OpenDataSUS to predict future case counts using supervised machine learning.

🧠 Model & Results
MetricValueAlgorithmSupport Vector Regression (SVR)Score0.7208R²0.7208Mean Absolute Error0.4466RMSE0.5284
The SVR model achieved an R² of 0.72, meaning it explains ~72% of the variance in flu syndrome case counts — a solid result for epidemiological time-series prediction.

📁 Project Structure
pred_sindromes_gripais/
└── Pred. Sindromes Gripais/
    └── pred_sindromes_gripais.ipynb   # Data loading, preprocessing, model training and evaluation

🚀 Getting Started
Prerequisites
bashpip install pandas numpy scikit-learn matplotlib jupyter
Run
bashjupyter notebook "Pred. Sindromes Gripais/pred_sindromes_gripais.ipynb"

📊 Data

Source: OpenDataSUS — Brazilian Ministry of Health open epidemiological data
Target: Flu syndrome (síndrome gripal) case notifications


🛠 Tech Stack
ToolPurposePythonCore languagescikit-learnSVR model + metricspandasData manipulationmatplotlibVisualizationJupyter NotebookDevelopment environment

👤 Author
me.
