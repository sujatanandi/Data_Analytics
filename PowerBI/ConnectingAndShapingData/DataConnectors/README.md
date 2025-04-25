# 🔍 Power BI Data Source Connection Demo

Welcome! This repository demonstrates how **Power BI** can connect to a variety of data sources and perform basic transformations using the **Power Query Editor**.

Whether you're new to Power BI or just exploring best practices, this guide walks you through a simple example helping you understand the import, transform, and load process in a visual and easy-to-follow format.

---

## 🔗 What Power BI Can Connect To

Power BI supports connections to virtually any type of data source, including:

- 📄 **Flat files & folders** (CSV, TXT, XLSX, etc.)
- 🗃️ **Databases** (SQL Server, Oracle, IBM DB2, Access, etc.)
- 🧩 **Power Platform** (Datamarts, Dataflows, Dataverse, etc.)
- ☁️ **Azure Services** (Azure SQL, Analysis Services, Databricks, etc.)
- 🌐 **Online Services** (SharePoint, GitHub, Dynamics 365, Google Analytics, Salesforce, Power BI Service, etc.)
- ⚙️ **Others** (Web, R scripts, Spark, Hadoop, OData feeds, etc.)

---

## 🛠️ Step-by-Step Guide (With Screenshots)

### 1. Click **Get Data**

![image1](https://github.com/user-attachments/assets/78682475-bd1f-4e1a-9583-2da53a69f4eb)

---

### 2. Choose **CSV** and click **Connect**

![image2](https://github.com/user-attachments/assets/efb9f52d-ffab-40e7-a20b-c68227e6bf61)

---

### 3. Load the `AdventureWorks_Territory_Lookup.csv` file

![image2](https://github.com/user-attachments/assets/b893e7cf-b05e-4950-8caa-68649fa9166e)

---

### 4. Click **Transform Data** to enter Power Query Editor

![image4](https://github.com/user-attachments/assets/04e9f431-e24e-4a72-b8cc-96f3d6e19e57)

---

### 5. Repeat for `AdventureWorks_Product_Lookup.csv`

![image5](https://github.com/user-attachments/assets/d999b279-35df-4dd2-a5b4-c0044652019e)

---

### 6. Check the **M-code** behind the scenes

![image6](https://github.com/user-attachments/assets/0b72cde0-502f-4343-ad0e-7763f3436356)

---

### 7. View **Applied Steps** in the query settings

Power BI automatically detects column types based on the first 200 rows. Eg. If integer values are entered in txt format, PBI will convert them to int datatype.

![image7](https://github.com/user-attachments/assets/d67f0aba-6feb-491f-87c2-48bf9cff9131)

---

### 8. Manually convert "ProductCost" and "ProductPrice" to currency

Use **Fixed Decimal Number**, rename the step to `Currency`.

![image8](https://github.com/user-attachments/assets/17dcffe4-69fd-449f-91c1-15a12240f71d)

---

### 9. Click **Close & Apply** to load tables into the data model

You're all set! Your tables are now ready for visualization and analysis.

---

## 🧠 Why This Matters

This walkthrough showcases how easy and powerful Power BI is when it comes to:

- Connecting multiple sources  
- Understanding and shaping data  
- Building a clean, scalable data model

Whether you're presenting data to stakeholders or building enterprise-level dashboards, these steps form the foundation of every great Power BI project.

