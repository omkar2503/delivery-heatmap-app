# 📍 Delivery Inefficiency Heatmap for Tier-2 Indian Cities

This project analyzes delivery performance across Nagpur and Nashik to identify failure hotspots and suggest optimal hub locations.

---

## 🔍 Problem Statement

In Tier-2 Indian cities, delivery delays and failures often result from poor hub placement and logistical challenges. This project uses delivery records to map and cluster inefficient zones.

---

## 📦 Dataset

- 3,000 simulated records for Nagpur & Nashik
- Fields: `Package ID`, `Pickup Time`, `Delivery Time`, `Status`, `Pincode`, `Latitude`, `Longitude`, `Delay Reason`

---

## 📊 Analysis Highlights

- Aggregated failures and success rate per pincode
- Calculated average delivery times
- Visualized delivery inefficiency using **Folium heatmaps**
- Applied **KMeans clustering** to suggest new delivery hub zones

---

## 🗺️ Visual Outputs

- **Heatmap of Delivery Failures**
- **Clustered Delivery Zones**


![image](https://github.com/user-attachments/assets/6936d0c1-c599-4a91-8792-a75e259645ee)


![image](https://github.com/user-attachments/assets/96278f45-1c6f-4db2-9791-56f2d5b38eaf)


- **Suggested Hub Locations**

![image](https://github.com/user-attachments/assets/fb913c0f-2f3d-418b-a4e7-ed6a2dfdf487)


![image](https://github.com/user-attachments/assets/6f680b15-52fb-443b-8ab0-1ca94665799d)




---

## 🧪 Tools Used

- Python, Pandas, NumPy, Scikit-learn
- Geopandas, Folium, Jupyter, Google Colab

---

## 🚀 Project Outcomes

- Identified 2 major failure zones in both cities
- Suggested 3+ optimal hub locations using KMeans clustering
- 78% of delivery issues were localized to <40% of zones

---

## 📂 Folder Structure
data/ → Contains raw & processed CSVs

notebooks/ → All Colab/Python notebooks

images/ → Screenshots of maps/plots

README.md → Project documentation

requirements.txt → Python environment dependencies


---

## 🧠 What I Learned

- Geo-based clustering using latitude/longitude
- Interpreting delivery status for operational insight
- Interactive map creation with Folium
