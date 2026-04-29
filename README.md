# 🐄 HerdAI

### Spatiotemporal Epidemic Prediction Using Graph Neural Networks

---

## 📌 Overview

**HerdAI** is an end-to-end AI system that simulates cattle herd behavior and predicts disease spread using **Agent-Based Modeling (ABM)** and **Spatio-Temporal Graph Neural Networks (STGNN)**.

It combines **simulation, data generation, analytics, and deep learning** to model how diseases evolve across both **space and time** in livestock populations.

---

## 🚀 Key Features

* 🐄 **Agent-Based Simulation** of cattle behavior and interactions
* 📊 **Multimodal Dataset Generation** (temperature, activity, respiratory signals, location)
* 📈 **Epidemic Analysis & Visualization** (SEIRS dynamics, heatmaps, correlations)
* 🤖 **Spatio-Temporal Graph Neural Network (STGNN)** for prediction
* 📉 **Performance:**

  * Accuracy: **91%**
  * ROC-AUC: **0.97**

---

## 👤 My Contributions

* Designed and implemented the **agent-based simulation framework**
* Generated and structured a **multimodal synthetic dataset (100,000+ records)**
* Performed **data preprocessing, feature engineering, and exploratory analysis**
* Built and trained the **Spatio-Temporal Graph Neural Network (STGNN)** using PyTorch
* Developed **visualizations** for epidemic trends, spatial spread, and feature relationships
* Evaluated model performance using **accuracy, ROC-AUC, and loss metrics**

---

## 🧠 Problem Statement

Livestock disease outbreaks can cause significant economic and ecological damage.
Traditional monitoring methods are reactive and often detect issues too late.

**Goal:**
To build an AI-driven system that can **simulate herd behavior** and **predict disease spread early**, enabling proactive intervention.

---

## 🏗️ Project Pipeline

```
Simulation → Data Generation → Data Analysis → Graph Construction → STGNN → Prediction
```

---

## ⚙️ System Workflow

### 1️⃣ Simulation

* 100 cattle agents
* Grid-based environment
* Movement, feeding, and interaction patterns
* SEIRS disease model

### 2️⃣ Data Generation

* 100,000+ records
* Features include:

  * Body temperature
  * Activity levels
  * Respiratory signals
  * Position & zone
  * Breed, age, susceptibility

### 3️⃣ Data Analysis

* Epidemic curves
* Correlation matrix
* Spatial heatmaps
* Time-series decomposition

### 4️⃣ Graph Construction

* Nodes → cattle agents
* Edges → proximity-based interactions
* Dynamic adjacency matrix

### 5️⃣ Model (STGNN)

* Temporal Convolution Layers
* Graph Convolution Layers
* Attention-based pooling
* Binary classification (Healthy vs Infected)

---

## 🧪 Model Performance

| Metric   | Value |
| -------- | ----- |
| Accuracy | 0.911 |
| ROC-AUC  | 0.970 |
| Loss     | 0.26  |

📌 The model effectively captures **spatial interactions and temporal disease progression**, enabling accurate prediction of infection states.

---

## 📊 Visualizations

*(Add your uploaded images below this section)*

* Epidemic curves (SEIRS progression)
* Sensor distribution plots
* Correlation heatmaps
* Spatial infection maps
* Time-series analysis

---

## 🛠️ Tech Stack

**Languages:** Python

**Libraries:**

* PyTorch
* NumPy, Pandas
* Matplotlib, Seaborn
* SciPy

**Concepts:**

* Agent-Based Modeling
* Graph Neural Networks
* Spatio-Temporal Learning
* Epidemiological Modeling

---

## 📂 Project Structure

```
HerdAI/
│── data/
│── figures/
│── models/
│── scripts / notebooks
│── README.md
```

---

## ⚙️ How to Run

```bash
# Clone repository
git clone https://github.com/your-username/HerdAI.git
cd HerdAI

# Install dependencies
pip install -r requirements.txt

# Run project
python main.py
```

---

## 👥 Contributors

* Ugwuaneke Lucy Ifeoma
* Swapnil Samrat
* Parth Bhutada
* Saleem Saeed

---

## 🌍 Applications

* Smart Agriculture
* Livestock Health Monitoring
* Early Disease Detection
* Epidemiological Modeling
* AI for Sustainability

---

## 🔮 Future Work

* Integrate real-time IoT sensor data
* Deploy as a web-based dashboard
* Extend to multi-species modeling
* Explore Transformer-based architectures

---

## 📬 Contact

Feel free to connect for collaboration, research, or opportunities.

---

## ⭐ Support

If you found this project interesting, consider giving it a ⭐ on GitHub!

---

