# 🚀 Gender Prediction Web Application (Flask + OpenCV)

## 📌 Project Overview
This project is an **end-to-end Gender Prediction Web Application** built using **Computer Vision and Deep Learning**, deployed via a **Flask web server**. The application detects human faces from images and predicts the **gender** using a trained deep learning model, providing a simple and interactive web interface for inference.

The project demonstrates the complete **machine learning lifecycle** — from preprocessing and model inference to backend integration and web deployment.

---

## 🧠 Key Features
- 📷 Face detection using **OpenCV**
- 🧠 Gender classification using a **pre-trained deep learning model**
- 🌐 Web application built with **Flask**
- ⚡ Real-time prediction on uploaded images
- 📁 Clean and modular project structure
- 🔄 End-to-end pipeline:  
  **Input → Face Detection → Prediction → Output**

---

## 🏗️ Tech Stack
- **Programming Language:** Python  
- **Computer Vision:** OpenCV  
- **Deep Learning:** TensorFlow / Keras  
- **Web Framework:** Flask  
- **Frontend:** HTML, CSS (Jinja Templates)  
- **Model Format:** `.h5` (Saved Keras Model)

---

## 📂 Project Structure

```
Gender_predictor_app/
│
├── model/
│   └── gender_model.h5
│
├── static/
│   ├── css/
│   └── uploads/
│
├── templates/
│   └── index.html
│
├── app.py
├── requirements.txt
└── README.md
```

---

## ⚙️ How It Works
1. User uploads an image through the web interface  
2. Image is processed using **OpenCV**  
3. Face(s) are detected using a **Haar Cascade / DNN-based detector**  
4. Detected face is passed to the **CNN-based gender classification model**  
5. Prediction is returned and displayed on the web page  

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/tusharg007/Gender_predictor_app.git
```
2️⃣ Navigate to the project directory
cd Gender_Prediction_Flask_CV

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run the Flask application
python main.py

5️⃣ Open in browser
http://127.0.0.1:5000/

## 📈 Learning Outcomes

Hands-on experience with **computer vision pipelines**

Practical understanding of **Flask-based ML deployment**

Experience in **model inference** and **backend integration**

Exposure to production-style project structuring

Improved understanding of **real-world ML workflows**

## 🔮 Future Enhancements

Add confidence score with predictions

Support **live webcam-based gender detection**

Improve accuracy using **transfer learning**

Deploy on **cloud platforms (Render / Railway / AWS)**

Add **multi-face detection support**

## 🧑‍💻 Author

**Tushar Ghosh**
**Data Science & Computer Vision Enthusiast**

## 📌 This project was independently built, customized, and deployed for learning and practical demonstration purposes.
