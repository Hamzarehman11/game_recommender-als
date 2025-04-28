<!-- BDTT Assignment Task-2: ALS Recommender System -->
This project implements a collaborative filtering recommender system using the Alternating Least Squares (ALS) algorithm with Spark MLlib on Databricks.
The model is evaluated using Root Mean Squared Error (RMSE).

The project was developed as part of a Big Data Tools & Techniques (BDTT) assignment using the Steam-200k dataset.

<!-- Project Highlights -->
Environment: Databricks (Community Edition)

<!-- Technologies Used: -->

PySpark

Spark MLlib

Databricks

MLflow (experiment tracking)

Machine Learning Model: ALS (Alternating Least Squares)

Evaluation Metric: RMSE (Root Mean Squared Error)

Dataset: Steam-200k dataset (user interactions with games)

Folder Contents
recommender.html — Full Databricks notebook exported as HTML, containing:

Data ingestion and preprocessing

ALS model building

Model evaluation (RMSE calculation)

Top-N recommendation generation

MLflow experiment tracking

How to View
Simply download or open the recommender.html file in a browser to view the complete project notebook with all code, outputs, and documentation.

Key Sections
Data Loading: Imported and preprocessed Steam-200k data.

Data Processing: Converted categorical fields, handled missing values, generated numerical indices.

Model Training: Built an ALS model using PySpark's MLlib.

Model Evaluation: Evaluated model performance using RMSE.

Recommendations: Generated top-N recommendations for users.

How to Run (if you want to reproduce)
Create a cluster in Databricks (Python 3, Spark 3.x).

Import the notebook into Databricks (if you export it from HTML to .ipynb).

Attach to the cluster and run cells sequentially.


