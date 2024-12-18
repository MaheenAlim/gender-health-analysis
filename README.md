# gender-health-analysis
Exploring cardiovascular health using BMI, gender, and occupation insights with Python and Seaborn.
# Health Analysis Project  
**Understanding the Role of Gender & Occupation on Stress Levels and BMI on Heart Rate**  
**Prepared by Maheen Mohammad Alim**  
**Student ID: 100878291**  

## Project Overview  
This project analyzes the **Sleep Health and Lifestyle Dataset** consisting of **374 individuals**. The dataset includes demographic information, health metrics (e.g., BMI, heart rate), and lifestyle indicators (e.g., stress levels, physical activity).  
The primary goals of this analysis are:  
1. To explore how **stress levels** are influenced by **gender** and **occupation**.  
2. To investigate the relationship between **Body Mass Index (BMI)** and **heart rate**.  

---

## Dataset  
- Source: [Kaggle - Sleep Health and Lifestyle Dataset](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset)  
- Dataset contains:  
  - **Demographics** (Gender, Age, Occupation)  
  - **Health Metrics** (BMI, Heart Rate, Blood Pressure)  
  - **Lifestyle Indicators** (Stress Levels, Sleep Quality, Physical Activity, Steps)  

---

## Data Processing  
1. The dataset was loaded into a DataFrame for analysis.  
2. Columns were renamed for better clarity, including adding units where applicable (e.g., Stress Level (out of 10), Heart Rate (bpm)).  
3. Missing data was checked and handled appropriately.  
4. Duplicate entries were identified and removed to ensure data consistency.  
5. For BMI values, "Normal" was replaced with "Normal Weight" for consistency.  
6. The dataset was cleaned and ready for analysis after these steps.  

---

## Visualizations  

### Gender Distribution  
- A count plot was generated to show the distribution of males and females in the dataset.  
- This visualization provided insights into the gender balance, which was essential for subsequent gender-based analysis.  

---

### BMI Distribution  
- A pie chart was created to display the proportion of individuals across different BMI categories: **Normal Weight**, **Overweight**, and **Obese**.  
- This chart highlighted the prevalence of obesity and other BMI categories in the dataset.  

---

### Stress Levels by Gender and Occupation  
- A bar chart was generated to visualize the average stress levels across different occupations, separated by gender.  
- The results showed how stress levels varied by gender for specific professions like Doctors, Engineers, and Sales Representatives.  
- Males exhibited higher stress levels compared to females across most occupations.  

---

### Heart Rate by BMI  
- A line chart was created to visualize the relationship between BMI categories and average heart rate.  
- The trend revealed that individuals with higher BMI values (e.g., Obese) had significantly higher heart rates compared to those in the Normal Weight or Overweight categories.  

---

## Statistical Insights  

### Stress Levels: Gender and Occupation  
- Males generally report higher stress levels across most occupations.  
- **High-Stress Occupations**:  
  - Males: Sales Representatives (8.0), Salespersons (7.0).  
  - Females: Scientists (7.0).  
- Females exhibit lower stress levels compared to males in the same occupation (e.g., Engineers, Doctors).  

---

### BMI and Heart Rate  
- **Positive Correlation**: Higher BMI corresponds to increased heart rate:  
  - **Normal Weight**: ~69 bpm  
  - **Overweight**: ~72 bpm  
  - **Obese**: ~84 bpm  
- This highlights the need for individuals with higher BMI to monitor their cardiovascular health.  

---

## Installation  
To run this analysis, ensure Python and the following libraries are installed:  

- pandas  
- seaborn  
- matplotlib  

You can install the required libraries using pip.  

---

## Usage  
1. Download the dataset from the [source link](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset).  
2. Place the `Sleep_health_and_lifestyle_dataset.csv` file in your project directory.  
3. Run the script in a Python environment (Jupyter Notebook, PyCharm, etc.).  
4. Modify the script to explore additional insights or visualizations.  

---

### References  
1. Source Data: [Sleep Health and Lifestyle Dataset](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset)  
2. Libraries:  
   - [pandas](https://pandas.pydata.org/)  
   - [seaborn](https://seaborn.pydata.org/)  
   - [matplotlib](https://matplotlib.org/)  
