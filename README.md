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

<img src="images/Heatmap of Delivery Failures - nagpur.png" width="600">
<img src="images/Heatmap of Delivery Failures - nashik.png" width="600">

- **Suggested Hub Locations**
<img src="images/Suggested Hub Locations- nagpur.png" width="600">
<img src="images/Suggested Hub Locations- nashik.png" width="600">

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

