# 💰 Financial Risk & Loan Analysis – Power BI Project

This Power BI project visualizes and analyzes financial risk and loan performance using structured SQL data and custom DAX logic. It focuses on understanding applicant profiles, loan distribution, and risk metrics to help financial institutions make informed lending decisions.

---

## 🚀 Project Summary

- **Tools Used:** MS SQL Server, Power BI, Power Query, DAX, On-Premises Gateway (Standard Mode)
- **Core Skills Applied:** Dataflows, data cleaning, data modeling, time intelligence with DAX, credit score analysis, dynamic visuals
- **Dashboard Pages:**
  - 📊 **Page 1:** Loan Default & Overview
  - 🧑‍💼 **Page 2:** Applicant Demographics & Financial Profile
  - 📉 **Page 3:** Financial Risk Metrics & Trends

---

## 🧩 Business Problems Solved

This project addresses real-world questions in financial lending, such as:

- 🔍 Which **loan purposes** carry the highest loan amounts?
- 👤 Which **age groups and employment types** are linked to higher loan amounts or defaults?
- 🧠 How does **credit score** relate to total loan amount and applicant behavior?
- 📈 How are loan trends changing **year-over-year (YoY)** and **year-to-date (YTD)**?
- 📊 What demographic segments carry **higher financial risk**, and how can banks adjust?

---

## 📌 Key Features

- 🔗 Connected to structured data from **MS SQL Server** via **Dataflow**
- 🧹 Cleaned and prepared data using SQL and Power Query (null removal, trimming, type correction)
- ⚙️ Built dynamic DAX measures for:
  - **Age Grouping**
  - **Credit Score Bins (CSB)**
  - **YoY and YTD calculations**
- 💡 Designed advanced visualizations to break down:
  - Loan Purpose
  - Demographics (Age, Gender, Marital Status)
  - Education vs. Credit Behavior
- 📈 Used Ribbon charts to analyze **YTD trends by marital status and credit score**
- 🔄 Configured **Scheduled Refresh** using On-Premises Data Gateway (Standard Mode)

---

## 📊 Dashboard Pages Breakdown

### 🔹 **Page 1: Loan Default & Overview**

- 📌 **Loan Amount by Purpose** (Home, Business, Education, Auto, Other)
- 📊 **Average Loan Amount by Age Group** – calculated using DAX-based buckets
- 👔 **Loan Income by Employment Type** – Full-Time, Part-Time, Self-Employed, etc.
- 🧾 Overview KPIs: Total Loan Amount, Approved Amount, Avg Interest Rate

### 🔹 **Page 2: Applicant Demographics & Financial Profile**

- 🥧 **Average Loan Amount by Age Group and Marital Status** – Dual-axis Pie Chart
- 📚 **Number of Loans by Education Type** – High School, Master’s, PhD
- 📊 **Total Loan Amount by Credit Score Bins (CSB)** – Custom binning logic created in DAX
- 👥 Gender vs. Loan Overview and Approval Ratio

### 🔹 **Page 3: Financial Risk Metrics**

- 🔁 **Loan Amount Change by Year** – Annual trend line
- 📈 **Year-over-Year (YoY) Loan Amount Change**
- 📊 **YTD Loan Amount by Credit Score Bin and Marital Status** – Ribbon Chart
- 📉 KPIs showing default trends, approval % by CSB category

---

## 🔗 Live Dashboard

👉 [📎 View the Power BI Dashboard](https://app.powerbi.com/links/PrculqM0W9?ctid=6d600138-0932-49bd-951c-0d8382b1ee74&pbi_source=linkShare&bookmarkGuid=d0596ffe-fa06-4184-8964-3b948c1259b5)

---

## 📂 Data Sources

Due to GitHub’s file size limit, data files are hosted externally:

- [📥 Loan_default.csv](https://drive.google.com/drive/folders/1XXWES_CD6kIrRdOVUtru744AFosP_9zz?usp=sharing)

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](./LICENSE) file for details.
