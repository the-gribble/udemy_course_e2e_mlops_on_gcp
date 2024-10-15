# udemy_course_e2e_mlops_on_gcp
This is my course output of the following Udemy course: https://www.udemy.com/course/machine-learning-ops-on-google-cloud-real-world-data-science

# Course Objectives
 - Help students excel in the machine learning aspect of data science
 - Help prepare you for teh GCP machine learning certification exam

# Sections of this course
 - Introduction to MLOps
 - CI/CD for cloud applications and ML models
 - Continuous training using GCP Composer / Airflow
 - Vertex AI
 - - Model Training
 - - Model Registry
 - - Batch & Online Predictions
 - Kubeflow pipelines for ML workflow orchestratino on Vertex AI
 - Hyperparameter tuning, model versioning, explainability of models, and feature store in Vertex AI
 Generative AI on VerexAI on GCP (brief intro)

# GCP Account
A personal trial GCP account was used to complete this course.

# GCP Used In This Course
 - Python & Docker
 - Cloud Composer
 - Cloud Build
 - Cloud Container/Artifact Registry
 - Gcloud CLI
 - GCS Buckets
 - Cloud Logging/Alerting
 - Cloud Run & Cloud Functions
 - Vertex AI
 - - Model Training services
 - - Model Regitry
 - - Vertex AI End-Points
 - - Experiments
 - - Explainability AI
 - - Hyperparameter Jobs
 - - Feature Store
 - - Kubeflow (Pipelines)

# What is MLOps?
 - Refers to the combination of best practices, principles, and tools for deploying, monitoring, and maintaining machine learning models
 - Seeks to bridge the gap between the development of ML models (typically by data scientists) and their operation in real-world production settings.
 - Aims to streamline development and deployment for machine leaning pipelines and data science models.

# DevOps VS MLOps
## DevOps
 - Primarily focused on code coverage, functionality, and unit tests
 - Focused on deploying and serving application code
 - **Testing:** Primarily focused on code quality and funcitonal testing
 - Software engineering focuses on system performance, error tracking, and log analysis.

 ## MLOps
  - The focus is not only on the code, but also on the data, such as data validation, retraining, model evaluation, automated model artifact deployment, etc.
  - Deals with versioning and managing machine learning models. I.e. Model training code and model inference code.
  - **Testing:** Incorporates continuous data validation techniques such as data validation checks, missing values, and schema validation.
  - ML-Ops tracks model metrics, data quality, and continuous drift detection.

# Why do we need MLOps?
ML code is actually a small part of an ML implementation, or aspect of machine learning. MLOps imvolves several other aspects that are extremely crutial for a data science model to be useful and successful to an organisation. 

This involves:
 - Appropriate infrastructure selection for model training and serving.
 - Data validation
 - Automated pipelines
 - Continuous training
 - Model Versioning
 - Testing & monitoring
 - and more
