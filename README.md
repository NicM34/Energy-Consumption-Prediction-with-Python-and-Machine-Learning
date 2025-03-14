<div align="center">

  <h1>⚡ Energy Consumption Prediction using Machine Learning ⚡</h1>
  
  <p>
    🔥 A project that predicts household energy consumption using machine learning models. 🔥
  </p>
  
  
<!-- Badges -->
<p>
  <a href="https://github.com/nicolesportfolio">
    <img src="https://img.shields.io/badge/Author-Wandisiwe%20Nicole%20Manyathela-blue" alt="author" />
  </a>
  <a href="mailto:nicolemanyathela5@gmail.com">
    <img src="https://img.shields.io/badge/Contact-nicolemanyathela5%40gmail.com-red" alt="contact" />
  </a>
</p>

</div>

<br />

## 📖 Table of Contents

- [⭐ About the Project](#star2-about-the-project)
  * [🛠 Tech Stack](#space_invader-tech-stack)
  * [🎯 Features](#dart-features)
- [🚀 Getting Started](#toolbox-getting-started)
  * [⚠️ Prerequisites](#bangbang-prerequisites)
  * [⚙️ Installation](#gear-installation)
  * [🏃‍♂️ Run Locally](#running-run-locally)
- [👀 Usage](#eyes-usage)
- [📊 Results & Performance](#chart_with_upwards_trend-results--performance)
- [🚀 Future Improvements](#rocket-future-improvements)
- [⚠️ License](#warning-license)
- [🤝 Contact](#handshake-contact)

---

## ⭐ About the Project

This project utilizes machine learning techniques to predict household energy consumption based on various environmental and appliance usage factors. The dataset contains over 500,000 records of energy consumption data collected from different household appliances, along with environmental parameters such as temperature, humidity, and pressure.

### 🛠 Tech Stack

- **🐍 Python**
- **📊 Pandas & NumPy** (Data manipulation)
- **📉 Matplotlib & Seaborn** (Data visualization)
- **🤖 Scikit-learn** (Machine learning models & preprocessing)

### 🎯 Features

- ✅ Data preprocessing and feature selection
- ✅ Implementation of **Multi-Layer Perceptron (MLP) Regressor**
- ✅ Implementation of **Random Forest Regressor**
- ✅ Model evaluation using **Mean Absolute Error (MAE)**
- ✅ Visualization of predictions vs. actual values

---

## 🚀 Getting Started

### ⚠️ Prerequisites

Ensure you have Python installed and install the required libraries:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

### ⚙️ Installation

Clone the project repository:

```bash
git clone https://github.com/nicolesportfolio/energy-consumption-prediction.git
cd energy-consumption-prediction
```

---

## 🏃‍♂️ Run Locally

1. 🔄 Load the dataset and preprocess it.
2. 🎯 Run the training script:

```bash
python train_model.py
```

3. 🔮 Use the trained model to make predictions.

---

## 👀 Usage

The model takes input features such as **🌡️ temperature, 💦 humidity, 🏋️‍♂️ pressure, and 🏠 appliance power consumption** and predicts the **overall household energy consumption**.

Example usage:

```python
from model import predict_energy

data = {
    "temperature": 36.17,
    "humidity": 0.20,
    "apparentTemperature": 29.22,
    "pressure": 1016.90,
    "Fridge [kW]": 0.123540,
    "Microwave [kW]": 0.004065,
    "Dishwasher [kW]": 0.000020,
    "Garage door [kW]": 0.013081,
    "Living room [kW]": 0.00162
}

prediction = predict_energy(data)
print("⚡ Predicted energy consumption:", prediction)
```

---

## 📊 Results & Performance

- **📉 MLP Model MAE:** 0.2846
- **🌲 Random Forest Model MAE:** 0.1366 (better performance)

📌 The following scatter plot visualizes the model’s predictions:

![Actual vs Predicted](https://via.placeholder.com/600x400?text=Visualization+Here)

---

## 🚀 Future Improvements

- 🚀 **Implement more advanced models** (e.g., XGBoost, LSTM for time-series forecasting).
- 🔍 **Optimize hyperparameters** for better performance.
- 🌐 **Deploy the model** as a web app or API for real-time predictions.

---

## ⚠️ License

This project is **open-source** and available under the **MIT License**.

---

## 🤝 Contact

👩‍💻 **Wandisiwe Nicole Manyathela**  
🔗 GitHub: [nicolesportfolio](https://nicolesportfolio.vercel.app/#projects)  
📧 Email: [nicolemanyathela5@gmail.com](mailto:nicolemanyathela5@gmail.com)

