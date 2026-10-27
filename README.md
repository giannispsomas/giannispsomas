<h1 align="center">Giannis Psomas</h1>
<h3 align="center">Data Analyst</h3>
<p align="center"><b>SQL Server (T-SQL)</b> · <b>Power BI (DAX)</b> · <b>Python</b> · <b>Excel</b></p>

<p align="center">
  <a href="https://www.linkedin.com/in/giannispsomas/"><img src="https://img.shields.io/badge/LinkedIn-giannispsomas-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:psomasgiannis2001@gmail.com?subject=Hello%20Giannis"><img src="https://img.shields.io/badge/Email-psomasgiannis2001%40gmail.com-D14836?logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://learn.microsoft.com/api/credentials/share/en-us/46493298/6C43F06A1C2655B1?sharingId=47388BA7B38FAAB"><img src="https://img.shields.io/badge/Microsoft-PL--300_Certified-0078D4?logo=microsoft&logoColor=white" alt="Microsoft PL-300 certification"></a>
  <a href="https://cs50.harvard.edu/certificates/d87a5b73-d158-42b2-8997-17aa7e955e02"><img src="https://img.shields.io/badge/Harvard-CS50x_Certified-A51C30?logo=harvard&logoColor=white" alt="Harvard CS50x certificate"></a>
  <a href="https://giannispsomas.github.io/giannispsomas/Giannis-Psomas-CV.pdf"><img src="https://img.shields.io/badge/CV-View_PDF-444444?logo=readthedocs&logoColor=white" alt="Giannis Psomas CV (PDF)"></a>
</p>

<p align="center">📍 Athens-based · open to remote</p>

## 👋 About me

Data analyst with end-to-end project experience in SQL Server (T-SQL), Python, Excel and Power BI. I turn raw commercial data into retention, acquisition and profitability insights.

My projects follow one standard: data is cleaned and validated, assumptions are documented, every figure traces back to a query, and each analysis ends with a recommendation.

- 🔧 **Stack:** I clean and model data in **SQL Server**, analyse it in **Python** (pandas, scikit-learn), build scenario models in **Excel** (Solver), and present results in **Power BI**.
- 🎯 **Focus:** customer analytics, covering retention and churn, segmentation, acquisition economics and credit risk.
- 🔎 **Looking for:** data analyst roles in customer analytics and BI, available across European time zones.
- 🗣️ **Languages:** Greek (Native) · English (C2) · German (B2) · French (B2)

## 🚀 Featured projects

### 1. [End-To-End Retail Retention Analysis](https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis)
`SQL Server (T-SQL)` `Python` `Power BI (DAX)` — *1M+ transactions*

**The question:** Where is an online retailer losing customers, and how much revenue can be won back?

**The answer:** 51% of customers have been inactive for 90+ days and hold £3.30M of historical revenue. The 589 who lapsed 91 to 180 days ago are the most recoverable.

- **Repeat buyers:** 72% of customers, generating **97% of revenue**. The median second order comes on day 57.
- **Concentration:** **42 customers hold 27% of revenue.**
- **Models:** RFM and K-Means segmentation, cohort retention, and churn scoring (**ROC-AUC 0.77**).
- **Delivery:** a star schema built from 1M+ raw rows and a 6-page Power BI report with 21 DAX measures.
- **Recommendation:** a day-30 follow-up to repeat buyers, dedicated account management for the top 42, and win-back outreach to the 589.

📊 [**Power BI report (PDF)**](https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/blob/main/power_bi/Retention_Analysis.pdf) · 🎥 [**Video walkthrough**](https://youtu.be/I_UvFsbfLRI) · 📄 [**Case study**](https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/blob/main/Case_Study.md) · 🧾 [**Executive summary**](https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/blob/main/Executive_Summary.pdf) · 🎞️ [**Slides**](https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/blob/main/Executive_Summary_Slides.pptx)

<p align="center">
  <a href="https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/blob/main/power_bi/Retention_Analysis.pdf">
    <img src="https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/raw/main/power_bi/images/1_Business_Overview.png" alt="Power BI dashboard: business overview" width="48%">
  </a>
  <a href="https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/blob/main/power_bi/Retention_Analysis.pdf">
    <img src="https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/raw/main/power_bi/images/6_Churn_Risk.png" alt="Power BI dashboard: churn risk" width="48%">
  </a>
</p>

---

### 2. [FinTech Customer Acquisition and Profitability Analysis](https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis)
`SQL Server (T-SQL)` `Excel (Solver)` `Power BI (DAX)` — *synthetic data, 10 tables, 136K rows*

**The question:** Which acquisition channels bring profitable customers for a fictional fintech company, and how should next quarter's budget be reallocated?

**The answer:** After credit losses only referral has a positive value per customer (+54 EUR). Affiliate looks best before them (252 EUR) and worst after them (-491 EUR), because 24% of its loans default.

- **Unit economics:** CAC from 12.47 EUR (referral) to 65.59 EUR (paid social). One paid social campaign costs 365 EUR per customer against a channel median of 62.
- **Statistics:** bootstrap intervals show affiliate is clearly the worst after credit losses. Referral's advantage is not yet proven.
- **Budget model:** a Solver optimizer tested in 8 scenarios, with a modelled uplift of about **40,700 EUR** for the quarter.
- **Delivery:** 10 reporting views and a 6-page Power BI report with 56 DAX measures.
- **Recommendation:** tighten credit rules for affiliate before cutting its spend, stop the overspending campaign, and shift budget to referral in steps.

🎥 [**Video walkthrough**](https://www.youtube.com/watch?v=IQ7_uw7gf64) · 📊 [**Power BI report (PDF)**](https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/blob/main/power_bi/Customer_Acquisition_Analysis.pdf) · 📄 [**Case study**](https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/blob/main/Case_Study.md) · 🧾 [**Executive summary**](https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/blob/main/Executive_Summary.pdf) · 🎞️ [**Slides**](https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/blob/main/Executive_Summary_Slides.pptx)

<p align="center">
  <a href="https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/blob/main/power_bi/Customer_Acquisition_Analysis.pdf">
    <img src="https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/raw/main/power_bi/images/1_Executive.png" alt="Power BI dashboard: executive" width="48%">
  </a>
  <a href="https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/blob/main/power_bi/Customer_Acquisition_Analysis.pdf">
    <img src="https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/raw/main/power_bi/images/4_Credit_Risk.png" alt="Power BI dashboard: credit risk" width="48%">
  </a>
</p>

## 🎓 University projects

Two analyses rebuilt in Python from coursework at the University of West Attica, each starting with a data audit. **[See both in one repo →](https://github.com/giannispsomas/University-Data-Projects)**

- **[Entersoft A.E.: Financial Statement Analysis, 2014–2017](https://github.com/giannispsomas/University-Data-Projects/tree/main/entersoft-financial-analysis):** I checked the coursework inputs against the published annual reports and **corrected 5 transcription errors** that had distorted the margin and interest-cover ratios. On the verified data, the EBIT margin stepped down from 24% to 12% in 2015 and then held at 14 to 15%. 📄 [Summary](https://github.com/giannispsomas/University-Data-Projects/blob/main/entersoft-financial-analysis/Entersoft_Financial_Analysis_Summary.pdf) · 📓 [Notebook](https://github.com/giannispsomas/University-Data-Projects/blob/main/entersoft-financial-analysis/analysis.ipynb)
- **[Film Tourism in Greece: Survey Analysis](https://github.com/giannispsomas/University-Data-Projects/tree/main/film-tourism-survey):** 60 survey responses, validated against the original paper (21 of 24 figures reproduced exactly). **58% would travel to a film set.** Students were more willing (69% vs 38%), but the difference was **not significant after correction**, so it is reported as a hypothesis. The original survey was a joint project with a fellow student. 📄 [Summary](https://github.com/giannispsomas/University-Data-Projects/blob/main/film-tourism-survey/Film_Tourism_Survey_Summary.pdf) · 📓 [Notebook](https://github.com/giannispsomas/University-Data-Projects/blob/main/film-tourism-survey/analysis.ipynb)

## 🛠️ Skills

**Data & BI**

![SQL Server](https://img.shields.io/badge/SQL_Server-T--SQL-CC2927?logo=microsoftsqlserver&logoColor=white)
![SSMS](https://img.shields.io/badge/SSMS-0078D4?logo=microsoft&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-DAX_·_Power_Query-F2C811?logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-Solver-217346?logo=microsoftexcel&logoColor=white)

**Python**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

**Methods:** data cleaning and validation · star schema modelling · cohort analysis · RFM and K-means segmentation · logistic regression · CAC and LTV · statistical testing (bootstrap, Mann-Whitney) · forecasting · attribution · credit risk · budget optimisation (Solver) · dashboard design

## 📫 Let's talk

Athens-based and open to **remote data analyst roles**.

**[LinkedIn](https://www.linkedin.com/in/giannispsomas)** · **[psomasgiannis2001@gmail.com](mailto:psomasgiannis2001@gmail.com)**
