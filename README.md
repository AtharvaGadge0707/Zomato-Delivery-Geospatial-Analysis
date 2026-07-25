# Zomato Delivery Data Analysis

## 📌 Project Overview
This is a Power BI dashboard built to analyze Zomato delivery data. The goal of this project was to take a raw, messy dataset, clean up the errors, and build an interactive dark-mode dashboard to see exactly what causes delivery delays.

## 🚀 Key Features
* **Data Cleaning:** Filtered out broken GPS coordinates (like locations appearing in the middle of the ocean) so the maps only show accurate deliveries within India.
* **Missing Data:** Left naturally missing values (like unrecorded order times) blank in the exported CSV so they can be properly handled later in a Python environment.
* **Geospatial Maps:** Used exact latitudes and longitudes to map out restaurant and delivery locations.
* **Trend Tracking:** Built visuals to show how traffic density, vehicle type, weather, and driver age impact the average delivery time.

## 🛠️ Tools Used
* **Power BI:** Used for building the dashboard, filtering data, and creating interactive maps.
* **Excel / CSV:** Used to format and export the final cleaned dataset.

## 📂 Repository Structure
* `data/` - Contains the raw dataset and the cleaned `.csv` file.
* `dashboard/` - Contains the final Power BI (`.pbix`) file and a PDF report.
* `images/` - Screenshots of the project.


### 2. Location & Map Dashboard
![Geospatial Map](images/page2_maps.png)
