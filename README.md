# Data_Analysis_Final_Project
University of the City of Buenos Aires

# Data Analysis Final Project - EasyJet Market Expansion Analysis

## 📋 Purpose of the Project
The goal of this project was to assist EasyJet, a multinational low-cost airline, in expanding its operations into Argentina's domestic flight market. Through advanced data analysis, we aimed to:
- Identify seasonal and monthly demand patterns.
- Detect peak days and times for interprovincial flights.
- Analyze air traffic between provinces to highlight high-volume destinations.

## 🔑 Key Insights/Findings
- **Seasonal Demand Trends:** Clear fluctuations in passenger demand across different seasons, aiding in capacity planning.
- **Peak Activity Periods:** Identification of peak days and times for flights, enabling optimized scheduling.
- **High-Traffic Provinces:** Highlighted provinces with the highest passenger volume to prioritize routes and focus marketing efforts.
- **Strategic Recommendations:** Suggestions to optimize pricing, scheduling, and route selection for increased market competitiveness and customer satisfaction.

## 🛠️ Tools and Methods Used
### **Data Processing**
- **ETL Workflow:** Manual CSV uploads were processed, integrating public datasets from [Datos.gob.ar](https://www.datos.gob.ar/dataset/transporte-lista-aeropuertos/archivo/transporte_eb54e49e-9a5a-4614-91f4-526c650d0105).
- **Data Cleaning:** Standardized column names, resolved null values, and ensured temporal consistency (UTC to UTC-3).
- **Transformation:** Combined datasets from 2019–2023, applied filtering for regular flights, and focused on flights with passenger data > 0.

### **Data Visualization**
- **Tableau Dashboard:** Interactive dashboard provided insights into demand trends, peak periods, and province-level traffic, enabling strategic decision-making. You can view the dashboard here:  
  [Tableau Dashboard - Vuelos Análisis](https://public.tableau.com/app/profile/micaela.dorado/viz/Vuelos_17311104748040/Anlisisdevuelos?publish=yes)

### **Programming and Libraries**
- **Python (Pandas):** For data preprocessing and transformation.
- **Time Zones:** Standardized time data to Argentina’s local timezone for analysis consistency.

## 🚀 Outcomes and Impact
- **Operational Efficiency:** Optimized flight schedules and fleet deployment based on demand.
- **Revenue Growth:** Price adjustments and targeted promotions led to better revenue management.
- **Customer Experience:** Enhanced service availability and tailored offerings for passenger needs.

## 📈 Recommendations for EasyJet
1. **Increase Flight Frequency:** Focus on high-demand routes and peak times.
2. **Dynamic Pricing:** Seasonal adjustments to maximize profitability.
3. **Marketing Campaigns:** Targeted advertising in regions of high potential growth.

---

## 🗂️ Large Files Storage
Due to GitHub's file size limitations, we encountered issues pushing large files to the repository. Therefore, the large files used in this project have been uploaded to Google Drive for easy access.

You can download the large files from the following link:

[Google Drive - Project Files](https://drive.google.com/drive/folders/1CF1FKISByTZDMYX3YNYeyY6xWZ7V1tN_?usp=drive_link)

---

### Contributors
This project was developed by Group 3 - Aprodatos:
- Micaela Rosa Dorado
- Guillermo German Jalil
- Nicolás Paul Ramírez Moreale
- Gabriel Iván Jofre
- Alan Aramayo
- Camila Funes

---

Feel free to explore the project and dashboard! Your feedback is welcome.

