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
- **Machine Learning:** Pandas, Scikit-learn, MLflow
- **API & Serving:** FastAPI, Uvicorn
- **Cloud & DevOps:** AWS (S3, EC2, ECR, CodePipeline, CodeBuild), CI/CD
- **Version Control & Experiment Tracking:** Git, MLflow (optional: DVC for data versioning)

---

## 🔄 Pipeline Workflow

### 1. Data Ingestion
- Collect raw student performance data from source files.
- Store data in an **S3 bucket** and load into pipeline.

### 2. Data Transformation
- Clean and preprocess data (handle nulls, encode categorical variables, feature scaling).
- Generate a model-ready dataset.

### 3. Model Training
- Train ML models like Decision Tree, Random Forest, or Logistic Regression.
- Track hyperparameters and performance metrics using MLflow.

### 4. Model Evaluation
- Evaluate the model using accuracy, precision, recall, F1-score.

### 5. Model Packaging
- Save the trained model.
- Package the model using **Docker** for consistent deployment.

### 6. Model Deployment
- Serve the model using **FastAPI** on an **AWS EC2 instance**.
- Deploy via **AWS CodePipeline + CodeBuild** for CI/CD.

---

## 📁 Project Structure
