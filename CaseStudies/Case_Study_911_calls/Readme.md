# 📞 911 Calls Data Analysis Project

## 📌 Project Overview
This project involves an exploratory data analysis (EDA) of **911 emergency call records** to uncover patterns, trends, and insights related to emergency incidents. The dataset captures information such as the reason for the call, time of the call, and location details.

The goal of this study is to understand:
- The most common reasons for 911 calls
- Temporal trends (daily, monthly, hourly)
- Geographic distribution of emergencies
- Relationships between time, location, and call types

---

## 📂 Dataset Description
The dataset contains the following key fields:

| Column Name | Description |
|------------|------------|
| `lat` | Latitude of the incident |
| `lng` | Longitude of the incident |
| `desc` | Description of the emergency |
| `zip` | Zip code |
| `title` | Emergency type and sub-type |
| `timeStamp` | Date and time of the call |
| `twp` | Township |
| `addr` | Address |
| `e` | Dummy variable (always 1) |

The data originates from **public 911 call records** and is commonly used for data analysis and visualization practice.

---

## 🛠️ Technologies Used
- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib** – basic plotting
- **Seaborn** – statistical visualizations
- **Jupyter Notebook**

---

## 🔍 Key Analysis Steps

### 1️⃣ Data Loading & Cleaning
- Loaded dataset using Pandas
- Converted timestamps into `datetime` objects
- Extracted useful time-based features (hour, day, month)
- Handled missing or inconsistent values

### 2️⃣ Feature Engineering
- Extracted **emergency reason** (EMS, Fire, Traffic) from the `title` column
- Created new columns:
  - Hour
  - Month
  - Day of Week

### 3️⃣ Exploratory Data Analysis (EDA)
- Most common reasons for 911 calls
- Call volume by:
  - Hour of the day
  - Day of the week
  - Month
- Geographic distribution of emergencies
- Heatmaps and count plots for pattern discovery

### 4️⃣ Visualization
- Count plots for call reasons
- Line plots for temporal trends
- Heatmaps for day vs hour relationships
- Clustered insights using Seaborn

---

## 📊 Key Insights
- **EMS-related calls** are the most frequent emergency type
- Call volume peaks during **daytime hours**
- Certain days of the week show consistently higher emergency activity
- Seasonal trends indicate variation in call frequency across months

---


---

## ▶️ How to Run the Project
Clone the repository:
bash
git clone https://github.com/Lakeshprabhu/911-calls-analysis.git



