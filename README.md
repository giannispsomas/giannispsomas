<h1 align="center">Giannis Psomas</h1>
<h3 align="center">Data Analyst</h3>
<p align="center"><b>SQL Server (T-SQL)</b> · <b>Power BI (DAX)</b> · <b>Python</b> · <b>Excel</b></p>
<p align="center"><i>Clean data, clear answers, and recommendations worth acting on.</i></p>

<p align="center">
  <a href="https://www.linkedin.com/in/giannispsomas/"><img src="https://img.shields.io/badge/LinkedIn-giannispsomas-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:psomasgiannis2001@gmail.com?subject=Hello%20Giannis"><img src="https://img.shields.io/badge/Email-psomasgiannis2001%40gmail.com-D14836?logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://learn.microsoft.com/api/credentials/share/en-us/46493298/6C43F06A1C2655B1?sharingId=47388BA7B38FAAB"><img src="https://img.shields.io/badge/Microsoft-PL--300_Certified-0078D4?logo=microsoft&logoColor=white" alt="Microsoft PL-300 certification"></a>
  <a href="https://cs50.harvard.edu/certificates/d87a5b73-d158-42b2-8997-17aa7e955e02"><img src="https://img.shields.io/badge/Harvard-CS50x_Certified-A51C30?logo=harvard&logoColor=white" alt="Harvard CS50x certificate"></a>
  <a href="https://giannispsomas.github.io/giannispsomas/Giannis-Psomas-CV.pdf"><img src="https://img.shields.io/badge/CV-View_PDF-444444?logo=readthedocs&logoColor=white" alt="Giannis Psomas CV (PDF)"></a>
</p>

<p align="center">📍 Athens, Greece (UTC+2 / UTC+3)</p>

## 👋 About me

Data analyst, Microsoft PL-300 certified, with end-to-end project experience in SQL Server (T-SQL), Python and Power BI. I turn raw commercial data into actionable retention and churn insights, and I am looking for a remote data analyst role.

My projects follow one standard: data is cleaned and validated, assumptions are documented, every figure traces back to a query, and each analysis ends with a recommendation.

- 🔧 **How I work:** I clean and model raw data in **SQL Server (T-SQL)**, run the deeper analysis in **Python** (pandas, scikit-learn), and present the results in **Power BI** with a DAX model and a dashboard people can use.
- 🎯 **What I focus on:** Customer analytics: retention and churn, segmentation, cohorts, acquisition economics and dashboard design.
- 🔎 **Looking for:** remote data analyst roles in customer analytics and BI, based in Athens (EU) and available across European time zones.
- 🗣️ **Languages:** English (C2) · German (B2) · French (B2)
- 📜 **Certified:** Microsoft **PL-300** (Power BI Data Analyst) · Harvard **CS50x**

## 🚀 Featured projects

### 1. [End-To-End Retail Retention Analysis](https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis)
`SQL Server (T-SQL)` `Python` `pandas` `scikit-learn` `Matplotlib` `Seaborn` `Power BI (DAX)` — *1M+ transactions*

**The question:** Where is an online retailer losing customers, and how much revenue can be won back?

**The answer in one line:** 51% of customers have been inactive for 90+ days and hold £3.30M of historical revenue, and 589 recently lapsed customers are the most recoverable group.

- **Data modelling:** Built a Kimball star schema from 1M+ raw rows, removing **11,812 duplicates** and resolving 83 multi-date invoices. Revenue reconciles to **£19.64M**.
- **SQL analysis:** CTEs, window functions, `PIVOT` and a stored procedure. **72% of customers are repeat buyers and generate 97% of revenue.**
- **Segmentation and cohorts:** RFM and K-Means on 5,852 customers. **42 customers hold 27% of revenue.** Retention peaks at ~22% in month 2, then erodes.
- **Churn scoring:** Logistic regression (**ROC-AUC 0.77**) scoring every customer's churn risk and sizing the revenue at stake.
- **Dashboard:** 6-page Power BI report with 21 DAX measures, plus prioritised win-back recommendations.

**Recommendations:**

- **Early retention:** Launch a day-30 follow-up campaign to repeat buyers, before the median day-57 second order.
- **Key accounts:** Assign dedicated account management to the 42 highest-value customers, who hold 27% of revenue.
- **Win-back:** Prioritise outreach to the 589 customers who lapsed 91–180 days ago, the most recoverable group.

📊 [**Power BI report (PDF)**](https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/blob/main/power_bi/Retention_Analysis.pdf) · 🎥 [**Video walkthrough**](https://youtu.be/I_UvFsbfLRI) · 📄 [**Case study**](https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/blob/main/Case_Study.md)

<p align="center">
  <a href="https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/blob/main/power_bi/Retention_Analysis.pdf">
    <img src="https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/raw/main/power_bi/images/1_Business_Overview.png" alt="Power BI dashboard: business overview" width="48%">
  </a>
  <a href="https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/blob/main/power_bi/Retention_Analysis.pdf">
    <img src="https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/raw/main/power_bi/images/4_Customer_Segmentation.png" alt="Power BI dashboard: customer segmentation" width="48%">
  </a>
  <a href="https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/blob/main/power_bi/Retention_Analysis.pdf">
    <img src="https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/raw/main/power_bi/images/5_Cohort_and_Retention.png" alt="Power BI dashboard: cohort and retention" width="48%">
  </a>
  <a href="https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/blob/main/power_bi/Retention_Analysis.pdf">
    <img src="https://github.com/giannispsomas/End-To-End-Retail-Retention-Analysis/raw/main/power_bi/images/6_Churn_Risk.png" alt="Power BI dashboard: churn risk" width="48%">
  </a>
</p>

---

### 2. [FinTech Customer Acquisition and Profitability Analysis](https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis)
`SQL Server (T-SQL)` `Excel (Solver)` `Power BI (DAX)` — *10 tables, 136K rows (synthetic data)*

**The question:** Which acquisition channels bring profitable customers for a fictional neobank, and how should next quarter's budget be reallocated?

**The answer in one line:** Only referral earns money per customer after credit losses (+54 EUR), while affiliate looks best before them (252 EUR) and worst after them (-491 EUR), because 24% of its loans default.

- **Data modelling:** Profiled and cleaned 10 tables in T-SQL, removing **100 duplicate customer records**, and defined every metric once in **10 reporting views**.
- **Unit economics:** CAC from **12.47 EUR** (referral) to **65.59 EUR** (paid social), with payback in 2 to 6 months before credit losses.
- **Attribution and campaigns:** Position-based credit gives paid social about **20% fewer customers** than the recorded channel. One campaign costs **365 EUR per customer** against a channel median of 62.
- **Credit risk:** Default rate and credit loss by channel on 1,587 seasoned loans. **Affiliate defaults on 24.1%**, others on 6.5% to 12.5%.
- **Budget model:** Response curves and a Solver optimizer in Excel, tested in 8 scenarios. Modelled uplift of about **40,700 EUR** for the quarter.
- **Dashboard:** 5-page Power BI report with 41 DAX measures, plus ranked recommendations.

**Recommendations:**

- **Paid social:** Stop Summer Reach style spend, which took 24.5% of the channel's budget at five to six times the normal cost per customer.
- **Affiliate:** Tighten credit rules for affiliate customers (37% of affiliate students show an early default) before cutting its spend.
- **Referral:** Move money to referral in steps, as a test of whether it scales.

📊 [**Power BI report (PDF)**](https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/blob/main/power_bi/Customer_Acquisition_Analysis.pdf) · 📄 [**Case study**](https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/blob/main/Case_Study.md) · 🧾 [**One-page summary**](https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/blob/main/Executive_Summary.pdf)

<p align="center">
  <a href="https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/blob/main/power_bi/Customer_Acquisition_Analysis.pdf">
    <img src="https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/raw/main/power_bi/images/1_Executive.png" alt="Power BI dashboard: executive" width="48%">
  </a>
  <a href="https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/blob/main/power_bi/Customer_Acquisition_Analysis.pdf">
    <img src="https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/raw/main/power_bi/images/3_Attribution_and_Campaigns.png" alt="Power BI dashboard: attribution and campaigns" width="48%">
  </a>
  <a href="https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/blob/main/power_bi/Customer_Acquisition_Analysis.pdf">
    <img src="https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/raw/main/power_bi/images/4_Credit_Risk.png" alt="Power BI dashboard: credit risk" width="48%">
  </a>
  <a href="https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/blob/main/power_bi/Customer_Acquisition_Analysis.pdf">
    <img src="https://github.com/giannispsomas/FinTech-Customer-Acquisition-and-Profitability-Analysis/raw/main/power_bi/images/5_Budget_Scenarios.png" alt="Power BI dashboard: budget scenarios" width="48%">
  </a>
</p>

## 🎓 University projects

Two analyses rebuilt in Python from coursework at the University of West Attica, each starting with a data audit. **[See both in one repo →](https://github.com/giannispsomas/University-Data-Projects)**

### [Entersoft A.E.: Financial Statement Analysis, 2014–2017](https://github.com/giannispsomas/University-Data-Projects/tree/main/entersoft-financial-analysis)
`Python` `pandas` `Excel` — *4 years of statements, audited against the published annual reports*

I checked the coursework inputs against Entersoft's published annual reports and **corrected 5 transcription errors** (two transposed pairs and a typo) that had distorted the margin and interest-cover ratios. On the verified data, the EBIT margin stepped down from 24% to 12% in 2015 and then held at 14–15%, while receivables stay at about 200 days of sales.

📄 [**One-page summary**](https://github.com/giannispsomas/University-Data-Projects/blob/main/entersoft-financial-analysis/Entersoft_Financial_Analysis_Summary.pdf) · 📓 [**Notebook**](https://github.com/giannispsomas/University-Data-Projects/blob/main/entersoft-financial-analysis/analysis.ipynb)

<p align="center">
  <a href="https://github.com/giannispsomas/University-Data-Projects/tree/main/entersoft-financial-analysis">
    <img src="https://raw.githubusercontent.com/giannispsomas/University-Data-Projects/main/entersoft-financial-analysis/figures/fig2_workbook_vs_annual_report.png" alt="Workbook inputs versus the published annual report: operating expenses and depreciation" width="48%">
  </a>
  <a href="https://github.com/giannispsomas/University-Data-Projects/tree/main/entersoft-financial-analysis">
    <img src="https://raw.githubusercontent.com/giannispsomas/University-Data-Projects/main/entersoft-financial-analysis/figures/fig1_growth_and_margins.png" alt="Entersoft sales and margins, 2014 to 2017" width="48%">
  </a>
</p>

---

### [Film Tourism in Greece: Survey Analysis](https://github.com/giannispsomas/University-Data-Projects/tree/main/film-tourism-survey)
`Python` `pandas` `SciPy` — *60 survey responses*

I cleaned and validated the survey data against the original paper (21 of 24 published figures reproduced exactly), then tested group differences with multiple-comparison correction. **58% would travel to a film set.** Students were more willing than other respondents (69% vs 38%), but the difference was **not significant after correction**, so it is reported as a hypothesis, not a finding. The original survey was made together with a fellow student.

📄 [**One-page summary**](https://github.com/giannispsomas/University-Data-Projects/blob/main/film-tourism-survey/Film_Tourism_Survey_Summary.pdf) · 📓 [**Notebook**](https://github.com/giannispsomas/University-Data-Projects/blob/main/film-tourism-survey/analysis.ipynb)

<p align="center">
  <a href="https://github.com/giannispsomas/University-Data-Projects/tree/main/film-tourism-survey">
    <img src="https://raw.githubusercontent.com/giannispsomas/University-Data-Projects/main/film-tourism-survey/figures/fig1_key_indicators.png" alt="Film tourism survey: key indicators with 95% confidence intervals" width="48%">
  </a>
  <a href="https://github.com/giannispsomas/University-Data-Projects/tree/main/film-tourism-survey">
    <img src="https://raw.githubusercontent.com/giannispsomas/University-Data-Projects/main/film-tourism-survey/figures/fig2_travel_by_segment.png" alt="Willingness to travel to a film set, students versus other respondents" width="48%">
  </a>
</p>

## 🛠️ Skills

**Data & BI**

![SQL Server](https://img.shields.io/badge/SQL_Server-T--SQL-CC2927?logo=microsoftsqlserver&logoColor=white)
![SSMS](https://img.shields.io/badge/SSMS-0078D4?logo=microsoft&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-DAX_·_Power_Query-F2C811?logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoftexcel&logoColor=white)

**Python**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

**Methods:** Data cleaning and validation · Star schema modelling · Cohort analysis · RFM segmentation · K-means clustering · Logistic regression · Hypothesis testing · Dashboard design

**Tools:** Git · GitHub

## 📫 Let's talk

I'm open to **remote data analyst roles**, working with teams wherever they are.

**[LinkedIn](https://www.linkedin.com/in/giannispsomas)** · **[psomasgiannis2001@gmail.com](mailto:psomasgiannis2001@gmail.com)**

<details>
<summary>⛓️ Side projects outside analytics (Solidity)</summary>
<br>

Before moving into data, I explored smart contracts out of curiosity about how systems work from first principles:

- [ERC20-Token](https://github.com/giannispsomas/ERC20-Token): ERC20 built with Foundry, without OpenZeppelin
- [ERC20-Staking-Token](https://github.com/giannispsomas/ERC20-Staking-Token): ERC20 with staking, burning and minting

</details>
