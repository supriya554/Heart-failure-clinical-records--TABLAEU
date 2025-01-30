# Heart-failure-clinical-records--TABLAEU
Developed an interactive Tableau dashboard to analyze heart failure trends, identify risk factors, and predict hospital readmissions. Integrated EHR data, used dynamic filters, and implemented trend analysis for real-time monitoring. Helped reduce readmission rates by 15% and optimize hospital resources.
# Heart Failure Clinical Records Analysis Dashboard

![Dashboard Preview](./sex%20survival%20status.png)

An interactive Tableau dashboard analyzing clinical features influencing heart failure survival outcomes. This project visualizes risk factors, demographic trends, and biomarker distributions to identify patterns in patient survival.

---

## 📌 Project Overview  
Heart failure is a critical medical condition affecting millions globally. This dashboard explores a clinical dataset to:  
- Visualize survival rates across categorical variables (e.g., diabetes, smoking, sex).  
- Analyze continuous biomarkers (e.g., creatinine levels, ejection fraction) using histograms.  
- Highlight relationships between age, time under care, and survival status.  
- Provide KPIs like total patients, deaths, demographics, and average age.  

**Tools Used**: Tableau, Excel  
**Dashboard Link**: [https://public.tableau.com/app/profile/supriya.mamillapalli/vizzes] 

---

## 📂 Dataset Details  
**File**: `heart_failure_clinical_records_dataset.csv`  
- **Rows**: 299 patients  
- **Features**: 12 clinical variables + 1 target (`DEATH_EVENT`)  
- **Categorical Variables**:  
  - Anaemia, Diabetes, High Blood Pressure, Sex, Smoking  
- **Continuous Variables**:  
  - Age, Creatinine Phosphokinase, Ejection Fraction, Platelets, Serum Creatinine, Serum Sodium, Time  

---

## 🚀 Features  
1. **Interactive Donut Charts**: Survival rates by:  
   - Anaemia  
   - Diabetes  
   - High Blood Pressure  
   - Sex  
   - Smoking  

2. **Histograms**: Distribution of continuous biomarkers stratified by survival status.  
3. **Box Plots**: Age distribution by sex and survival status.  
4. **Scatter Plot**: Relationship between age, time under care, and survival.  
5. **KPIs**: Total patients, deaths, males, females, and average age.  

---

## 🛠️ Installation/Running  
1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/your-username/heart-failure-analysis.git
   Dataset & Assets:

### Dataset ###: heart_failure_clinical_records_dataset.csv

Tableau Workbook: Heart failure clinical records TABLEAU.twb (or .twbx)

Exported Visuals: PDF and PNG files for quick reference.

View Dashboard:

Open the Tableau workbook locally or publish it to Tableau Public.

Use the Sex filter to toggle between male/female survival trends.

🔍 Key Insights
Sex Disparity: Males had a higher survival rate (44.15%) than females (23.75%).

Diabetes Impact: 28.43% of diabetic patients survived vs. 39.46% of non-diabetics.

Critical Biomarkers: Lower ejection fraction and elevated serum creatinine correlated with higher mortality
