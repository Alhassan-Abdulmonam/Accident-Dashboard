# 🚗💥 Power BI Accident Analysis Dashboard

## 📌 Project Overview
This project presents an **interactive Power BI dashboard** that analyzes traffic accident data based on various factors such as **weather conditions, road conditions, accident causes, casualties, and vehicle involvement**. The goal is to provide **data-driven insights** that can help policymakers, traffic management authorities, and researchers understand accident trends and make informed decisions to improve road safety.

## 🎯 **Key Features**
🔹 **Accident Statistics KPIs**: Displays total accidents, casualties, accidents per day, and total vehicles involved.  
🔹 **Time-Based Analysis**: Analyzes accident trends over time (monthly/yearly).  
🔹 **Geospatial Insights**: Uses an interactive map to display accident locations.  
🔹 **Accidents by Cause**: Identifies primary causes such as **speeding, distracted driving, and mechanical failure**.  
🔹 **Weather & Road Conditions Impact**: Compares accident counts across different **weather conditions (rain, fog, snow, etc.)** and **road conditions (wet, icy, under construction, etc.)**.  
🔹 **Filter & Slicer Options**: Users can filter data based on **date, accident cause, weather, road condition, and location** for in-depth analysis.  
🔹 **Advanced DAX Measures**: Uses **Power BI DAX functions** for custom calculations and insights.
🔹 **Drill-Through & Tooltip Insights**: Enables users to explore accident details dynamically.

---

## 📂 **Files in Repository**

| File Name                | Description                                      |
|--------------------------|--------------------------------------------------|
| `Accident_Dashboard.pbix` | The **Power BI file** containing the dashboard. |
| `dashboard-image.png`     | Screenshot of the dashboard for preview.       |
| `dataset.csv` *(optional)* | Sample dataset used for analysis.              |
| `README.md`              | Documentation of the project.                   |

---

## 🛠️ **Installation & Setup Guide**

### **Prerequisites**
Before using this project, ensure you have the following installed:
✅ **Power BI Desktop** – [Download Here](https://powerbi.microsoft.com/desktop/)  
✅ **Git (optional, for version control)** – [Download Here](https://git-scm.com/)  
✅ **Dataset (if needed)** – A CSV/Excel file containing accident data.  

### **Steps to Open the Dashboard**

1️⃣ **Clone the Repository** (if using Git):  
```bash
git clone https://github.com/yourusername/Accident-Dashboard.git
cd Accident-Dashboard
```

2️⃣ **Download the `.pbix` file** directly from GitHub if not using Git.  
3️⃣ **Open Power BI Desktop**.  
4️⃣ **Click "Open File"** and select `Accident_Dashboard.pbix`.  
5️⃣ **Interact with the dashboard** by applying filters and analyzing the data.

---

## 📊 **Dataset Description**

The dataset used in this project contains traffic accident records with key attributes such as:

| Column Name           | Description                                           |
|---------------------- |------------------------------------------------------|
| `Accident ID`        | Unique identifier for each accident.                 |
| `Date`               | The date of the accident.                            |
| `Time`               | The time at which the accident occurred.            |
| `Location`           | The city or area where the accident took place.     |
| `Latitude & Longitude` | Geographic coordinates of the accident.             |
| `Weather Condition`  | Weather at the time (e.g., Clear, Rain, Snow, Fog).  |
| `Road Condition`     | Condition of the road (e.g., Dry, Wet, Icy).         |
| `Vehicles Involved`  | Number of vehicles involved in the accident.         |
| `Casualties`         | Number of people injured or killed.                 |
| `Cause`             | Primary cause of the accident (e.g., Drunk Driving, Speeding). |

---

## 📊 **Dashboard Visuals & Insights**

### **1️⃣ Key Performance Indicators (KPIs)**
* **Total Accidents** – Displays the total number of recorded accidents.
* **Total Casualties** – Sum of all fatalities and injuries.
* **Accidents Per Day** – Shows the average number of accidents occurring daily.
* **Total Vehicles Involved** – Total count of all vehicles in recorded accidents.

### **2️⃣ Accident Trends Over Time** _(Line Chart)_
* Analyzes the increase or decrease in accidents over the years.
* Helps identify peak accident months for further investigation.

### **3️⃣ Accident Distribution by Location** _(Map Visualization)_
* Uses **latitude & longitude** data to pinpoint accident hotspots.
* Helps in identifying high-risk areas for safety improvements.

### **4️⃣ Accidents by Cause** _(Bar Chart)_
* Displays the most common causes of accidents (e.g., Speeding, Reckless Driving).
* Allows users to filter and analyze specific accident causes.

### **5️⃣ Road Condition vs. Accidents** _(Stacked Bar Chart)_
* Examines accident distribution based on road conditions.
* Identifies hazardous road conditions leading to more accidents.

### **6️⃣ Weather Conditions Impact on Accidents** _(Column Chart)_
* Compares accident frequency across **rain, snow, fog, and clear weather**.
* Helps in understanding seasonal accident trends.

### **7️⃣ Custom Insights & Predictive Analysis**
* Uses **DAX calculations** to generate predictive insights.
* Examines correlation between accident causes and fatalities.
* Implements **custom tooltips** for an interactive data exploration experience.

---

## 🔥 **Advanced Features & Enhancements**

🚀 **Dynamic Filters & Slicers**: Interactive filtering by date, accident cause, and road/weather conditions.  
🚀 **Drill-Through Analysis**: Click on accident categories to view detailed reports.  
🚀 **Custom DAX Measures**: Power BI **DAX functions** were used to calculate accident trends and KPIs.  
🚀 **Forecasting & Trend Analysis**: Predicting future accident trends using historical data.  
🚀 **Future Improvements**:
* Incorporating **Machine Learning models** to predict accident-prone zones.
* Adding **real-time accident data integration**.
* Improving **UI/UX design** with Power BI themes and advanced visuals.

---

## 📜 **License**
This project is licensed under the **MIT License**. You are free to use, modify, and distribute it.

## 🤝 **Contributions**
Contributions are welcome! If you have suggestions or want to improve the dashboard, feel free to fork the repository and submit a pull request.

---

## 🌎 **Connect With Me**
📧 Email: [My Gmail](alhassanabdulmonam@gmail.com) 
🔗 LinkedIn: [My LinkedIn Profile](www.linkedin.com/in/hassan-abdulmonam-)   
💻 GitHub: [My GitHub Profile](https://github.com/Alhassan-Abdulmonam)

---

## 📷 **Dashboard Preview**
![Dashboard Screenshot](https://github.com/Alhassan-Abdulmonam/Accident-Dashboard/blob/main/Accident-Dashboard.png)

---

### **🚀 Next Steps for You:**
1️⃣ **Upload this README.md file to your GitHub repository.**  
2️⃣ **Add your `.pbix` Power BI file and a dataset if applicable.**  
3️⃣ **Take a better screenshot of your dashboard and replace `dashboard-image.png`.**  
4️⃣ **Update links (LinkedIn, GitHub, email) in the README file.**  
5️⃣ **Share your GitHub repository! 🎉**
