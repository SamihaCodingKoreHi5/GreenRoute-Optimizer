# 🌱 GreenRoute-Optimizer: Eco-Friendly Trip Analyzer

An interactive, data-driven spatial analytics dashboard built with Python and Streamlit that maps popular cities across Bangladesh, calculates real-time trip distance vectors, optimizes travel paths, and provides actionable environmental tree offset metrics.

This project beautifully complements my previous implementations in automotive tracking (`Smart-car-trip-analyzer`) and environmental impacts (`AI-Model-Carbon-Footprint-Tracker`) by synthesizing routing logic with carbon footprint modeling.

---

## 🚀 Live Visual Preview

Keep track of the visuals by viewing the dashboard interfaces below:

### 📊 Configuration & Key Metric Cards

![Dashboard Overview](assets/dashboard_preview.png)

### 🗺️ Data Table Breakdown & Spatial Route Mapping Node

![Metrics and Data Visualization](assets/metrics_chart.png)

---

## ✨ Core Features

- **📍 Real Bangladesh Cities Registry Database:** Computes spatial values based on exact geographical coordinates ($\text{Lat/Lon}$) for major hubs like Dhaka, Chittagong, Sylhet, Rajshahi, Khulna, Barisal, Rangpur, and Cox's Bazar.
- **🚗 Dynamic Multi-Scenario Routing Engine:** Uses real coordinate differences to mathematically estimate distances and simulates 3 operational paths based on alternative traffic overhead factors.
- **🌳 Carbon Offset Metric Simulator:** Calculates the explicit number of mature trees required annually to completely neutralize your selected trip's greenhouse gas emissions.
- **📉 Interactive Visualization Dashboard:** Renders clean data comparative tracking using native Streamlit tabular view frameworks alongside Plotly Express multi-colored bar charts.
- **🗺️ Interactive Vector Map Plotting:** Dynamically updates coordinate pins on a relative geographical map whenever a user alters destinations or parameters.
- **📥 Native CSV Data Exporter:** Features an integrated data download stream module allowing users to pull calculated routing sheets straight out of the app.

---

## 🛠️ Installation & Local Setup

Follow these steps to deploy and explore the optimizer on your machine:

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/SamihaCodingKoreHi5/GreenRoute-Optimizer.git](https://github.com/SamihaCodingKoreHi5/GreenRoute-Optimizer.git)
   cd GreenRoute-Optimizer
   ```

Install Required Framework Dependencies:
Make sure you have your virtual environment set up, then run:

Bash
pip install -r requirements.txt
Execute the Streamlit Core Engine:

Bash
streamlit run app.py
📊 Core Architecture & Dependencies
This application is engineered with a clean, lightweight Python file blueprint powered entirely by open-source libraries:

streamlit - For rendering the front-end user interface framework.

pandas - For dynamic data matrix parsing and data table generation.

plotly - For plotting pristine reactive bar metrics.

math - Built-in coordinate grid calculations.

📜 License
This project is licensed under the MIT License.
