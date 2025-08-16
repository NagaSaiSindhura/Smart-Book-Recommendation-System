**Overview**

This project implements a scalable and efficient book recommendation system by integrating big data technologies and machine learning models.It leverages Apache Hadoop (HDFS & MapReduce), Apache Spark (PySpark & MLlib), Plotly Dash for visualization, and a Flask-based web application for deployment.

The system supports:

1.Distributed storage and computation for large-scale datasets.

2.Preprocessing, exploratory data analysis, and feature engineering.

3.Machine learning models for collaborative filtering and content-based filtering.

4.Interactive dashboards for insights into user behavior and book trends.

A web-based user interface to deliver personalized book recommendations.

**System Architecture**

HDFS – Fault-tolerant distributed data storage.

MapReduce – Extract insights like top categories, popular authors, and review trends.

Apache Spark – Distributed data processing and MLlib-based recommendation algorithms.

Machine Learning Models –

1.Collaborative Filtering (ALS) – Personalized recommendations using user-item interactions.

2.Content-Based Filtering – Book similarity using MinHashLSH & textual metadata.

3.Plotly Dash – Visualization dashboards for insights.

Flask Web App – User-facing interface for book search, details, and recommendations.

**Dataset**

Source: Amazon Books Reviews Dataset (Kaggle)

Size: ~2.89 GB (3M reviews, 212K books)

Features: Ratings, reviews, categories, authors, publishers, summaries, etc.

**Tech Stack**

**Big Data:** Hadoop, HDFS, MapReduce, Apache Spark (PySpark)

**Machine Learning:** Spark MLlib (ALS, MinHashLSH), Scikit-learn, Pickle (.pkl serialization)

**Visualization:** Plotly, Dash

**Backend:** Python (Flask, Pandas, NumPy, Seaborn, Matplotlib)

**Frontend:** HTML, CSS, Jinja2 templates

**Results**

Collaborative Filtering (ALS) – RMSE ≈ 1.28

Content-Based Filtering – Efficient similarity search with MinHashLSH

Interactive Dashboards – Popular authors, categories, review distributions, word clouds

Flask UI – Seamless book search and personalized recommendations
