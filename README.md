# imdbproject_mlflow_endtoend
# Capstone ML Project: Flask App on AWS EKS with MLFlow & DVC

![Project Status](https://img.shields.io/badge/Status-In_Progress-yellow)

## 🚀 Project Overview

This project demonstrates a full **ML lifecycle pipeline** from local experimentation to cloud deployment using:  

- **MLFlow** for experiment tracking  
- **DVC** for data versioning and reproducible pipelines  
- **Flask** for serving the ML model  
- **Docker** for containerization  
- **AWS EKS** for scalable deployment  
- **CI/CD** with GitHub Actions  

The project is designed for **end-to-end reproducibility**, enabling you to track experiments, version datasets, and deploy models seamlessly.

---

## 🏗 Project Structure

```text
.
├── flask_app/           # Flask app for serving ML model
├── local_s3/            # Temporary local storage for DVC
├── src/                 # Source code
│   ├── data_ingestion.py
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_building.py
│   ├── model_evaluation.py
│   └── register_model.py
├── tests/               # Unit tests and CI scripts
├── scripts/             # Helper scripts
├── dvc.yaml             # DVC pipeline definition
├── params.yaml          # DVC parameters
├── requirements.txt
├── Dockerfile
└── .github/workflows/ci.yaml   # CI/CD workflow

