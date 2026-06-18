# 📊 Sales Data Transformation and Data Modeling using Power BI

The project demonstrates best practices in data preparation, transformation, and data modeling that support effective business intelligence and decision-making.

## 📑 Table of Contents
* [Project Overview](#-project-overview)
* [Data Sources & Architecture](#-data-sources--architecture)
* [Data Transformation ETL](#-data-transformation-etl)
* [Data Model DAX](#-data-model-dax)
* [Key Insights](#-key-insights)
* [How To Use](#-how-to-use)

---

## 🎯 Project Overview

* **Business Problem:**
  This project focuses on transforming raw sales data into a structured and analysis-ready format using Power Query and building an efficient data model in Power BI.
  
* **Objective:**
  The Sales Data Transformation and Data Modeling assignment is to perform data preparation and data modeling using Power BI. The dataset contains multiple related files representing order-level, product-level, and sales target information.

  The focus of this assignment is on data import, transformation, cleansing, aggregation, and relationship modelling using Power BI and Power Query Editor, while ensuring consistency,
accuracy, and business relevance of the prepared data model.
.
* **Target Audience:**
  Identify the primary users of Executive Leadership, Customers and Sales Operations.

## 🗃️ Data Sources & Architecture
* **Source Systems:** Text/Csv files.
* **Data Volume:** Maximum Thousand Five Hundred rows are listed in the files.
* **Storage Mode:** Using Import Mode.

## ⚙️ Data Transformation (ETL)
* **Tool Used:** Power Query Editor.
* **Key Cleanups:** Row Limiting & Data Type, Text Formatting, Merging Data using Joins,andling Missing Data & Duplicate Data, Sorting and Filtering Data.
* **Custom Functions:**
    1.	To find the Profit Margin  
               Formula: Profit / Amount
    2.	To find the Profit Status

               Formula:
               ■ Profit < 0 → Loss 
               ■ Profit = 0 → Break-Even 
               ■ Profit > 0 → Profit


## 🧠 Data Model & DAX
* **Model Type:** This is Star Schema.
* **Fact Tables:** Order details table.
* **Dimension Tables:** List of Orders and Sales target Tables.


## 💡 Key Insights
* **Trend A:** First major operations of Data Preparation, Data Cleaning and Data Aggregations are accomplished.
* **Trend B:** Data Integration and Data Modeling are generated.
* **Recommendation:** Translating business logic into data models.

## 🚀 How To Use
1. **Prerequisites:**
   Ensure you have the latest Power BI Desktop installed.
   Prior knowledge in Power BI Interface operations.
   
3. **File Formats:** Clone the repository to access the `Sales Data Transformation and Data Modeling.pbix` file.
   
5. **Data Refresh:** Change the source path under **Data Source Settings** to point to your data files.

  
