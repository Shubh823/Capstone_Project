# 🚀 Machine Learning & Deep Learning Capstone Projects

This repository contains a collection of end-to-end **Machine Learning and Deep Learning capstone projects** completed as part of my learning journey.

Each notebook focuses on solving a different real-world problem and covers the complete workflow from **data preparation and model building to evaluation, comparison, and final analysis**.

---

## 📂 Projects

### 📊 1. Customer Churn Prediction

**Notebook:** `day16_capstone (1).ipynb`

An end-to-end Machine Learning classification project focused on identifying customers who are likely to churn.

#### Key Work

- Data generation and exploration
- Data leakage detection
- Train, validation, and test splitting
- Numerical and categorical preprocessing
- Machine Learning pipelines
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- Gradient Boosting
- Stratified Cross-Validation
- Hyperparameter tuning with `GridSearchCV`
- ROC-AUC based model selection
- Confusion matrix and classification metrics
- Precision and recall evaluation
- Classification threshold analysis
- Business-focused churn recommendation

The project compares multiple classification algorithms and tunes the selected Gradient Boosting model to build a practical customer-retention solution.

---

### 🖼️ 2. CIFAR-10 Image Classification with Transfer Learning

**Notebook:** `day20_capstone.ipynb`

A Computer Vision project that classifies images from the **CIFAR-10 dataset** using both a CNN built from scratch and transfer learning with **MobileNetV2**.

#### Key Work

- CIFAR-10 image preprocessing
- Data visualization
- CNN model from scratch
- Data augmentation
- Transfer Learning with MobileNetV2
- Feature extraction
- Model fine-tuning
- Early stopping and model checkpointing
- Accuracy evaluation
- Confusion matrix
- Precision, Recall, and F1-score
- Grad-CAM visualization for model interpretability
- Baseline vs transfer-learning comparison

The project demonstrates how pretrained visual features and fine-tuning can improve image-classification performance compared with learning entirely from scratch.

---

### ⚡ 3. Energy-Demand Forecasting with LSTM + Attention

**Notebook:** `day22_capstone.ipynb`

A Deep Learning time-series forecasting project that predicts the **next 24 hours of energy demand using the previous 168 hours**.

#### Key Work

- Synthetic hourly energy-demand generation
- Daily and weekly seasonal patterns
- Sliding-window sequence creation
- 168-hour lookback window
- 24-hour forecasting horizon
- Chronological train/validation/test splitting
- Train-only normalization
- Seasonal-naive forecasting baseline
- LSTM forecasting
- LSTM with Attention
- Early stopping
- MAE, RMSE, and MAPE evaluation
- Forecast visualization
- Teacher forcing vs autoregressive forecasting analysis

The project compares a strong seasonal baseline with LSTM and LSTM-with-attention approaches to understand whether more advanced sequence models provide a meaningful forecasting improvement.

---

## 📌 Project Overview

| Project | Problem Type | Main Models / Techniques |
|---|---|---|
| Customer Churn Prediction | Classification | Logistic Regression, Random Forest, SVM, Gradient Boosting |
| CIFAR-10 Image Classification | Computer Vision | CNN, MobileNetV2, Transfer Learning, Grad-CAM |
| Energy-Demand Forecasting | Time-Series Forecasting | Seasonal Baseline, LSTM, Attention |

---

## 🛠️ Technologies Used

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Scikit-learn**
- **TensorFlow**
- **Keras**
- **Jupyter Notebook**

---

## 🧠 Concepts Covered

The projects collectively demonstrate practical knowledge of:

- Data preprocessing and exploration
- Feature preprocessing
- Train/validation/test splitting
- Classification
- Cross-validation
- Hyperparameter tuning
- Model evaluation
- Deep Learning
- Convolutional Neural Networks
- Transfer Learning
- LSTM Networks
- Attention Mechanisms
- Time-Series Forecasting
- Data Augmentation
- Model Interpretability
- Grad-CAM
- Data Leakage Prevention
- Performance comparison against baseline models

---

## 📁 Repository Structure

All capstone notebooks are currently stored directly in the repository.

```text
Capstone-Projects/
│
├── day16_capstone (1).ipynb
├── day20_capstone.ipynb
├── day22_capstone.ipynb
├── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone <your-repository-url>
cd <your-repository-name>
```

Create a virtual environment:

```bash
python -m venv .venv
```

### Windows

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
source .venv/bin/activate
```

Install the main dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow jupyter
```

Or, if `requirements.txt` is available:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Projects

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open the required `.ipynb` file and run the cells from **top to bottom**.

---

## 🎯 Learning Outcomes

Through these capstone projects, I gained hands-on experience in:

- Designing complete Machine Learning workflows
- Comparing different algorithms
- Hyperparameter tuning and cross-validation
- Evaluating classification models with appropriate metrics
- Building CNN architectures
- Applying transfer learning with pretrained networks
- Understanding and visualizing model decisions with Grad-CAM
- Preparing sequential data for time-series forecasting
- Building LSTM models
- Applying attention to sequence models
- Comparing advanced models against simple baselines
- Translating model results into practical conclusions

---

## 🔮 Future Work

This repository will continue to grow with additional capstone projects covering different areas of:

- Machine Learning
- Deep Learning
- Computer Vision
- Natural Language Processing
- Time-Series Forecasting
- Generative AI

---

## 👨‍💻 Author

**Shubham Bhushan Patil**

Graduate Apprentice  
Python | Machine Learning | Deep Learning | Data Science

---

## ⭐ About This Repository

This repository represents my practical learning journey in **Artificial Intelligence, Machine Learning, and Deep Learning**.

Rather than focusing only on individual algorithms, each capstone project applies multiple concepts together to solve a complete problem from **data preparation to final evaluation and analysis**.
