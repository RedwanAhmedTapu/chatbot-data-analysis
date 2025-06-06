# 💬 Chatbot Message Analysis System

![Customer Segmentation](reports/figures/customer_segments.png)

## 📌 Project Overview

This project analyzes customer chatbot interactions to uncover product demand patterns, customer engagement levels, and operational insights using machine learning and clustering techniques.

---

## ✨ Key Features

- 🧼 Automated data cleaning pipeline for raw chat logs  
- 📈 Product demand analysis and trend visualization  
- 👥 Customer segmentation using K-Means clustering  
- ⏱️ Insights for optimizing response times  
- 📊 Automated report generation with visual summaries  

---

## 🚀 How to Use

### 1. 📄 Explore the Notebooks
Check the step-by-step data analysis in Jupyter:
- [`1_data_cleaning.ipynb`](notebook/chat_bot_data_analysis.ipynb)

### 2. 🔗 Run It on Binder (No Install Required)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/RedwanAhmedTapu/chatbot-data-analysis/HEAD?filepath=notebooks%2Fchat_bot_data_analysis.ipynb)

### 3. 💻 Run Locally
```bash
# Clone the repository
git clone https://github.com/RedwanAhmedTapu/chatbot-data-analysis.git
cd chatbot-data-analysis

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate        # For Linux/Mac
# venv\Scripts\activate         # For Windows

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
