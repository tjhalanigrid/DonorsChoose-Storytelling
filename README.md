# Funding the Gap – DonorsChoose Data Storytelling Project

## 📌 Project Overview
This project analyzes DonorsChoose classroom funding data using visual storytelling techniques.  
The goal is to understand which types of projects are more or less likely to be approved and which
project characteristics are associated with approval outcomes, with a focus on subject categories,
grade levels, project cost, project scale, and teacher experience.

The project is designed for non-technical stakeholders and emphasizes clarity, interpretability,
and actionable insights.

---

## 🎯 Objectives
- Identify which project characteristics are associated with approval outcomes  
- Highlight disparities across subjects and grade levels  
- Examine how project cost, scale, and teacher experience interact  
- Provide actionable recommendations to improve equity and platform support  

---

## 📊 Key Insights
- Project cost is the most consistent constraint on approval outcomes  
- Teacher experience improves approval likelihood, but does not fully offset high project cost  
- Projects serving older students and some subject categories experience systematically lower approval rates  
- Approval outcomes are shaped by interacting project characteristics rather than any single factor  

---

## 📁 Repository Structure

- visuals/  
  → Final interactive charts (Plotly HTML files) used in the report.

- notebooks/  
  → analysis.ipynb: full exploratory analysis, data preparation, and intermediate experiments.  
  → main.ipynb: final analysis and code used to generate the report visuals.

- data/  
  → Dataset files (not included in the repository due to large size; see data source below).

- report/  
  → main.html: main storytelling report.  
  → NextExperiments.html: extended future work section.

- style.css  
  → Custom styling for the storytelling report.

- README.md  
  → Project documentation and reproduction instructions.

---

## 🔁 How to Reproduce the Analysis

1. Download the DonorsChoose dataset from the link provided below.
2. Place the dataset files inside the `data/` directory.
3. Open `notebooks/analysis.ipynb` and run all cells in order.
4. Run `notebooks/main.ipynb` to generate the final visualizations.
5. The generated Plotly HTML files will be saved to the `visuals/` folder.
6. Open `report/main.html` in a browser to view the final storytelling report.

---

## 🌐 Final Report

You can view the full interactive report here:  
➡️ https://tjhalanigrid.github.io/DonorsChoose-Storytelling/main.html

---

## 📌 Data Source
DonorsChoose dataset from Kaggle:  
https://www.kaggle.com/datasets/arunasivapragasam/donors-choose

---

## 🚀 Future Work
- Analyze proposal text quality and clarity using NLP techniques  
- Build predictive models to identify projects at risk of rejection  
- Explore regional and geographic differences in funding outcomes  

---

## 👩‍💻 Author
Tanisha Jhalani  
Storytelling with Data Project
