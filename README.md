# Waze User Churn Analysis

This repository contains my **Course 1 Portfolio Project** from the **Google Advanced Data Analytics Professional Certificate**.

## Project Overview

The objective of this project is to inspect, organize, and summarize a synthetic Waze dataset before exploratory data analysis (EDA) and machine learning.

The project follows the **PACE** workflow (Plan, Analyze, Construct, Execute) and focuses on understanding the structure and quality of the data.

## Dataset

The dataset contains:

* **14,999 user records**
* **13 variables**
* User activity, driving behavior, device type, and churn status

The dataset is synthetic and was created for educational purposes in partnership with Waze.

## Tasks Completed

* Imported the dataset using pandas
* Inspected the dataframe structure
* Examined data types
* Identified missing values
* Generated descriptive statistics
* Compared churned and retained users
* Created additional analytical variables:

  * Kilometers per drive
  * Kilometers per driving day
  * Drives per driving day
* Analyzed device distribution
* Prepared an executive summary for stakeholders

## Tools & Technologies

* Python
* Jupyter Notebook
* pandas

## Key Findings

* The dataset contains **700 missing values**, all in the `label` column.
* Missing values appear to be randomly distributed.
* Approximately **64.5%** of users use **iPhone**, while **35.5%** use **Android**.
* Retained users were active on significantly more days than churned users.
* Churned users tended to drive longer distances and complete more drives within fewer days.
* Device type showed no meaningful relationship with user churn.

## Repository Contents

* `Course_1_Waze_Project.ipynb` — Jupyter Notebook
* `Executive_Summary.pdf` — Project executive summary
* `PACE_Strategy_Document.pdf` — Project planning document
* `README.md` — Project documentation

## Skills Demonstrated

* Data inspection
* Data cleaning
* Exploratory data analysis (EDA)
* Descriptive statistics
* Data storytelling
* Business communication
* Python programming
* pandas

---

**Certificate Program:** Google Advanced Data Analytics Professional Certificate

**Course:** Foundations of Data Science
