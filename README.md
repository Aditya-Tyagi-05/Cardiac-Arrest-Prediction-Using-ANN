# 🫀 Cardiac Arrest Prediction using Artificial Neural Network (ANN)

This project predicts the possibility of cardiac arrest in individuals using an Artificial Neural Network (ANN) model. It uses clinical data to provide early warnings and assist healthcare professionals in identifying high-risk patients.

---

## 📌 Table of Contents

- [About](#about)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 📖 About

Cardiac arrest is one of the leading causes of death globally. Early prediction and risk assessment can help in saving lives. This project aims to build a predictive model using **Artificial Neural Networks (ANN)** that can classify whether a person is at risk of cardiac arrest based on health parameters.

---

## 💻 Tech Stack

- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## ✅ Features

- Predicts cardiac arrest risk using ANN
- Data preprocessing and feature engineering
- Accuracy and performance evaluation
- Visualizations of model performance

---

## 📊 Dataset

- **Source**: Kaggle
- **Features Used**:
  - Age
  - Gender
  - Chest Pain Type
  - Resting Blood Pressure
  - Cholesterol
  - Fasting Blood Sugar
  - Resting ECG Results
  - Max Heart Rate Achieved
  - Exercise-Induced Angina
  - Oldpeak (ST depression)
  - ST Slope
  - ...and others

---

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/cardiac-arrest-ann.git
   cd cardiac-arrest-ann
   ```

2. **Create a virtual environment (optional)**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application (if using Streamlit)**
   ```bash
   streamlit run app.py
   ```

---

## ▶️ Usage

- Open the application
- Enter the patient details (age, chest pain type, etc.)
- Click **Predict**
- The model will show whether the person is **at risk** or **not at risk**

---

## 🧠 Model Architecture

- **Input Layer**: Number of input features
- **Hidden Layers**:
  - Dense Layer with 64 neurons and ReLU activation
  - Dense Layer with 32 neurons and ReLU activation
- **Output Layer**:
  - Dense Layer with 1 neuron and Sigmoid activation (binary classification)

- **Loss Function**: Binary Crossentropy  
- **Optimizer**: Adam  
- **Metrics**: Accuracy

---


## 🤝 Contributing

Contributions are welcome!  
If you find a bug or want to improve the code, feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

**Aditya Tyagi**  
📧 Email: supertgoofficial@gmail.com  
🔗 LinkedIn: (https://linkedin.com/in/aditya-tyagi-18b696327)

---
