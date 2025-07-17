# 🌿 Cottonsage SoilSavvy AgroEye – Frontend (React.js)

This is the **React.js frontend** of the full-stack AI-powered agriculture project: **Cottonsage SoilSavvy AgroEye**. It allows farmers to upload images of their crops and receive real-time disease predictions along with actionable treatment recommendations.

---

## 🔁 Navigation – Other Parts of This Project

This project is divided into 3 components:

| Folder | Description |
|--------|-------------|
| [`../backend/`](https://github.com/akshaykathwate/CattonSage_Backend) | Spring Boot backend – handles image requests, communicates with the model API, and maps prediction to recommendations |
| [`../model-api/`](https://github.com/akshaykathwate/Model) | Flask API that serves the trained AI models (MobileNet, ResNet) for crop disease classification |
| `frontend/` | 🌱 React-based frontend – You are here. Upload image → Get result → View treatment suggestions -> generate disease report |

---

## 🚀 Project Overview & Features

Cottonsage AgroEye helps farmers detect crop diseases (focused on cotton) by analyzing images and offering guidance. This frontend interface makes it easy for users to interact with the system.

### ✅ Core Features

- 📸 Upload cotton plant/leaf image
- ⚙️ Send image to backend via REST API
- 📊 Show:
  - ✅ Disease name
  - 🔬 Confidence score
  - 💊 Treatment recommendation (chemical & organic)
- 🖥️ Clean, mobile-responsive UI
- ⚠️ Error handling with user alerts

### 🎯 Advanced Features

- ⏳ **Spinner/Loader** while prediction is being processed
- 🖱️ **Drag-and-drop image upload**
- 📄 **Export prediction result as PDF**
- 📱 **Responsive mobile experience** using Tailwind CSS

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **React.js** | Component-based frontend |
| **Redux Toolkit** | State Management Tool |
| **Tailwind CSS** | Utility-first responsive styling |
| **Axios** | API communication |
| **JavaScript (ES6)** | Logic and state management |
| **jsPDF** | PDF export (optional) |

---

## ⚙️ How to Run This Frontend App

### 1️⃣ Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher)
- npm or yarn
- Backend and model API running

### 2️⃣ Install Dependencies

```bash
cd frontend
npm install
npm run dev
