# 🏥 Hospital Performance & Operations Analytics (Power BI)

## 📌 Executive Summary
A comprehensive, 3-page interactive Power BI dashboard designed to evaluate healthcare operational efficiency, clinical outcomes, financial performance, and patient demographics. Built using a healthcare dataset with robust ETL in Power Query and star-schema DAX modeling.

---

## 🛠️ Data Pipeline & Analytics Architecture
1. **Data Cleaning & ETL (Power Query):**
   * Handled missing and negative billing values using Absolute Value transformations.
   * Derived **Length of Stay (LOS)** from admission and discharge dates.
   * Engineered dynamic **Age Groups** (Pediatric, Young Adult, Adult, Senior).
2. **Data Modeling & Time Intelligence:**
   * Constructed a **Star Schema** centered around a dedicated `Dim_Date` dimension.
   * Developed key DAX measures for Revenue, Average Daily Revenue, Length of Stay, and Emergency Admission rates.
3. **Interactive Dashboard Layout:**
   * **Page 1: Executive Overview** — High-level financial performance, admission trends over time, and specialty breakdown.
   * **Page 2: Clinical & Operational Performance** — Clinical test outcomes, daily revenue efficiency, maximum stay limits, and doctor capacity.
   * **Page 3: Patient Demographics & Insurance** — Insurance provider profitability, age/gender distribution, and blood type breakdown.

---

## 📊 Core Key Performance Indicators (KPIs)
* **Total Revenue & Admissions**
* **Average & Max Length of Stay (ALOS / Max LOS)**
* **Average Daily Revenue**
* **Abnormal Test Results %**
* **Insurance Revenue Contribution**

---

## 🚀 How to Explore
1. Download or clone this repository.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Interact with dynamic slicers for deep-dive analytics across all pages.
  
## 🛡️ License

This project is licensed under the MIT License. You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

Hi there! I'm Ahmed Alnaggar. I'm a data analyst.
