# 🦀 King Crab Population Health Analysis Using Tableau

## 📌 Project Overview

This project analyzes the health, growth patterns, and commercial viability of King Crab populations in Alaskan waters using Tableau. The objective was to evaluate population sustainability, identify biological health indicators, and assess harvesting potential through data visualization and exploratory data analysis (EDA).

The analysis was conducted using data collected during 2018 and 2019, containing over 4,000 observations of King Crabs with measurements related to size, weight, sex classification, and health indicators.

---

## 🎯 Business Problem

Marine biologists and fisheries management agencies require data-driven insights to ensure sustainable harvesting practices while maintaining healthy crab populations.

This project aims to:

- Assess the overall health of King Crab populations
- Identify growth and aging patterns
- Evaluate commercial harvesting viability
- Analyze market quality indicators
- Support sustainable fisheries management decisions

---

## 📊 Dataset Information

**Dataset Size:** 4,177 records

**Study Period:** 2018–2019

### Variables Included

| Variable | Description |
|-----------|------------|
| Sex | Male, Female, Infant |
| Length | Crab length (mm) |
| Diameter | Crab diameter (mm) |
| Height | Crab height (mm) |
| Whole Weight | Total body weight (g) |
| Shucked Weight | Edible meat weight (g) |
| Sell Weight | Marketable weight (g) |
| Spots | Age-related indicator (2018 only) |

---

## 🛠 Tools & Technologies

- Tableau
- Microsoft Excel
- Data Visualization
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Statistical Analysis

---

## 🧹 Data Cleaning & Preprocessing

Several data quality issues were identified and addressed before analysis:

### Data Quality Checks

- Removed invalid sex classifications
- Handled missing values using median imputation
- Removed physically impossible measurements
- Detected and removed outliers
- Corrected weight inconsistencies
- Standardized variables using normalization techniques

### Final Dataset

- Initial Records: **4,177**
- Cleaned Records: **4,092**

---

## 📈 Analysis Performed

### 1. Correlation Analysis

Analyzed relationships between:

- Length vs Diameter
- Length vs Whole Weight
- Whole Weight vs Shucked Weight

**Key Finding:**
Strong positive correlations were observed between physical dimensions and weight indicators, demonstrating consistent growth patterns across the population.

---

### 2. Population Health Assessment

Developed a weighted health score using:

- Length
- Diameter
- Height
- Whole Weight
- Shucked Weight

A weighted-average approach was implemented to classify crabs into health and size categories.

---

### 3. Aging Pattern Analysis

Used spot count as an age-related indicator to evaluate maturity levels across:

- Male Crabs
- Female Crabs
- Infants

**Key Finding:**
Spot counts increased consistently with size categories, indicating normal aging and development patterns.

---

### 4. Meat Yield Analysis

Calculated Meat Yield:

```text
Shucked Weight / Whole Weight
```

This metric was used to assess:

- Nutritional condition
- Growth efficiency
- Overall biological health

**Key Finding:**
Average meat yield remained consistent across the population, indicating healthy development.

---

### 5. Commercial Viability Assessment

Developed a commercial viability model to identify crabs suitable for harvesting.

Factors considered:

- Size
- Weight
- Health Score
- Biological Maturity

**Key Finding:**

- Approximately 70% of adult crabs were classified as commercially viable.
- Population structure supports sustainable harvesting practices.

---

### 6. Market Quality Analysis

Analyzed the relationship between:

```text
Sell Weight / Shucked Weight
```

to understand market value and processing efficiency.

**Key Finding:**
Market quality varied by size category, providing insights for optimizing harvesting strategies.

---

## 📌 Key Insights

### Population Sustainability

✅ Stable population structure across years

✅ Healthy distribution of males, females, and juveniles

✅ Strong evidence of ongoing reproduction

### Biological Health

✅ Strong growth correlations

✅ Healthy condition index distribution

✅ No major signs of disease-related abnormalities

### Commercial Potential

✅ High proportion of harvestable crabs

✅ Strong market value indicators

✅ Sustainable harvesting opportunities

---

## 📊 Dashboard Features

The Tableau dashboard includes:

- Data Quality Assessment
- Correlation Analysis
- Population Distribution
- Health Scoring Model
- Aging Pattern Heatmaps
- Commercial Viability Analysis
- Market Quality Visualizations

---

## 📷 Dashboard Preview

### Correlation Analysis

![Correlation Dashboard](https://github.com/DevangiDodiya-DA/king-crab-population-health-analysis/blob/main/Correlation%20Dashboard.png)

### Population Health Dashboard

![Health Dashboard](https://github.com/DevangiDodiya-DA/king-crab-population-health-analysis/blob/main/Health%20Dashboard.png)

### Commercial Viability Dashboard

![Commercial Dashboard](https://github.com/DevangiDodiya-DA/king-crab-population-health-analysis/blob/main/Commercial%20Dashboard.png)

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Visualization
- Tableau Dashboard Development
- Exploratory Data Analysis
- Statistical Analysis
- Data Storytelling
- Business Intelligence
- Insight Generation

---

## 👨‍💻 Author

**Devangi Dodiya**

MSc Data Analytics

Aspiring Data Analyst | Tableau | SQL | Python | Power BI

Connect me: 
[LinkedIn](https://www.linkedin.com/in/devangidodiya/) || 
[GitHub](https://github.com/DevangiDodiya-DA)

---

## ⭐ Future Improvements

- Integrate environmental factors such as temperature and habitat conditions
- Develop predictive models for population sustainability
- Build interactive Tableau Public dashboards
- Apply machine learning techniques for harvesting recommendations
