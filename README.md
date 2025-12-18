# **Impact_of_Handwashing_on_Maternal_Mortality: A Historical Data Analysis**

---
## **TABLE OF CONTENT**
[INTRODUCTION](#Introduction)
[OBJECTIVES](#Objectives)
[DATA DESCRIPTION](#DataDescription)
[METHODOLOGY](#Methodology)
[KEY FINDINGS](#KeyFindings)
[STATISTICAL ANALYSIS](#StatisticalAnalysis)
[CONCLUSION](#Conclusion)
[TOOLS USED](#ToolsUsed)

---
## **INTRODUCTION**
Maternal mortality was a major public health challenge in 19th-century hospitals. This project analyzes historical birth and death records from two clinics to evaluate differences in mortality rates and assess the impact of introducing handwashing practices in 1847.

---
### **OBJECTIVES**
1. Determine yearly mortality trends across clinics
2. Identify the year with the highest proportion of deaths
3. Evaluate mortality differences before and after handwashing
4. Statistically test the effectiveness of handwashing
5. Communicate insights using Python and Power BI

---
### **DATASET DESCRIPTION**
The dataset contains monthly and yearly records with:
- year
- month
- clinic
- births
- deaths

---
#### **METHODOLOGY**
- Data cleaning and aggregation using **pandas**
- Visualization using **matplotlib**
- Statistical inference using **Welch's t-test**
- Interactive dashboard built in **Power BI**

---
#### **KEY FINDINGS**
- Clinic 1 consistently recorded higher mortality than Clinic 2
- The highest mortality occurred in 1842 for both clinics
- Mean monthly death proportion:
    - **Before handwashing: 10.51%**
    - **After handwashing: 2.11%**
- Handwashing reduced mortality by approximately **80%**

---
##### **STATISTICAL ANALYSIS**
A Welch's t-test comparing monthly death proportions before and after handwashing yielded:
- **p-value <0.001**

This confirms that the reduction in mortality after handwashing was **statistically significant**

---
##### **CONCLUSION**
The analysis provides compelling statistical and visual evidence that handwashing dramatically reduced maternal mortality. This reinforces the importance of hygiene practices in healthcare and demonstrates how data-driven decisions can save lives.

---
###### **TOOLS USED**
- Python (pandas, matplotlib, scipy)  
- Microsoft Power BI  
- GitHub (documentation and version control)