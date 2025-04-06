### END TO END ML PROJECT #####

# 🎯 Student Performance Indicator - End-to-End MLOps Project

This project aims to predict **student performance indicators** using machine learning while implementing an **end-to-end MLOps pipeline** with **CI/CD on AWS**. The pipeline includes all stages from data ingestion and transformation to model training, evaluation, and deployment — following MLOps best practices for automation, reproducibility, and scalability.

---

## 🚀 Objectives

- Build a machine learning model to predict student academic performance.
- Design a modular, automated MLOps pipeline using Python and cloud technologies.
- Integrate CI/CD pipelines for continuous integration and delivery.
- Deploy the model to AWS with containerization and server orchestration.

---

## 🔧 Tech Stack

- **Languages & Tools:** Python, Docker, Git, GitHub Actions
- **Machine Learning:** Pandas, Scikit-learn
- **Cloud & DevOps:** AWS Elastic Beanstalk, CI/CD
- **Version Control & Experiment Tracking:** Git

---

## 🔄 Pipeline Workflow

### 1. Data Ingestion
- Collect raw student performance data from source files.
- Store data and load it into the pipeline.

### 2. Data Transformation
- Clean and preprocess data (handle nulls, encode categorical variables, feature scaling).
- Generate a model-ready dataset.

### 3. Model Training
- Train ML models like Decision Trees, Random Forests, or Logistic Regression.
- Hyperparameters tunning

### 4. Model Evaluation
- Evaluate the model using accuracy, precision, recall, and F1-score.

### 5. Model Packaging
- Save the trained model.
- Package the model using **Docker** for consistent deployment.

### 6. Model Deployment
- Serve the trained model using a **FastAPI** application.
- Deploy the containerized application to **AWS Elastic Beanstalk**.
- Automate the deployment process using **CI/CD pipelines** (e.g., GitHub Actions or AWS CodePipeline).
