# 🏥 NHS Capacity Analysis

**Author:** Phil Best  
**Tools Used:** Python, pandas, seaborn, matplotlib

## 📌 Objective

To assess whether the NHS has sufficient appointment capacity to meet national demand, and to explore how healthcare resources are currently being utilized. The analysis supports decision-making around staffing, scheduling, and service delivery.

---

## 📊 Data Sources

- `appointments_regional.csv` — Monthly appointment data by region
- `actual_duration.csv` — Daily appointment duration data
- `national_categories.xlsx` — Appointment categories and context

Data was sourced from NHS England and included appointment volume, attendance, mode, professional type, and service setting.

---

## 🔎 Key Analytical Steps

### 🔹 Data Cleaning
- Converted date formats and standardized column names
- Removed outliers, including COVID-impacted months and weekend data
- Filtered weekday data to reduce skew from low-volume days

### 🔹 Exploratory Analysis
- Monthly and daily appointment trends
- Distribution across regions, service settings, and professional types
- Attendance rates, face-to-face vs remote ratios, and booking delays

### 🔹 Visualisation
- Line plots, boxplots, bar charts, and stacked bar charts
- NHS-compliant colour palette and design principles (FT Visual Vocabulary)

---

## 📈 Insights & Findings

- **Weekday demand exceeds NHS capacity** (1.2M appointments/day) in nearly every month, especially Mon–Thu
- **GPs handle 52% of appointments**, averaging well above safe daily limits
- **General Practice** accounts for 90% of all appointments
- Seasonal spikes (e.g., flu vaccines) strain resources further
- ~5% of appointments are lost to no-shows

---

## 💡 Recommendations

### Business
- Hire ~2,640 more FTE staff to meet weekday demand
- Extend GP availability over weekends
- Launch flu programmes earlier to avoid peak clashes
- Reduce no-shows via incentives or penalties

### Analytical
- Standardise data entry across services
- Explore GP workforce trends and retention
- Develop localised capacity models by region

---

## 📂 Files in This Repository

- `nhs_capacity_analysis.ipynb` — Full Python notebook
- `actual_duration.csv` — Raw data
- `appointments_regional.csv` — Raw data
- `national_categories.xlsx` — Categorical definitions
- `README.md` — You are here

---

📌 *This project was completed as part of the LSE Data Analytics Career Accelerator.*
