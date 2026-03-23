# ⚡ Power Plant Energy Prediction using ANN

## 📌 Overview

This project implements an **Artificial Neural Network (ANN)** to predict the **energy output of a power plant** based on environmental factors such as temperature, pressure, humidity, and exhaust vacuum.

The goal is to build a regression model that can accurately estimate power generation under different conditions.

---

## 📊 Dataset

The dataset contains the following features:

* 🌡️ Temperature (T)
* 💨  Vacuum (V)
* 🌫️ Ambient Pressure (AP)
* 💧 Relative Humidity (RH)

🎯 Target:

* ⚡ Energy Output (PE)

---

## 🧠 Model Architecture

* Fully Connected Neural Network (ANN)
* Input Layer → Hidden Layers → Output Layer
* Activation Function: ReLU
* Loss Function: Mean Squared Error (MSE)

---

## ⚙️ Tech Stack

* Python 🐍
* PyTorch 🔥
* NumPy
* Pandas
* Matplotlib

---

## 🚀 Features

* Data preprocessing and normalization
* ANN model implementation using PyTorch
* Training and validation pipeline
* Loss tracking (Train vs Validation)
* Model evaluation

---

## 📉 Training

* Optimizer: Adam
* Loss Function: MSELoss
* Epochs: 10–100 (configurable)

---

## 📈 Results

* Model learns relationship between environmental factors and energy output
* Training and validation loss used to evaluate performance
* Helps understand overfitting and generalization

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/power-plant-energy-prediction-ann.git
```

2. Navigate to the project folder:

```bash
cd power-plant-energy-prediction-ann
```

3. Run the notebook or script:

```bash
jupyter notebook
```

---

## 📌 Future Improvements

* Add Dropout for regularization
* Hyperparameter tuning
* Use advanced architectures
* Deploy as a web app

---

## 🙌 Author

**Priyanshi Tiwari**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
