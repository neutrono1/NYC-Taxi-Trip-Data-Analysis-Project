# NYC Taxi Trip Data Analysis Project

This project performs complete data cleaning, feature engineering, exploration, and visualization on NYC Taxi trip data using Python. It follows a structure similar to a typical data‑analysis GitHub project and is fully reproducible.

---
## Dataset

The dataset used in this project can be downloaded from Google Drive:

Download Link: https://drive.google.com/file/d/1EjhP1_2A_trKNy3wRctubCvSefCbMQQh/view?usp=sharing

After downloading, rename the file to train.csv and place it in the project folder following this:

## 📂 Project Structure

```
nyc_taxi_project/
│
├──.gitattributes
├──train.csv
├──.gitignore
├── analysis.py
├── README.md
├── sample_cleaned.csv # auto-generated
└── plots/
    ├── trip_duration_distribution.png
    ├── trips_by_hour.png
    ├── median_trip_duration_by_hour.png
    ├── distance_vs_duration_scatter.png
    ├── passenger_count_distribution.png
    ├── vendor_median_trip_duration.png
    └── correlation_matrix.png
```

---
## 📌 Project Goals

* Clean and preprocess raw NYC taxi trip data
* Engineer useful features such as:

  * Trip duration (minutes)
  * Trip distance (Haversine)
  * Pickup hour, day of week
* Explore taxi patterns and trends
* Visualize taxi behaviour using Matplotlib:

  * Trip duration distribution
  * Trips by hour
  * Trip distance vs duration
  * Passenger count distribution
  * Vendor comparison
  * Correlation heatmap
* Save all plots inside a `/plots` directory

---

## 🧰 Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**

---



## ▶️ How to Run the Project

### 1. Install required libraries

```bash
pip install pandas numpy matplotlib
```

### 2. Run the project

```bash
python analysis.py
```

### 3. View the visualizations

All generated graphs will appear inside the **plots/** folder.

---

## 📈 Visualizations Generated

* Taxi trip duration distribution (log-scaled)
* Number of trips by hour of day
* Median trip duration by hour
* Passenger count distribution
* Vendor performance comparison
* Trip distance vs duration (scatter)
* Correlation heatmap of numerical fields

---

## ✨ Next Possible Improvements

* Add ML model to predict trip duration
* Detect anomalies in long/short trips


---
