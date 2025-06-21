# 🚖 Ride-Sharing Demand Forecasting & Surge Pricing Insights

This end-to-end data analytics project explores patterns in ride-sharing demand and surge pricing using Uber/FHV data. Built with Python and Power BI, it delivers insights into peak hours, base activity, and surge patterns — enabling better operational and pricing decisions.

![Dashboard Preview](dashboard/powerbi_screenshots/page1_daily_overview.PNG)

---

## 📌 Project Overview

- **Dataset**: Downsampled version of Kaggle’s NYC Uber/FHV ride data (Jan–June 2015)
- **Tools Used**:  
  - Python (Pandas, Matplotlib, Seaborn)  
  - Power BI (Data Modeling + Visual Dashboards)  
  - Jupyter Notebook

---

## 🎯 Objectives

- Analyze temporal ride demand (hour, weekday, month)
- Identify surge-like high-demand periods using Z-scores
- Visualize base-wise performance
- Create interactive dashboards for insights

---

## 🧾 Dataset Description

| Column                 | Description                               |
|------------------------|-------------------------------------------|
| `Dispatching_base_num` | Base/dispatch code of the ride            |
| `Pickup_date`          | Ride pickup timestamp                     |
| `locationID`           | Zone code or ID for pickup (if available) |
| `Affiliated_base_num`  | Associated base number (where present)    |

📁 Cleaned data saved as: `data/processed/uber_sampled_cleaned.csv`

🔗 **Download Full Data & Dashboard Files**:  
[📂 Google Drive Link](https://drive.google.com/drive/folders/1k9-AQv--hyDYhC2EAJZikWRuA9tuN8ZH?usp=drive_link)

---

## 📊 Key Dashboards (Power BI)

| Page | Description |
|------|-------------|
| **Page 1**: Daily Ride Demand Overview | KPIs, trends by hour/weekday/month |
| **Page 2**: Base Performance & Surge Hotspots | Top-performing dispatch bases, surge zones |
| **Page 3**: Strategic Business Insights | Actionable metrics for supply planning |

All dashboards use Uber’s signature dark theme:

- **Background**: `#121212`  
- **Highlight Blue**: `#2171ec`  
- **Text**: `#ffffff`  
- **Accents**: `#e7e8ec`, `#adadad`

---

## 🛠 Folder Structure

```
Ride-Sharing-Insights/
│
├── data/
│   ├── raw/                # Original Kaggle files
│   ├── processed/          # Cleaned & downsampled files
│
├── output/
│   ├── visualizations/     # PNG screenshots of dashboards
│   ├── base_hourly_rides.csv
│   ├── base_total_rides.csv
│   ├── surge_hourly_demand.csv
│   └── uber_sampled_cleaned.csv
│
├── notebooks/
│   └── ride_sharing_analysis.ipynb
│
├── dashboard/
│   └── RideSharingInsights.pbix   # Power BI file (if public)
│   └── powerbi_screenshots/
│       └── page1_daily_overview.PNG
│
├── requirements.txt
└── README.md
```

---

## 🔍 Key Insights

- 🚨 **Peak demand** occurs during 5 PM–8 PM (evening commute)
- 📈 **Friday** sees the highest surge-like periods
- 🏢 Base **B02598** leads in total rides
- 📊 Clear patterns support dynamic pricing and fleet optimization

---

## 💡 Future Improvements

- Analyze full-year data for seasonal trends
- Integrate geographic analysis (borough-level mapping)
- Include driver behavior metrics
- Apply forecasting models (e.g., Prophet, SARIMA)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/D1VYANSHx7877/ride-sharing-demand-forecasting.git
cd ride-sharing-demand-forecasting
```

### 2. Install Python Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook

Launch the Jupyter notebook:

```bash
jupyter notebook notebooks/ride_sharing_analysis.ipynb
```

### 4. Open the Power BI Dashboard

Open `RideSharingInsights.pbix` using Power BI Desktop to explore the interactive dashboard.

---

## 🙏 Acknowledgements

- 📊 Kaggle: Uber/FHV NYC Dataset
- 🎨 Uber Color Theme inspiration
- 💻 Built on a performance-constrained machine (Lenovo G50-80)

---

## 👨‍💻 Author

Made with 💻 and 📊 by **Divyansh Dhadhich**  
📧 divyanshdhadhich@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/divyansh-dhadhich)
