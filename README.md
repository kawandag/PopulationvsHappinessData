# 🌍 World Happiness Index: A Cross-Metric Analysis

This project explores how the **World Happiness Index (WHI)** correlates with a range of important socioeconomic, environmental, and political indicators. The goal is to understand whether happiness levels across countries can be explained or predicted by other measurable factors such as internet usage, CO₂ emissions, governance, and more.

---

## 🖥️ Presentation Slide Deck  
View the complete project presentation:  
[**World Happiness Index Slide Deck**](https://docs.google.com/presentation/d/e/2PACX-1vRaShmeR9hyph6LR_Dy3nwkJRifTp3Cn5e--SofeIQF-6j4lf3wjiqwQew3IU1zcDEnOisMorLPY35P/pub?start=true&loop=false&delayms=3000)

---

## 👥 Team Members

- Di Gibson  
- Hanah Kwon  
- Hari Somayajula  
- Kawanda Gray  
- Ramirra Marshall  
- Ricardo Mora

---

## 📁 Project Structure

### 🗂️ Data Preparation Notebooks

These notebooks consolidate and clean the World Happiness Report (WHR) data:

- **`GeWhRData.ipynb`**  
  Aggregates WHR data across multiple years into a single Excel file (`WHRData`) for analysis.

- **`WHR_CountryCleanup.ipynb`**  
  Standardizes and cleans country names and formats for consistency across datasets.

---

### 📊 Analytical Modules

Each subdirectory contains a Jupyter notebook that analyzes the correlation between WHI and another key metric:

#### 🌐 Internet Usage
- **`WHI_and_internet_Usage/InternetuseAnalysis.ipynb`**  
  Compares WHI with internet penetration (% of population using the internet).

#### 🧭 Latitude & Longitude
- **`Long_lat/Project 1 - World Happiness Long & Lat.ipynb`**  
  Explores geographic patterns in happiness by hemisphere and coordinates.

#### 🌿 CO₂ Emissions & Energy Consumption
- **`CO2 Emissions Analysis/CO2 Emissions.ipynb`**  
  Examines the relationship between WHI, CO₂ emissions, and energy usage.

#### 🏙️ Population Density
- **`population density/Project 1_PopulationvsHappinessData.ipynb`**  
  Analyzes how densely populated countries compare in happiness rankings.

#### 🚰 Water Supply & Sanitation
- **`watersanitation/waterSanitationVsWHI.ipynb`**  
  Investigates the impact of water access and sanitation on happiness levels.

#### 🍽️ Consumer Food Prices
- **`Consumer Price Index Analysis/WHIvsFoodPrices.ipynb`**  
  Evaluates how fluctuations in consumer food prices relate to WHI.

#### 🏛️ Governance Metrics
- **`Governance Metrics Analysis/HappinessIndexVsGovernanceMetrics.ipynb`**  
  Assesses correlations between WHI and political indicators such as government effectiveness, corruption perception, and rule of law.

---

## 📌 Summary

This multi-dimensional analysis offers insights into how various global indicators may influence or reflect a country’s happiness. The project leverages data science tools such as **Pandas**, **Matplotlib**, and **Seaborn**, and is structured for modular exploration of individual metrics.

---

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook
- Google Slides (for presentation)
- Excel (for consolidated WHR data)
