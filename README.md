# 🌍 GeoRiskPredict: AI-Powered Geo Safety Predictor

**GeoRiskPredict** is a geo-location based AI project that generates synthetic datasets and predicts the danger level of areas in Morocco based on age, sex, time, and location.

This project focuses on preparing, training, and evaluating machine learning models for urban safety analysis.

---

## ✨ Features

- 🕒 **Time-based Danger Detection**: Considers time of day for risk assessment  
- 👤 **Age & Gender Sensitive**: Adjusts danger predictions based on victim profile  
- 📍 **Location-Specific Analysis**: Parks, mosques, and public spaces  
- 📊 **Multiple ML Models**: Random Forest, Gradient Boosting, SVM, KNN, Logistic Regression  
- 🔄 **Daily Updates**: Generates realistic synthetic data for continuous model testing  

---

## 📂 Dataset & Models

### Dataset

- **File:** `geo_safety_data.csv`  
- **Contents:** Coordinates, time, age, sex, risk label  
- **Purpose:** Training and evaluation of AI models for danger prediction  

### Trained Models & Notebooks

- `RandomForestModel.ipynb`  
- `GradientBoostingM.ipynb`  
- `LogisticRegrModele.ipynb`  
- `svmM&knnM.ipynb`  
- `models_audio_text/` (Whisper-small integration for audio keywords)

---

## 🧰 Tech Stack

- **Languages:** Python  
- **Libraries:** scikit-learn, torch, transformers, datasets, librosa, soundfile  
- **Data:** Synthetic geolocation-based dataset  

---

### 🧠 AI Module Info

The machine learning models are designed to predict dangerous zones based on synthetic data.

- **Random Forest** achieved ~95% accuracy.
- Other models (**Gradient Boosting, Logistic Regression, SVM, KNN**) are included for comparison.

---

### 🔗 Related Projects

This AI module is integrated into the **ShakeUp** mobile app for real-time danger prediction:

👉 [ShakeUp GitHub Repository](https://github.com/AjgagalAsma/ShakeUp)


---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/AjgagalAsma/GeoRiskPredict.git
cd GeoRiskPredict
```
### 2. Install dependencies

```bash
pip install torch transformers
```
### 3. Run notebooks
- Open any of the .ipynb notebooks in Jupyter or Colab to train or evaluate the models.

