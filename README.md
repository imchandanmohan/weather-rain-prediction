# 🌧️ Weather Rain Prediction using CI/CD and Kubernetes

This project implements a machine learning pipeline to predict whether it will rain tomorrow in different parts of Australia. It includes data preprocessing, model training, a Flask-based web application, and CI/CD automation using GitHub Actions, CircleCI, and GitLab CI/CD. The final app is containerized with Docker and deployed on Kubernetes via Google Cloud.

---

## 📌 Objective

To build and deploy an ML model that forecasts rain based on historical Australian weather data. The solution aims to assist weather forecasting departments by automating prediction and deployment workflows using DevOps tools.

---

## 🧰 Tech Stack

- **Language:** Python  
- **ML Libraries:** Pandas, Scikit-learn, NumPy  
- **App Framework:** Flask  
- **AI Integration:** ChatGPT (via OpenAI API)  
- **CI/CD Tools:** GitHub Actions, CircleCI, GitLab CI/CD  
- **Cloud & Containerization:** Docker, Kubernetes, Google Cloud  
- **Version Control:** GitHub  

---

## 📁 Project Structure

```bash
.
├── artifacts/                         # Trained models and outputs
├── notebook/
│   └── notebook.ipynb                 # EDA, preprocessing, training
├── pipeline/                          # Pipeline automation scripts
├── src/                               # Core ML logic and utilities
├── static/                            # CSS, JS for the web interface
├── templates/                         # HTML templates for Flask
├── application.py                     # Flask app entry point
├── Dockerfile                         # Docker container configuration
├── kubernetes-deployment.yaml        # Kubernetes deployment manifest
├── requirements.txt                   # Python dependencies
├── setup.py                           # Packaging config
└── README.md                          # Project documentation
