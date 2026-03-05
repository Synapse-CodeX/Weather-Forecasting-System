# 🌦 Bakkhali Weather Prediction AI

<div align="center">
  
  ![Python](https://img.shields.io/badge/Python-3.9-blue)
  ![FastAPI](https://img.shields.io/badge/FastAPI-0.104-green)
  ![Streamlit](https://img.shields.io/badge/Streamlit-1.28-red)
  ![Docker](https://img.shields.io/badge/Docker-24.0-blue)
  ![XGBoost](https://img.shields.io/badge/XGBoost-2.0-orange)
  ![License](https://img.shields.io/badge/License-MIT-yellow)
  
  **An end-to-end Multi-Output Time Series Weather Forecasting System for Bakkhali Beach, West Bengal**
  
</div>

---


## ✨ Features

### 🤖 Machine Learning
- **Multi-Output Regression**: Predicts 7 weather parameters simultaneously
- **Algorithm**: Uses XGBoost 
- **Physical Constraints**: Automatically applies real-world rules (e.g., radiation = 0 at night)
- **Auto-Retraining**: Weekly automatic model updates with fresh data

### 🌐 API & Backend
- **RESTful API**: Built with FastAPI, fully documented with Swagger
- **Async Support**: Handles multiple requests efficiently
- **Pydantic Validation**: Request/response validation with detailed schemas
- **Background Tasks**: Non-blocking model training

### 🎨 Frontend
- **Interactive Dashboard**: Built with Streamlit
- **Real-time Predictions**: Get forecasts for any future date/time
- **Visual Analytics**: Interactive charts with Plotly
- **Responsive Design**: Works on desktop and mobile

### 🐳 DevOps
- **Docker Support**: Containerized application
- **Docker Compose**: Orchestrate multiple services
- **Health Checks**: Automatic service monitoring
- **Scalable**: Easy to scale horizontally
