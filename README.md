# QS World University Rankings 2026 Analysis  
Analysis to explore global leading institutions ranked as per 6 ranking indicators by QS World University Rankings

---
## MAIN PRESANTATION YOU CAN FIND BY THIS LINK -- https://public.tableau.com/app/profile/ola.gaffarova/viz/UNI_17581014299910/Story1#1 --
---

## Project Summary  
This project analyzes the **QS World University Rankings 2026 dataset** to uncover insights into how universities worldwide are evaluated across multiple performance indicators. The rankings combine various lenses, including **Academic Reputation, Employer Reputation, Faculty/Student Ratio, International Research Network, Sustainability, and Employability & Outcomes**.  

The goal of this analysis is to help **students, researchers, and policymakers** better understand what drives a university’s overall performance and which factors differentiate top-ranked institutions from others. By examining relationships between the different score indicators, trends across countries and regions, and quartile comparisons, the project provides data-driven insights to guide educational decision-making.  

The analysis explores correlations, regression models, quartile distributions, and country-level comparisons, while also preparing clean, structured datasets for further visualization in **Tableau**.  

## Motivation
It is easy to assume that the best universities are simply those with the highest rankings at the very top of the QS list.
However, not everyone can realistically enroll in the top 10 due to high competition and cost. This project is motivated by the idea that high-quality education can also be found beyond the top tier, since there are many excellent universities worldwide that could be strong alternatives.

## Objective
According to the QS methodology, the Discovery and Research lens carries the greatest weight (50%), with Academic Reputation (AR) as its key component (30%).
The goal of this analysis is to explore which other scores contribute to success in AR, helping us better understand what drives rankings outside of the top tier.

---

## Key Questions  
- Which indicators have the strongest correlation with the **Overall Score**?  
- How do different sub-scores (e.g., Academic Reputation, Employer Reputation, Sustainability) interact with each other?  
- What are the strongest predictors of **Academic Reputation** and other key indicators?  
- How do universities compare across **quartiles** (top 25%, 50%, etc.) in terms of performance drivers?  
- Which countries and regions consistently host the highest-performing institutions?  
- How do patterns differ between large, medium, and small universities, or between public and private institutions?  
- What insights can students use when choosing universities based on their personal priorities (employability, sustainability, research, etc.)?  

---

## Data Set  
The dataset contains detailed information on more than **1,500 universities worldwide**, including:  
- **Overall Score and Rank**  
- **Academic Reputation (AR)**  
- **Employer Reputation (ER)**  
- **Faculty/Student Ratio (FSR)**  
- **Citations per Faculty (CPF)**  
- **International Faculty Ratio (IFR)**  
- **International Student Ratio (ISR)**  
- **International Research Network (IRN)**  
- **Employability & Outcomes (EO)**  
- **Sustainability (SUS)**  
- Metadata: Country/Territory, Region, Size, Focus, Research intensity, Status  

**Note**: Due to file size limitations, the dataset is not uploaded to GitHub.  
You can access it on the official QS website: [QS World University Rankings 2026](https://www.topuniversities.com/world-university-rankings)  

---

## Repository Structure  

### 01 Project Management  
- **Project Brief** → Overview of goals and research questions  

### 02 Data  
- **Original Data** → Raw QS dataset  
- **Prepared Data** → Cleaned, transformed, and aggregated datasets (for Python and Tableau analysis)  

### 03 Scripts  
- Python scripts (Jupyter notebooks) for data cleaning, descriptive statistics, correlation, regression, and data export for visualization  

### 04 Analysis  
- **Visualizations** → Correlation heatmaps, regression plots, quartile boxplots, and country/region aggregations  

### 05 Sent to Client  
- Final slide deck with summarized findings and recommendations for stakeholders  

### README.md  
This file (project documentation)  

---

## Tools and Libraries Used  
The analysis was conducted in **Python** using **Jupyter notebooks**, with the following libraries:  

- **pandas** → Data manipulation and cleaning  
- **numpy** → Numerical operations  
- **os** → File and directory management  
- **matplotlib.pyplot** → Visualizations (heatmaps, regression, boxplots)  
- **seaborn** → Advanced statistical data visualization  
- **scikit-learn** → Regression modeling (linear regression, multiple regression)  
- **scipy** → Correlation and statistical analysis  

For **interactive dashboards and visual storytelling**, the cleaned data was imported into **Tableau**.  

---

## Disclaimer  
The QS World University Rankings dataset is publicly available via QS. This project is conducted as part of **CareerFoundry’s Data Analytics Program** for educational purposes.  

---

## Author  
Data Analysis by **Olga Gaffarova**  
