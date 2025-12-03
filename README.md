🌍 Global Air Quality Analysis – 2023
Python (Google Colab) • Tableau • Data Cleaning • EDA • Dashboard

This project analyses the Global Air Quality 2023 dataset to uncover global pollution patterns, seasonal trends, weather–pollution relationships, and city-level disparities.
It includes data loading, cleaning, feature engineering, statistical exploration, and a fully interactive Tableau dashboard.

Completed as part of COMP11108 – Data Analysis & Visualisation (UWS).


🔎 Project Overview

The dataset contains 30,450+ daily pollution observations recorded across major global cities throughout 2023.
This project explores:

🌫 PM2.5 seasonal & monthly trends

🏙 Global pollution hotspots

🌦 Weather relationships (temperature, wind, humidity)

🏭 City-level distributions & rankings

🌍 Geographical inequalities in air quality

📊 Pollution category analysis



🛠️ Workflow Summary

1️⃣ Data Loading & Audit

Imported raw Kaggle dataset

Reviewed structure, completeness, and inconsistencies

Identified missing values and formatting issues


2️⃣ Data Cleaning & Feature Engineering

Standardised city name formatting

Converted date fields and corrected invalid entries

Removed duplicate city–date records

Applied hierarchical imputation (City–Month → City mean)

Engineered new analytical fields:

Year, Month, YearMonth

PM2.5 category (Good → Very Unhealthy)

Composite Pollution Index (z-score based)


3️⃣ Exploratory Data Analysis (EDA)

Summary statistics and distributions

Monthly pollution trends

Correlation analysis (pollutants vs weather)

City ranking by PM2.5

Heatmaps, boxplots, scatter plots, choropleths


4️⃣ Tableau Dashboard

The interactive dashboard includes:

KPI Cards: avg PM2.5, max PM2.5, unhealthy days

Pollution hotspot world map

City–Month heatmap

PM2.5 vs Temperature/Wind scatter plots

Seasonal trend lines

Top 10 most polluted cities

Fully interactive filters (city, country, month)



📈 Key Insights
🌡 1. Seasonal Variation

PM2.5 peaks during winter months (Jan–Mar) due to temperature inversion.

🌍 2. Geographic Inequality

Highest pollution: Beijing, Mumbai, Johannesburg, Dubai
Cleanest: London, Sydney, Berlin

🌬 3. Meteorological Influence

Higher temperature and wind speed correlate with lower PM2.5 levels.

📉 4. Right-Skewed Distribution

Many cities show extreme pollution spikes → high health-risk days.


🔗 Project Links

📓 Google Colab Notebook (EDA + Cleaning)	https://colab.research.google.com/drive/19HIYpk9msYK64HNTGiqBCnyRY3qNXHzd

📊 Interactive Tableau Dashboard	https://public.tableau.com/views/Global_AirQualityindex/Dashboard1

🗂 Raw Dataset (Kaggle)	https://www.kaggle.com/datasets/coffxc12/global-air-quality-2023-messy-from-waqi786

🧼 Cleaned Dataset (Google Drive)	https://drive.google.com/file/d/1J_VxKwlcuyDlx70Kr_dcLW8CrxLa3Umt/view

📄 Coursework Report (PDF)	(Add link here once uploaded)

👥 Team Contributions (Group Project)
Member	Contribution
Alish	Data selection, initial EDA, final report compilation
Rajeev	Data cleaning, missing value handling, descriptive statistics
Amit	Python visualisations
Sanjay	Tableau dashboard development
Sajan	Data storytelling, reflection, documentation

🧰 Technologies & Tools

Python (pandas, numpy, seaborn, matplotlib, scipy)

Google Colab

Tableau Public

Feature engineering, EDA, data cleaning, storytelling


🎯 Project Summary

This project demonstrates the complete data analysis lifecycle:

Raw messy dataset → cleaned structured data → EDA → insights → interactive dashboard

It showcases strong skills in:

Data cleaning & preprocessing

Exploratory data analysis

Visualisation & dashboard design

Interpreting environmental datasets

Communicating insights clearly
