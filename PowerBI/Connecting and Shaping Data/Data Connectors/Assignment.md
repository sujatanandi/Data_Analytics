# 📊 Power BI Transformation Task

## 🧩 Problem Statement

Create two new queries to connect to the **Product Category Lookup** and **Product Subcategory Lookup** CSV files and make the following modifications to the **Product** table.

---

## 🎯 Key Objectives

1. Create queries to connect to the two new `.csv` files.
2. Name your queries:  
   - `Product Category Lookup`  
   - `Product Subcategory Lookup`
3. Promote headers and confirm all data types are correct.
4. Extract all characters **before the dash ("-")** in the `Product SKU` column. Name the new column `SKU Type`.
5. Update the `SKU Type` calculation to extract characters **before the second dash** instead.
6. Replace all `0`s in the `Product Style` column with `"NA"`.
7. Close and load the queries to your data model.

---

## 🛠️ Solution Steps

### 1. Load CSV Files
- Import both CSV files into Power BI.
- Rename them to:  
  - `Product Category Lookup`  
  - `Product Subcategory Lookup`
- Ensure headers are promoted and data types are correct.

---

### 2. Extract SKU Type (Before Dash)

- Navigate to the **Product Lookup** query.
- Select the `Product SKU` column.
- Go to **Add Column** → **Extract** → **Text Before Delimiter**.

<img width="709" alt="image" src="https://github.com/user-attachments/assets/0eefc12d-4d5d-4dbc-bb02-760ffa0cb7b7" />


- In the dialog box, type `-` as the delimiter and click **OK**.
- Rename the new column to `SKU Type`.

<img width="655" alt="image (1)" src="https://github.com/user-attachments/assets/0748755c-1d0a-458c-90dc-9158bcd71caa" />


---

### 3. Update to Extract Before Second Dash

- In the **Applied Steps** panel, click the gear icon on the "Extracted Text Before Delimiter" step.
- Under **Advanced Options**, change the **Occurrence** value from `0` to `1` to skip the first dash and extract before the second dash.

![image (2)](https://github.com/user-attachments/assets/0308776e-4144-45c7-b556-1b76d30b3af9)


---

### 4. Replace `0` with `NA` in Product Style

- Select the `Product Style` column.
- Go to **Transform** → **Replace Values**.

![image (3)](https://github.com/user-attachments/assets/50baaf0b-6596-4173-a2aa-c98f607dc74f)


- In the dialog box:
  - **Find**: `0`
  - **Replace With**: `NA`
- Click **OK**.
<img width="660" alt="image (4)" src="https://github.com/user-attachments/assets/1544667d-5a63-4706-9657-2c06739ff8e6" />

---

### 5. Final Step

- Click **Close & Apply** to save your changes and load the data model.

---

✅ *All objectives have been completed successfully.*
