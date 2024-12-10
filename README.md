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
- **Tableau Dashboard:** Interactive dashboard provided insights into demand trends, peak periods, and province-level traffic, enabling strategic decision-making.

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
3. **Marketing Campaigns:** Targeted advertising in underrepresented but high-potential regions.
4. **Ongoing Analysis:** Continuous monitoring to adapt to evolving market trends.

## 📂 Data Source
The dataset was sourced from the official [Datos.gob.ar](https://www.datos.gob.ar), providing detailed records on domestic flights in Argentina.

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
