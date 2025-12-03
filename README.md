# 🌍 Global Air Quality Analysis – 2023

**Python (Google Colab) • Tableau • Data Cleaning • EDA • Dashboard**

This project analyses the Global Air Quality 2023 dataset to uncover global pollution patterns, seasonal trends, weather–pollution relationships, and city-level disparities. It covers the full data analysis workflow: data loading, cleaning, feature engineering, exploratory analysis, and a fully interactive Tableau dashboard.  

Completed as part of **COMP11108 – Data Analysis & Visualisation (UWS)**.

---

## **Dataset**

- **Global Air Quality 2023**: Contains 30,450+ daily pollution observations recorded across major global cities throughout 2023.  
- Key variables include: PM2.5, PM10, CO, NO2, O3, temperature, humidity, wind speed, city, and date.

---

## **Project Objectives**

- Analyze **PM2.5 seasonal and monthly trends**  
- Identify **global pollution hotspots**  
- Explore **weather–pollution relationships** (temperature, wind, humidity)  
- Examine **city-level disparities and rankings**  
- Assess **geographical inequalities in air quality**  
- Categorize pollution levels for public health insights  

---

## **Workflow Summary**

### **1️⃣ Data Loading & Audit**
- Imported raw Kaggle dataset  
- Reviewed data structure, completeness, and inconsistencies  
- Identified missing values and formatting issues  

### **2️⃣ Data Cleaning & Feature Engineering**
- Standardized city name formatting  
- Converted date fields and corrected invalid entries  
- Removed duplicate city–date records  
- Applied hierarchical imputation (City–Month → City mean)  
- Engineered analytical fields: Year, Month, YearMonth, PM2.5 category (Good → Very Unhealthy), Composite Pollution Index (z-score based)  

### **3️⃣ Exploratory Data Analysis (EDA)**
- Summary statistics and distributions  
- Monthly pollution trends  
- Correlation analysis between pollutants and weather variables  
- City ranking by PM2.5  
- Visualizations: heatmaps, boxplots, scatter plots, choropleths  

### **4️⃣ Tableau Dashboard**
- **KPI Cards**: average PM2.5, max PM2.5, unhealthy days  
- **Pollution Hotspot Map**: global visualization of city pollution levels  
- **City–Month Heatmap**: monthly trends per city  
- **PM2.5 vs Weather Scatter Plots**: temperature, wind, humidity  
- Seasonal trend lines and top 10 most polluted cities  
- Fully interactive filters (city, country, month)  

---

## **Key Insights**

1. **Seasonal Variation**: PM2.5 peaks during winter months (Jan–Mar) due to temperature inversion.  
2. **Geographic Inequality**: Highest pollution: Beijing, Mumbai, Johannesburg, Dubai | Cleanest: London, Sydney, Berlin  
3. **Meteorological Influence**: Higher temperature and wind speed correlate with lower PM2.5 levels  
4. **Right-Skewed Distribution**: Many cities experience extreme pollution spikes → high health-risk days  

---

## **Project Links**

- **Google Colab Notebook (EDA + Cleaning)**: [Link](https://colab.research.google.com/drive/19HIYpk9msYK64HNTGiqBCnyRY3qNXHzd)  
- **Interactive Tableau Dashboard**: [Link](https://public.tableau.com/views/Global_AirQualityindex/Dashboard1)  
- **Raw Dataset (Kaggle)**: [Link](https://www.kaggle.com/datasets/coffxc12/global-air-quality-2023-messy-from-waqi786)  
- **Cleaned Dataset (Google Drive)**: [Link](https://drive.google.com/file/d/1J_VxKwlcuyDlx70Kr_dcLW8CrxLa3Umt/view)  
- **Coursework Report (PDF)**: [A6 (1).docx](https://github.com/user-attachments/files/23907461/A6.1.docx)
  

---

## **Team Contributions**

| Member  | Contribution |
|---------|-------------|
| Alish   | Data selection, initial EDA, final report compilation |
| Rajeev  | Data cleaning, missing value handling, descriptive statistics |
| Amit    | Python visualizations |
| Sanjay  | Tableau dashboard development |
| Sajan   | Data storytelling, reflection, documentation |

---

## **Technologies & Tools**

- **Python**: pandas, numpy, seaborn, matplotlib, scipy  
- **Google Colab**: for coding and analysis  
- **Tableau Public**: for interactive dashboards  
- Feature engineering, data cleaning, EDA, visualization, storytelling  

---

## **Project Summary**

This project demonstrates the **full data analysis lifecycle**:  

**Raw messy dataset → Cleaned structured data → EDA → Insights → Interactive Dashboard**  

It highlights strong skills in:  
- Data cleaning & preprocessing  
- Exploratory data analysis  
- Visualization & dashboard design  
- Interpreting environmental datasets  
- Communicating insights effectively  
