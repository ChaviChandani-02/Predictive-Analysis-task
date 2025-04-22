# Predictive-Analysis-task

COMPANY- CODTECH IT SOLUTIONS

NAME- CHAVI CHANDANI

INTERN ID- CT04DA482

DOMAIN- DATA ANALYTICS

DURATION- 4 WEEKS

MENTOR- NEELA SANTOSH

# Predictive ANALYSIS USING Machine Learning

# Overview

As part of my internship, I worked on a predictive analysis task using machine learning. The goal was to develop a classification model that can predict whether a Netflix show would appear in the Top 10 weekly rankings. For this, I used a real-world Netflix Dataset containing viewership metrics and other features

The task involved cleaning and preparing the data, performing feature engineering and selection, training a machine learning model, and evaluationg its performance using various metrics.

# Tools and Technologies Used

PYTHON-
Python is a widely used programming language in data science and machine learning. It was used in this task for data handling, visualisation and integration with PySpark. Python's simplicity and vast library support made it perfect for building the analysis workflow

APACHE SPARK(PySpark)-
PySpark is the Python API for Apache Spark, used for fast and distributed processing of large datasets. It enables parallel computation, making it deal for big data tasks across multiple machines. Features like Spark SQL and DataFrames allows easy querying and transformation of structured data.

GOOGLE COLAB-
Google Colab is a free, cloud-based platform to write and run python code in notebooks. It provides access to powerful GUIs and TPUs, which helps process large datasets efficiently. In this task, Colab was used to run PySpark and analyze the Netflix dataset interactively.

CSV( COMMA-SEPARATED VALUES)-
CSV is a common format used to store and share tabular data in plain text. The Netflix dataset was imported as a CSV file into PySpark using spark.read.csv(). It saerves as the input data source for performing cleaning, analysis and modelling

MATPLOTLIB AND SEABORN-
Matplotlib and Seaborn are python libraries used to create rich, visual representation of data. They were used to plot graphs like heatmaps and bar cgarts to highlight key trends. These visualisations made it easier to understand patterns in the Netflix dataset


# Real-World Applications

CONTENT RANKING AND PROMOTION- 
Streaming platforms like Netflix, Amazon Prime, and YouTube can use such models to predict the success or popularity of a show before or after its release

MARKETING STATEGY-
Helps identify which types of shows are likely to succeed and enables data-driven promotion decisions

PERSONALIZED RECOMMENDATIONS-
Predictive models can help recommend trending or high- performing shows to users.

VIEWER RETENTION-
Understanding patterns in successful content can inform what keeps audience engaged

# Key insights

1. The target variable Top10 was highly imbalanced, with the majority of shows not making it to the Top 10
2. Feature engineering(like creating the Top10 label from weekly_rank) played a crucial role in framing the prediction problem efficiently
3. After encoding catergorical variables and training a Random Forect Classifier, the model performed well, achieving a decent accuracy and providing a clear classification report
4. To handle imbalance in the dataset, class weights were incorporated to make the model more sensitive to the monority class.

# Outcomes
1. A fully functional classfication model was developed to predict whether a show would enter the weekly Top 10 list.
2. Model evaluation included accuracy, confusion matrix, and classification metrics such as precision, recall and F1 score
3. The approach highlighted the importance of data preprocessing, feature encoding, and model evaluation in real- worl predictive analysis
4. the final notebook clearly demonstrates the full machine learning pipeline, from raw data to actionable insights.

# Conclusion
This project helped me gain practical experience with-
1. Solving classification problems in real- world scenarios
2. Handling data imbalances and interpreting model performances beyong accuracy
3. Working with end toi end machine learning pipelines

It was a hands- on application of the theory i've learned and gave me a solid foundation to build more advanced ML models in the future





