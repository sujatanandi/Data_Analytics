# Data Profiling with Power BI

This repository demonstrates how to use **Power BI’s Data Profiling tools** — including **Column Quality**, **Column Distribution**, and **Column Profile** — to explore the quality, composition, and distribution of your data before loading it into the Power BI front-end.

These tools help ensure your data is clean, accurate, and ready for analysis.

---

## 📋 What You’ll Learn
✅ How to enable and use Power BI’s data profiling tools  
✅ How to identify and remove errors and empty rows  
✅ How to inspect and understand column distributions and profiles  

---

## 🔷 Steps

### 1️⃣ Load the Data
- Load the **AdventureWorks Customer Lookup** dataset into Power Query.
- Follow the recommended best practices (e.g., promote headers, correct data types).

---

### 2️⃣ Enable Column Quality
- Go to the **View** menu.
- Check the **Column Quality** box.  
<img width="1020" alt="image (1)" src="https://github.com/user-attachments/assets/027ccfcc-4001-4bf4-95d1-23701c733159" />

---

### 3️⃣ Profile All Rows
- By default, Power BI only profiles the first 1000 rows.
- To profile the **entire dataset**, click the option in the **bottom left corner** of the Power Query window.
<img width="729" alt="image (2)" src="https://github.com/user-attachments/assets/9dbe44e3-74d5-4b82-a124-77e93c810572" />

---

### 4️⃣ Identify & Remove Errors
- Hover over the column quality indicators to see errors.
- Power BI suggests ways to clean the data —> click **Remove Errors**.
- Similarly, filter out **Empty rows**.
<img width="349" alt="image (3)" src="https://github.com/user-attachments/assets/a3f5c521-eb4c-436d-bed2-eedf6633b998" />

---

### 5️⃣ Inspect Errors Before Cleaning
- If you want to review errors before removing them:
  - Right click the column and select **Keep Errors**.
  - Open each error to understand what caused it.
<img width="835" alt="image (4)" src="https://github.com/user-attachments/assets/d369f434-612d-4648-8c77-7eec0371e2a5" />

---

### 6️⃣ Use Column Distribution & Profile
- Enable **Column Distribution** and **Column Profile** to analyze the data more deeply.
- These tools help you spot outliers, validate distributions, and guide further cleaning or transformation.
<img width="1003" alt="image (5)" src="https://github.com/user-attachments/assets/6ab61a12-6f29-4a8f-bc25-1bb8803853c7" />

---

## 📌 Notes
- Data profiling is performed in Power Query Editor.
- Profiling large datasets may affect performance, use wisely on very big data.
- Clean data improves the reliability of your reports & dashboards.

