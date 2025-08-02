# 📊 Brent Oil Price Change Point Analysis

> **Data-Driven Insights into the Impact of Major Events on Brent Crude Oil Prices**

---

## 📌 Project Overview

This project analyzes **how major geopolitical and economic events influence Brent crude oil prices** using statistical modeling and Bayesian change point detection.  
By identifying structural breaks in price trends and linking them to real-world events (like OPEC decisions, conflicts, and sanctions), we provide **actionable insights for investors, policymakers, and energy stakeholders**.

---

## 🎯 Business Objective

- Detect **significant change points** in Brent oil prices over the past decade.
- Associate changes with **key global events** (e.g., political shifts, conflicts, sanctions, OPEC actions).
- Quantify impact and volatility around these events.
- Present findings through an **interactive dashboard** to support data-driven decision-making.

---

## 🧠 Key Tasks

### ✅ Task 1: Laying the Foundation

- Defined analysis workflow and core objectives.
- Researched 10–15 key global events affecting oil markets.
- Performed time series exploration (trend, stationarity, assumptions).
- Prepared clean datasets and described changepoint modeling approach.

### ✅ Task 2: Change Point Modeling

- Implemented **Bayesian Change Point Detection** using `PyMC3`.
- Identified statistically significant structural breaks in oil prices.
- Linked detected changes to real-world events.
- Quantified shifts in average prices and volatility before/after key events.

### ✅ Task 3: Interactive Dashboard

- Developed a full-stack dashboard using **Flask (API backend)** and **React (frontend)**.
- Enabled dynamic exploration of price trends, change points, and event correlations.
- Features filtering, event highlights, and statistical indicators.

---

## 🗂️ Folder Structure

brent-oil-impact-analysis/
│
├── data/ # Raw, external, processed datasets
├── notebooks/ # EDA, modeling, event analysis
├── scripts/ # Reusable preprocessing and model code
├── dashboard/ # Flask (API) + React (UI)
├── reports/ # Plots, final report, presentation
├── environment.yml # Conda environment setup
├── requirements.txt # pip packages
├── README.md # Project documentation
└── .gitignore

---

## ⚙️ Tech Stack

| Layer         | Tools & Libraries                                      |
| ------------- | ------------------------------------------------------ |
| Language      | Python 3.10, JavaScript (ES6)                          |
| Data Analysis | `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`   |
| Modeling      | `PyMC3`, `statsmodels`, `ruptures`, `arviz`            |
| Dashboard     | `Flask`, `Flask-CORS`, `React`, `Recharts`, `Chart.js` |
| Dev Tools     | `JupyterLab`, `Git`, `VSCode`, `Postman` (API testing) |

---

## 📊 Example Outputs

- Change point detection plot with Bayesian probability.
- Summary of events and associated price shifts.
- Interactive UI with event filters and real-time data visualization.

---

## 🚀 How to Run

### 🔹 1. Clone the Repository

git clone https://github.com/your-username/brent-oil-impact-analysis.git
cd brent-oil-impact-analysis

🔹 2. Set Up Python Environment

conda env create -f environment.yml
conda activate brent_env
🔹 3. Run Notebooks
Navigate to the notebooks/ folder and start with:

jupyter lab
🔹 4. Start the Dashboard
Backend (Flask API):

cd dashboard/backend
python app.py
Frontend (React UI):

cd dashboard/frontend
npm install
npm start
