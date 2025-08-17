
# Applied Statistics with RStudio  
Statistical modelling and analysis using R — Linear Regression & Two-Way ANOVA  

## 📌 Project Overview  
This repository contains my **Applied Statistics (STAT2170)** assignment, where I applied statistical modelling techniques in RStudio. The project consists of two main parts:  

1. **Real Estate Pricing Analysis (Multiple Linear Regression)**  
   - Built regression models to predict housing prices based on predictors such as size, number of bedrooms, and age.  
   - Conducted hypothesis tests and confidence intervals for coefficients.  
   - Evaluated model assumptions (linearity, constant variance, normality) with residual diagnostics.  
   - Selected the best parsimonious model using adjusted R² and hypothesis testing.  

2. **Freshness Study (Two-Way ANOVA)**  
   - Analysed the effect of **packaging type (Paper vs Plastic)** and **storage condition (Refrigerated vs Room Temperature)** on product freshness.  
   - Tested for interaction effects between packaging and storage.  
   - Validated model assumptions using diagnostic plots.  
   - Found strong main effects of both factors on freshness, but no significant interaction.  

---

## 🛠️ Tools & Technologies  
- **RStudio**  
- **R Libraries**:  
  - `stats` (linear models, ANOVA)  
  - `ggplot2` (visualisation)  
  - `dplyr` (data wrangling)  

---

## 📂 Repository Structure  
-  assignment_report.pdf # Final PDF output
-  README.md # Project documentation
---

## 🔑 Key Insights  
- **Real Estate Regression**: Property size is the strongest predictor of price, while age was not significant. Final model achieved an adjusted R² ≈ 0.62.  
- **Freshness ANOVA**: Both packaging and storage significantly affect freshness, but no interaction effect was found.  

---

## 🚀 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/applied-statistics-rstudio.git
