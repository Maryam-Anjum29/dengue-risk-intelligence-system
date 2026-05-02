# 🦟 Dengue Risk Intelligence Dashboard

### Climate-driven dengue modeling, visualization, and early-warning insights

---

## 🚀 Overview

This project presents an **interactive dengue analytics dashboard** that explores the relationship between climatic variables and dengue incidence using:

* 📊 Exploratory Data Analysis (EDA)
* 📈 Time-series visualization
* 🤖 Regression modeling (OLS)
* 🌦️ Climate–disease interaction insights

The goal is to demonstrate how **temperature, humidity, and rainfall patterns** can be leveraged for **early-warning systems and public health decision-making**.

---

## 🎯 Problem Statement

Dengue outbreaks are strongly influenced by environmental conditions, yet many regions lack **data-driven surveillance tools**.

This project answers:

> *Can climatic variables alone provide meaningful predictive signals for dengue outbreaks?*

---

## 🧠 Key Insights

* 🌡️ Temperature is the strongest predictor of dengue cases
* 💧 Humidity amplifies transmission risk significantly
* 🌧️ Rainfall shows diminishing returns at extreme levels
* 📅 Strong seasonal peaks observed during monsoon months (July–August)
* 📉 Low-risk periods identified in winter (Jan–Feb)

---

## 📊 Dashboard Features

* Interactive time-series of dengue cases
* Scatter plots (climate vs cases)
* Monthly seasonality breakdown
* Regression model summary (coefficients, R², RMSE)
* Predicted vs actual comparison

---

## 🧪 Methodology

### Data

* 300 weekly observations (2019–2024)
* Variables:

  * Temperature (°C)
  * Humidity (%)
  * Rainfall (mm)
  * Dengue cases

> ⚠️ Note: Current dataset is **synthetic**, designed to simulate realistic seasonal and climatic patterns. Future versions will integrate real-world epidemiological datasets.

---

### Model

* Ordinary Least Squares (OLS) regression
* Target: Dengue cases
* Features: Temperature, humidity, rainfall

**Performance:**

* R² ≈ 0.88
* RMSE ≈ (model output)

---

## 🖥️ Tech Stack

* HTML / CSS / JavaScript
* Chart.js (visualizations)
* Vanilla JS (data simulation + modeling)

---

## 📸 Preview

<img width="858" height="330" alt="image" src="https://github.com/user-attachments/assets/d2074bbd-6604-47db-b753-fa04f2fe4800" />
<img width="858" height="330" alt="image" src="https://github.com/user-attachments/assets/50995494-9706-48e4-a305-46cd2384c8b1" />
<img width="858" height="330" alt="image" src="https://github.com/user-attachments/assets/0e078983-5d5b-483b-9bbb-392edcfe6888" />
<img width="1801" height="390" alt="image" src="https://github.com/user-attachments/assets/320baca9-d491-4302-8f10-cb5886382e53" />



---

## ⚡ How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/dengue-dashboard.git

# Open the dashboard
open dengue_eda_dashboard.html
```

Or simply open the `.html` file in your browser.

---

## 🌍 Applications

* Public health surveillance systems
* Climate-based disease prediction
* Early-warning tools for dengue outbreaks
* Policy and intervention planning

---

## 🔮 Future Work

* Integrate real-world datasets (WHO / national health data)
* Add machine learning models (Random Forest, XGBoost)
* Incorporate lag effects (rainfall → mosquito breeding cycles)
* Deploy as a web app (Streamlit / Flask)
* Expand to multi-disease modeling (malaria, chikungunya)

---

## 🤝 Contributing

Contributions, ideas, and collaborations are welcome.
Feel free to fork the repo or open an issue.

---

## 📜 License

This project is open-source under the MIT License.

---

## 👤 Author

**Maryam Anjum**
MPhil  Entomology | Data-driven Entomology & Public Health Research

---

## ⭐ Final Note

This project is a **proof-of-concept** demonstrating how data science can bridge climate analytics and disease forecasting.

> The real value lies not in the dashboard — but in scaling this into a **decision-support system for real-world impact**.
