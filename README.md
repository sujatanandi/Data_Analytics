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

![Get Data](https://prod-files-secure.s3.us-west-2.amazonaws.com/456fe8c2-8771-43d9-87f2-a749cf9e4634/62c456ec-b64d-431d-95da-ed7d352757b4/image.png)

---

### 2. Choose **CSV** and click **Connect**

![Connect CSV](https://prod-files-secure.s3.us-west-2.amazonaws.com/456fe8c2-8771-43d9-87f2-a749cf9e4634/ace93f4f-b3de-467b-8294-7df87c17ac9d/image.png)

---

### 3. Load the `AdventureWorks_Territory_Lookup.csv` file

![Load CSV File](https://prod-files-secure.s3.us-west-2.amazonaws.com/456fe8c2-8771-43d9-87f2-a749cf9e4634/238ef14b-1abd-4ba1-a8ae-4cc64de74b4d/image.png)

---

### 4. Click **Transform Data** to enter Power Query Editor

![Transform Data](https://prod-files-secure.s3.us-west-2.amazonaws.com/456fe8c2-8771-43d9-87f2-a749cf9e4634/2d833926-f194-44fd-ab6c-def44bb67ed4/image.png)

---

### 5. Repeat for `AdventureWorks_Product_Lookup.csv`

![Repeat Load](https://prod-files-secure.s3.us-west-2.amazonaws.com/456fe8c2-8771-43d9-87f2-a749cf9e4634/b7329a04-4226-465b-a2ba-ae75165d1ab0/image.png)

---

### 6. Check the **M-code** behind the scenes

![M-code](https://prod-files-secure.s3.us-west-2.amazonaws.com/456fe8c2-8771-43d9-87f2-a749cf9e4634/43bf3b45-e0d7-4b18-a3ed-a61c4ee663f7/image.png)

---

### 7. View **Applied Steps** in the query settings

Power BI automatically detects column types based on the first 200 rows.

![Applied Steps](https://prod-files-secure.s3.us-west-2.amazonaws.com/456fe8c2-8771-43d9-87f2-a749cf9e4634/9341a262-6c4d-4a37-8233-368e7be6c33e/image.png)

---

### 8. Manually convert "ProductCost" and "ProductPrice" to currency

Use **Fixed Decimal Number**, rename the step to `Currency`.

![Convert to Currency](https://prod-files-secure.s3.us-west-2.amazonaws.com/456fe8c2-8771-43d9-87f2-a749cf9e4634/9382dae6-c869-4a76-b3f8-366eea5c07de/image.png)

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

If you found this helpful or want to collaborate on data-related projects, let’s connect on [LinkedIn](https://www.linkedin.com/in/your-profile)!
