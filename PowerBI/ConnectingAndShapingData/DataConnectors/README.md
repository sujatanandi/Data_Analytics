# 🔍 Power BI Data Source Connection Demo

Welcome! This repository demonstrates how **Power BI** can connect to a variety of data sources and perform basic transformations using the **Power Query Editor**.

Whether you're new to Power BI or just exploring best practices, this guide walks you through a simple example using **AdventureWorks CSV files**, helping you understand the import, transform, and load process in a visual and easy-to-follow format.

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

![image](https://github.com/user-attachments/assets/b17c91fa-e03c-445c-bfc5-bad9e7d57313)


---

### 2. Choose **CSV** and click **Connect**

![image (1)](https://github.com/user-attachments/assets/48ee9f0a-ffff-4c24-87ed-2120ae0b4878)


---

### 3. Load the `AdventureWorks_Territory_Lookup.csv` file

![image (2)](https://github.com/user-attachments/assets/2c719c85-caaf-4a1c-9215-54e74b32e914)


---

### 4. Click **Transform Data** to enter Power Query Editor

![image (3)](https://github.com/user-attachments/assets/54a229f4-87df-42bf-adbd-0a41257a9aa5)


---

### 5. Repeat for `AdventureWorks_Product_Lookup.csv`

![image (4)](https://github.com/user-attachments/assets/625f8af0-14ac-464d-82d3-7300efe75e94)


---

### 6. Check the **M-code** behind the scenes

![image (5)](https://github.com/user-attachments/assets/67d07b85-6313-4e6b-98b6-639469ad2e14)


---

### 7. View **Applied Steps** in the query settings

Power BI automatically detects column types based on the first 200 rows.

![image (6)](https://github.com/user-attachments/assets/0322ea99-fabd-42d2-a256-4e1c9328282d)


---

### 8. Manually convert "ProductCost" and "ProductPrice" to currency

Use **Fixed Decimal Number**, rename the step to `Currency`.

![image (7)](https://github.com/user-attachments/assets/332ad9cd-f175-4f81-b11c-16eb1e3d7600)

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

---

## 🔗 Connect with Me

If you found this helpful or want to collaborate on data-related projects, let’s connect on [LinkedIn](https://www.linkedin.com/in/sujatanandi/)!
