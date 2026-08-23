# Fee Payment Tracker Dashboard and Prediction

## 📊 Project Overview

**Fee Payment Tracker Dashboard and Prediction** is a data analytics and
business intelligence project developed to organize, analyze, visualize,
and monitor student fee payment information.

The project combines data preparation, SQL-based analysis, dashboard
visualization, and payment-risk prediction to provide useful insights
into fee collection and pending payments.

The overall project workflow is:

**Raw Data → Excel Cleaning → SQL Database → SQL Analysis → Dashboard →
Business Insights**

------------------------------------------------------------------------

## 🎯 Objectives

The main objectives of the project are:

-   To organize student fee data in a structured format.
-   To clean and preprocess raw fee collection data using Microsoft
    Excel.
-   To store and manage structured fee information using SQL.
-   To calculate total, collected, and pending fees.
-   To identify students with pending or partially paid fees.
-   To analyze fee collection by course and month.
-   To develop an interactive dashboard for fee collection monitoring.
-   To provide payment-risk prediction as an additional analytical
    feature.

------------------------------------------------------------------------

## ✨ Key Features

### Dashboard

The dashboard provides:

-   Total Fees
-   Collected Fees
-   Pending Fees
-   Collection Percentage
-   Total Students
-   Total Payments
-   Course-wise fee collection
-   Payment-status analysis
-   Month-wise collection trends
-   Pending-fee analysis
-   Student-level fee summary
-   Interactive filters and data exploration

### Payment Prediction

The web dashboard includes a payment-risk prediction module.

The prediction uses information such as:

-   Course
-   Batch
-   Total Fee
-   Amount Paid
-   Amount Paid Ratio
-   Days Overdue

The model uses multinomial softmax logistic regression with standardized
numerical features and one-hot encoded categorical features.

The prediction result is represented as:

-   **LOW RISK**
-   **MEDIUM RISK**
-   **HIGH RISK**

> The prediction is intended as an analytical screening signal and
> should not be treated as a guaranteed individual forecast.

------------------------------------------------------------------------

## 🛠️ Technologies Used

### Data Preparation

-   Microsoft Excel

### Data Storage and Analysis

-   SQL

### Business Intelligence

-   Microsoft Power BI
-   DAX

### Web Dashboard

-   HTML5
-   CSS3
-   JavaScript
-   Chart.js
-   SheetJS / xlsx.js

### Deployment

-   GitHub
-   GitHub Pages

------------------------------------------------------------------------

## 🔄 Project Methodology

### 1. Data Collection and Cleaning

The raw student fee records are prepared using Microsoft Excel.

The cleaning process includes:

-   Removing duplicate student records
-   Handling missing or blank fee values
-   Standardizing course and payment-status labels
-   Checking pending-fee calculations
-   Formatting date fields consistently

### 2. SQL Database and Analysis

The cleaned data is stored in a SQL database.

SQL queries are used to calculate:

-   Total fees
-   Collected fees
-   Pending fees
-   Collection percentage
-   Course-wise collection
-   Month-wise collection
-   Pending and partially paid student records

Important calculations include:

``` text
Pending Fee = Total Fees - Collected Fees

Collection % = (Collected Fees / Total Fees) × 100
```

### 3. Power BI Dashboard

The SQL output is connected to Microsoft Power BI.

The dashboard uses:

-   KPI cards
-   Charts
-   Tables
-   Slicers
-   Filters

These allow administrators to explore fee collection information
interactively.

### 4. Web Dashboard and Prediction

The project also includes a browser-based `index.html` dashboard.

The web application contains the dashboard interface, JavaScript logic,
charts, data handling, and prediction functionality in a single HTML
file.

Chart.js is used for visualizations and SheetJS/xlsx.js is used to read
Excel/CSV data directly in the browser.

------------------------------------------------------------------------

## 📁 Project Structure

``` text
Fee-payment-tracker-dashboard-and-prediction/
│
├── index.html
├── README.md
├── Fee_Collection_Tracker_Doc (1).pdf
└── Fee payment tracker dashboard and prediction.xlsx
```

### `index.html`

Contains the browser-based dashboard and prediction application.

### Excel Dataset

Contains the student fee records used for analysis.

### Project Report

`Fee_Collection_Tracker_Doc (1).pdf` contains the complete project
documentation, including the introduction, methodology, results,
limitations, and future scope.

------------------------------------------------------------------------

## 🗂️ Dataset Fields

The project dataset contains student-level fee information including:

  Field                  Description
  ---------------------- ---------------------------------
  Student ID             Unique identification number
  Student Name           Name of the student
  Course                 Course enrolled by the student
  Academic Year          Academic year of the fee record
  Total Fees             Total fee payable
  Collected Fees         Amount already paid
  Pending Fees           Remaining fee amount
  Payment Status         Paid, Partial Paid, or Pending
  Payment Date / Month   Date or month of payment

------------------------------------------------------------------------

## 📈 Dashboard Results

For the academic year **2024--25**, the project report presents the
following key performance indicators:

  KPI                              Value
  ----------------------- --------------
  Total Fees                ₹1,25,00,000
  Collected Fees              ₹87,45,000
  Pending Fees                ₹37,55,000
  Collection Percentage           69.96%
  Total Students                   1,250
  Total Payments                   2,345

The report also presents course-wise collection information,
payment-status distribution, monthly collection trends, and pending-fee
analysis.

------------------------------------------------------------------------

## 🔍 Business Insights

The dashboard helps users quickly understand:

-   How much total fee has been assigned.
-   How much fee has been collected.
-   How much fee is still pending.
-   The overall collection percentage.
-   Which courses contribute most to fee collection.
-   Which students have pending or partially paid fees.
-   How fee collection changes over time.
-   Which records may require further payment follow-up.

------------------------------------------------------------------------

## ⚠️ Limitations

The project documentation identifies the following limitations:

-   The dashboard is based on a static dataset for the 2024--25 academic
    year.
-   It is not connected to a continuously updating institutional
    database.
-   Automated student payment reminders are not currently implemented.
-   Data cleaning and validation are currently performed manually in
    Excel.
-   The prediction should be treated as an analytical screening signal
    rather than a guaranteed individual forecast.

------------------------------------------------------------------------

## 🔮 Future Scope

The project can be further enhanced by:

-   Integrating the system with a live student information system or
    ERP.
-   Automatically updating the SQL database when new payment
    transactions occur.
-   Adding automated email or SMS reminders for pending payments.
-   Using historical payment patterns for improved predictive analytics.
-   Adding role-based dashboard views for different departments and
    management users.

------------------------------------------------------------------------

## 🌐 GitHub Pages Deployment

This project is suitable for deployment using GitHub Pages because the
web dashboard is implemented as a single HTML file and does not require
a backend or build step.

### Steps

1.  Create a GitHub repository.
2.  Upload `index.html`.
3.  Upload this `README.md`.
4.  Upload the project documentation if required.
5.  Open **Settings → Pages**.
6.  Under **Build and deployment**, select **Deploy from a branch**.
7.  Select the `main` branch and `/ (root)`.
8.  Click **Save**.
9.  Open the GitHub Pages URL generated by GitHub.

------------------------------------------------------------------------

## 🔐 Data Privacy

If this repository is public, make sure that the uploaded dataset does
not contain real student personal or financial information.

For a public portfolio repository, use anonymized or sample data before
uploading student-level records.

------------------------------------------------------------------------

## 👩‍💻 Project Team

-   **Gopidi Rishitha**
-   **Banoth Rajendar**
-   **N Mahesh**
-   **K Sai Kumar**

### Project Guide

**Ms. Vijayata Ramateke**\
Assistant Professor, Department of Computer Science and Engineering

### Institution

**Siddhartha Institute of Technology & Sciences**\
Department of Computer Science and Engineering

------------------------------------------------------------------------

## 📄 Documentation

The complete project report is available in:

`Fee_Collection_Tracker_Doc (1).pdf`

It contains the project introduction, literature review, methodology,
dashboard results, conclusion, limitations, and future scope.

------------------------------------------------------------------------

## ⭐ Conclusion

The Fee Payment Tracker Dashboard and Prediction project demonstrates
how Excel, SQL, Power BI, and web technologies can be combined to
transform student fee records into meaningful analytical insights.

The system provides a centralized view of fee collection performance and
helps users identify pending payments, analyze collection trends, and
use payment-risk prediction as an additional decision-support feature.
