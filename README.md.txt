# 🚛 Transport Route Optimizer (GA-based)

A web-based logistics simulation tool that helps companies decide the **most cost-effective** shipping method — using either their **own fleet** or **third-party logistics (3PL)** — based on **annual demand** and **per-route costs**.

## 📌 Features

- Upload your Excel file with demand and cost data.
- Choose between **Company** and **3PL** using **Genetic Algorithm (GA)** optimization.
- Visual preview of routes and optimized decisions.
- Fully interactive web app powered by **Streamlit**.

## 📂 How It Works

1. Upload an Excel file with:
   - `Demand` sheet: Origin, Destination, and Demand.
   - `Cost` sheet: Origin, Destination, Company Cost, and 3PL Cost.

2. Set GA parameters:
   - Population size
   - Number of generations
   - Mutation rate

3. Get optimal route decisions + total transport cost.

## 📦 Example Excel Format

### Sheet: `Demand`

| From   | To     | Demand |
|--------|--------|--------|
| Riyadh | Jeddah | 800    |
| ...    | ...    | ...    |

### Sheet: `Cost`

| From   | To     | Company | 3PL |
|--------|--------|---------|-----|
| Riyadh | Jeddah | 950     | 1200 |

---

## 📊 Technologies

- Python 🐍
- Streamlit 🌐
- Pandas 📈
- Genetic Algorithms 🧬

---

## 🚀 Try It Online

> You can deploy this app using [Streamlit Cloud](https://streamlit.io/cloud)

---

## 👤 Developed by

**Hussein (Sahnonman)**  
Logistics Optimization Enthusiast | 🇸🇦 Saudi Arabia

---

