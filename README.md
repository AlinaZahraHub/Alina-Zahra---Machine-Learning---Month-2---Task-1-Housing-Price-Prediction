# Alina-Zahra---Machine-Learning---Month-2---Task-1-Housing-Price-Prediction

> An enterprise-grade ultra-luxury real estate valuation web application built for predicting property prices based on features like area, bedrooms, and location. Developed as part of the Machine Learning Internship Program at **Arch Technologies**.

---

## 🔗 Live Demo

* **Live Application:**
  

 <img width="1919" height="917" alt="image" src="https://github.com/user-attachments/assets/1a1cdde7-81ce-4052-85a9-fae128397d9e" />


---

## 📌 Problem Statement & Motivation
With Lahore’s real estate market expanding rapidly, accurate and transparent property valuation is essential for buyers, sellers, and investors. This project delivers an end-to-end supervised machine learning pipeline trained directly on local Lahore real estate datasets (`lahore_house_listings_zameen.csv`) to automatically evaluate and predict property market values under elite brand standards in real-time.

---

## ✨ Key Features & Architecture
* **Trained ML Regression Engine:** Powered by a robust Random Forest Regressor trained on 10k+ Lahore real estate market transactions.
* **Luxury Emaar-Inspired UI:** Designed with a bespoke dark-mode editorial layout, gold-accented typography (Cormorant Garamond & Inter), and interactive custom number inputs.
* **Dynamic Capital Evaluation:** Computes precise property asset valuations in Crores/PKR instantly upon user interaction.
* **Technical Metadata Insights:** Built-in verification badges showing active model version (`v2.pkl`), algorithm type, and input feature configuration.
* **Responsive Editorial Split-Screen:** Mirrors high-end architectural web portals for an immersive user experience.

---

## 🛠️ Tech Stack & Tools
* **Programming Language:** Python
* **Machine Learning & Data Science:** Scikit-Learn (Random Forest), Pandas, NumPy, Pickle/Joblib
* **Frontend & UI:** Streamlit, Custom CSS (Glassmorphism & Gold Theme)
* **Deployment & Version Control:** Streamlit Community Cloud, GitHub

---

## 🔄 Project Architecture & Workflow
1. **User Input:** User inputs property parameters (Location/Society, Area in Marla, Bedrooms, Bathrooms) via the interactive Streamlit console.
2. **Data Preprocessing & Engineering:** Input attributes are structured and mapped into expected model schema features (`Clean_Area_Marla`, `Bedrooms`, `Bathrooms`, `Total_Rooms`).
3. **Model Prediction:** The pre-trained Random Forest model (`house_price_model_v2.pkl`) evaluates the engineered feature vector.
4. **Currency Transformation:** Model output is scaled and converted into PKR Crore formatting with professional precision.
5. **Result Render:** The luxury editorial dashboard displays the headline hero valuation badge and breakdown metrics.

---

## ⚙️ Installation & Local Setup Guide

Follow these steps to run the project locally on your machine:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/AlinaZahraHub/Alina-Zahra---Machine-Learning---Month-2---Task-1-Housing-Price-Prediction.git](https://github.com/AlinaZahraHub/Alina-Zahra---Machine-Learning---Month-2---Task-1-Housing-Price-Prediction.git)
   cd Housing-Price-Prediction

```

2. **Install dependencies:**
```bash
pip install -r requirements.txt

```


3. **Run the Streamlit application:**
```bash
streamlit run app.py

```



---

## 📂 Project Structure

```text
House-Price-Prediction/
│
├── app.py                         # Main Streamlit application interface and logic
├── house_price_prediction_v2.ipynb # Jupyter Notebook containing EDA, preprocessing, and model training
├── house_price_model_v2.pkl       # Trained Random Forest regression model weights
├── lahore_house_listings_zameen.csv # Real estate dataset used for training and testing
├── requirements.txt               # Project dependencies
└── README.md                      # Project documentation

```

---

## 👩‍💻 Author & Acknowledgement

* **Name:** Alina Zahra
* **Internship Program:** Machine Learning Internship & Training Program (August – September 2026)
* **Organization:** Arch Technologies
* **GitHub:** https://github.com/AlinaZahraHub
* **LinkedIn:** https://www.linkedin.com/in/alina-zahra12/

```

```
