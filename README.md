# 🥔 Potato Disease Classifier

A deep learning-based web application to detect diseases in potato leaves using Convolutional Neural Networks (CNN). The model identifies three classes: **Early Blight**, **Late Blight**, and **Healthy**. Built with a TensorFlow/Keras backend, served using FastAPI, and deployed with a React frontend.

---

## 🔍 Features

- ✅ Classifies potato leaf images into:  
  - **Healthy**  
  - **Early Blight**  
  - **Late Blight**
- ✅ Simple web interface to upload and get results
- ✅ Deployed with TensorFlow Serving + FastAPI backend
- ✅ Real-time prediction with confidence score
- ✅ Basic image verification to reject invalid uploads

---

## 🛠 Tech Stack

| Component      | Technology           |
|----------------|----------------------|
| Model          | CNN (TensorFlow/Keras) |
| API Backend    | FastAPI              |
| Model Serving  | TensorFlow Serving   |
| Frontend       | React.js             |
| Deployment     | Docker (optional), Vercel/Render/Fly.io |

---

## 📁 Dataset

- **Source**: [PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)
- Classes used:
  - `Potato___Early_blight`
  - `Potato___Late_blight`
  - `Potato___healthy`

---

## 🚀 Getting Started

### 🔧 Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/yourusername/potato-disease-classifier.git
   cd potato-disease-classifier
