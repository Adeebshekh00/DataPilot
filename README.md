# 🚀 DataPilot

**Interactive AI-powered platform for exploring credit card customer data, visualizing trends, and predicting churn in real-time using ML models.**

---

## 📌 Project Highlights

- 🛠 **Built & deployed** a Streamlit-based app to **upload datasets**, explore data, visualize trends with **Plotly**, and obtain **real-time churn predictions** using ML models.  
- 📈 Achieved **97.2%+ accuracy** on customer attrition using ensemble models (**XGBoost, Random Forest, AdaBoost**) fine-tuned with **GridSearchCV** and a **ColumnTransformer preprocessing pipeline**.  
- 🤖 Embedded an **LLM-powered AI assistant (LLaMA-4 via Groq API)** to answer questions about churn logic, code snippets, and graph explanations — enhancing usability for both technical and non-technical users.

---

## 📂 Dataset

This project uses the **"Bank Customer Churn Prediction"** dataset from Kaggle:

[Kaggle – Credit Card Customer Churn Dataset](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)

---

## 🌐 Live Demo

Experience the application live at:

[Link](https://datapilot00.streamlit.app/)

---

## 🛠 Setup & Installation

Steps to run locally:

```bash
git clone https://github.com/Adeebshekh00/DataPilot.git
cd DataPilot

# Create virtual environment (Windows)
python -m venv .venv
.venv\Scripts\activate

# (macOS/Linux)
# python3 -m venv .venv
# source .venv/bin/activate

pip install -r requirements.txt

# Create a .env file with your Groq API key
echo GROQ_API_KEY=your_api_key > .env

# Launch the app
streamlit run Home.py
