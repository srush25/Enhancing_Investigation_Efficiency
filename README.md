# Enhancing_Investigation_Efficiency


This project focuses on improving digital forensic investigations using machine learning, dynamic data generation, and real-time visualization. It analyzes behavioral and network traffic datasets to classify threats, calculate threat scores, and present actionable insights through a live dashboard.



## 🚀 Features

- 🧠 **Machine Learning-Based Threat Classification**
- 🔐 **Threat Scoring System**
- 📊 **Real-Time Visualization Dashboard using Tableau**
- 🛠️ **Dummy Data Generator for Dynamic Testing**
- 🧾 **Google Sheets as Lightweight Data Warehouse**
- 🌐 **Web Deployment for Live Monitoring**

---

## 📂 Datasets Used

### 1. **Supervised Behavioral Dataset**
- `_id`
- `inter_api_access_duration(sec)`
- `api_access_uniqueness`
- `sequence_length(count)`
- `vsession_duration(min)`
- `ip_type`
- `num_sessions`
- `num_users`
- `num_unique_apis`
- `source`
- link of datasheet to view: https://docs.google.com/spreadsheets/d/1yluIXEu_XRjAaaotMhQkdW01QqPiiFWnmlhzJy_CDgA/edit?gid=0#gid=0
- run Data dummy_data_API_generation.py to generate the dummy data

### 2. **Network Traffic Dataset**
- `Duration`
- `Protocol`
- `SourceIP`
- `DestinationIP`
- `SourcePort`
- `DestinationPort`
- `PacketCount`
- `ByteCount`
- `Label`
- link of datasheet to view: https://docs.google.com/spreadsheets/d/1toiier58qqNEnMRIRMisAtXSwovlnpxRWAuaKIXuYZk/edit?gid=0#gid=0 
- run Data dummydata.py to generate the dummy data
---

## 🧪 Methodology

1. **Data Preprocessing:** Cleaning and formatting the datasets.
2. **Dummy Data Generation:** Python-based simulation of real-time data.
3. **ML Model Training:** Classification using Decision Trees / Random Forests.
4. **Threat Scoring:** Output threat score for each session or packet flow.
5. **Dashboarding:** Tableau connected to Google Sheets for live visualization.
6. **Deployment:** Integrated into a website for investigator access.

---

## 📊 Visual Insights

- Threat Score by Byte Count
- Session Complexity
- Threat Contribution by Protocol
- Threat Score by IP Type
- Threat Score Over Time
- API Access Behavior
- Network Traffic Volume
- Protocol-Wise Distribution
- Threat Score Frequency
- ML Classification Filters

---

## 🛠️ Tools & Technologies

- Python
- Pandas, Scikit-learn
- Google Sheets API
- Tableau
- HTML/CSS for Web Deployment


---


