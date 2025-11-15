# World Happiness Report – Data Analysis

This project analyzes whether economically wealthier countries tend to report higher levels of happiness, with a specific focus on the Nordic region.

---

## 🧩 Research Questions
1. Do countries with higher **GDP per capita** report higher **happiness scores**?
2. Does **social support** also impact happiness?
3. Are the **Nordic countries** statistically different from other regions?

---

## 📊 Dataset
- Source: World Happiness Report (year: 2019)
- Variables used:
  - `GDP_per_capita`
  - `Social_support`
  - `Score` (happiness)
  - `Country_or_region`

---

## 🔧 Methods
- Correlation analysis  
- Simple and multiple linear regression  
- Regional comparison (Nordic vs Others)  
- Visualization using **ggplot2**

---

## 📈 Key Findings

### 1. GDP and Happiness (Correlation)
**Correlation coefficient:** `r = 0.79`  
→ Strong positive relationship.

### 2. Regression Models

#### Model 1: Happiness ~ GDP  
- R² = 0.63
- GDP is a strong predictor of happiness.

#### Model 2: Happiness ~ Social Support  
- R² = 0.60
- Social support alone also strongly predicts happiness.

#### Model 3: Combined Model  
- R² = 0.70 (highest)
- Both GDP and social support are significant predictors.

---

## 📉 Visualizations

### GDP vs Happiness
![GDP vs Happiness](plots/gdp_happiness.png)

### Model Comparison
![Model Summary](plots/model1.png)

*(Upload your actual images to this folder and use the filenames accordingly)*

---

## 📜 Files

| File | Description |
|------|-------------|
| `code.R` | Full R script used for cleaning, modeling, and plotting |
| `plots/` | Folder containing all exported images |
| `report.pdf` | Optional formatted report |

---

## 💡 Conclusion
Both **economic prosperity** and **social support networks** significantly influence national happiness levels.  
Nordic countries distinguish themselves by scoring **high in both factors**, explaining their consistently high happiness rankings.

---

## 🔄 Reproducibility
This project is fully reproducible.  
All code and data files are included in this directory.


