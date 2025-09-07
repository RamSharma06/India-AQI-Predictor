# India AQI Analysis  

##  Overview  
This project was carried out at the **Defence Research and Development Organisation (DRDO)** to analyze the **Air Quality Index (AQI)** across India. The study focused on identifying spatial and temporal pollution patterns, assessing pollutant contributions, and applying statistical and machine learning techniques for AQI prediction.  

---

##  Objectives  
- Analyze AQI variations across major Indian cities and states.  
- Identify dominant pollutants influencing AQI values.  
- Examine seasonal patterns in AQI (summer, monsoon, winter).  
- Develop visualizations for clear interpretation of AQI trends.  
- Build predictive models to estimate AQI from pollutant concentrations.  

---

##  Dataset  
- **Source:** Central Pollution Control Board (CPCB), Open Government Data (OGD) Platform India.  
- **Timeframe:** 2015 onwards.  
- **Features:**  
  - Location (city/state)  
  - AQI value and category (Good, Satisfactory, Moderate, Poor, Very Poor, Severe)  
  - Pollutant concentrations: PM₂.₅, PM₁₀, NO₂, SO₂, CO, O₃, NH₃  
  - Date and time  

---

##  Methodology  

### 🔹 Data Collection & Preprocessing  
- Extracted AQI and pollutant data from CPCB datasets and APIs.  
- Cleaned missing/duplicate entries and standardized units.  
- Structured the dataset for analysis and visualization.  

### 🔹 Exploratory Data Analysis  
- Descriptive statistics to understand pollutant distributions.  
- Time-series analysis for temporal AQI variations.  
- Correlation analysis between AQI and individual pollutants.  

### 🔹 Visualization  
- Heatmaps showing AQI distribution across regions.  
- Seasonal trend analysis through line and bar charts.  
- Geospatial mapping of AQI hotspots.  
- Comparative pollutant contribution plots.  

### 🔹 Machine Learning  
- Regression models (Linear Regression, Random Forest) used for AQI prediction.  
- Feature importance ranking to identify key pollutants.  
- Evaluated models using R², MAE, and RMSE.  

---

##  Key Findings  
- Northern cities (Delhi, Kanpur, Lucknow) consistently showed **poor to severe AQI** levels.  
- **PM₂.₅ and PM₁₀** were identified as the most critical pollutants.  
- AQI spikes were most frequent in **winter months (Nov–Jan)** due to stubble burning and meteorological factors.  
- Southern and coastal cities generally reported **better AQI**, with occasional traffic and industrial impacts.  
- Predictive models demonstrated that AQI can be effectively estimated using **PM₂.₅, PM₁₀, and NO₂** as primary features.  

---

##  Tools & Technologies  
- **Programming Language:** Python  
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Plotly, Folium, Scikit-learn  
- **Environment:** Jupyter Notebook / Google Colab  

---

##  Future Work  
- Development of a **real-time AQI dashboard**.  
- Implementation of **deep learning models** (LSTM/GRU) for improved prediction accuracy.  
- Integration with **health datasets** to study AQI impact on respiratory diseases.  
- Long-term AQI forecasting under **climate change scenarios**.  


