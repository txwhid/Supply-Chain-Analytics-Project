# Supply-Chain-Analytics-Project
This project demonstrates end-to-end data analytics skills by analyzing a supply chain dataset sourced from Kaggle. It includes data cleaning, transformation, and visualization to extract actionable business insights. Additionally, it showcases my skills in data cleaning, querying, and deriving insights to address real-world business questions. As a university student aspiring to become a Data Analyst, I designed this project to highlight my ability to work with data, manipulate databases, and generate actionable insights. The project demonstrates expertise in Excel, SQL, and Power BI.



## Project Workflow

### **1. Excel Data Cleaning and Transformation**

#### **What Was Done**
- **Data Cleaning:**
  - Removed inconsistencies and handled missing values in the dataset.
  - Corrected formatting issues to ensure a clean dataset for analysis.
- **Data Transformation:**
  - Created pivot tables to summarize insights across dimensions such as product categories and suppliers.
- **Visualizations:**
  - Generated charts to visualize revenue, product sales, supplier performance metrics, and trends.

#### **Key Insights from Excel**
1. **Revenue Insights:**
   - Skincare products generated the highest revenue, indicating higher demand or premium pricing.
   - Cosmetics and haircare showed moderate revenue, presenting opportunities for optimization.
2. **Supplier Analysis:**
   - Lead times varied significantly across suppliers, particularly for skincare products, potentially impacting customer satisfaction.
   - Shipping costs remained stable, but defect rates varied slightly, highlighting areas for quality improvement.
3. **Potential Supply Chain Optimizations:**
   - Standardizing lead times across suppliers could enhance consistency.
   - Strengthening quality control for certain product categories could reduce defect rates.

#### **Before and After Cleaning (Excel Workflow)**
- Before cleaning: The dataset had inconsistencies and missing values, requiring significant preprocessing.
 ![image1](https://github.com/user-attachments/assets/c1e49711-2911-4f96-8662-27389fc1778a)

  
- After cleaning: A clean dataset suitable for analysis and visualization.
  ![image7](https://github.com/user-attachments/assets/b33d198b-099a-468f-b8b1-41fad2b68fc6)

- Pivot Tables.
  ![image12](https://github.com/user-attachments/assets/3c74b22c-5b0b-40c9-b14c-1f857d84bdd5)

  




# Supply Chain Data Analysis with SQL:

## Project Overview
The objective of this project is to analyze a supply chain dataset to gain insights into sales performance, inventory management, supplier efficiency, and customer behavior. The dataset includes attributes such as product types, stock levels, lead times, revenue generated, shipping costs, and more.

### Dataset Summary
The dataset contains the following key columns:
- **Product Information**: Product type, SKU, price, availability.
- **Sales Data**: Number of products sold, revenue generated.
- **Inventory Data**: Stock levels, lead times, order quantities.
- **Shipping Data**: Shipping times, carriers, costs, transportation modes, routes.
- **Supplier Data**: Supplier name, location, production volumes, manufacturing lead time, manufacturing costs.
- **Quality Data**: Inspection results, defect rates.

## Steps Taken

### 1. Data Preparation and Import
1. The dataset was initially provided in a CSV file format.
2. Imported the CSV file into SQLite using DB Browser for SQLite.
3. Ensured proper data types were assigned to columns:
   - `REAL` for numeric values like price, revenue, and costs.
   - `INTEGER` for count data like stock levels and quantities sold.
   - `TEXT` for categorical data like product type and supplier name.

### 2. Data Cleaning
- Removed unnecessary rows and ensured no duplicate headers (e.g., `Column1`).
- Cast columns to the appropriate data types to allow for accurate numeric calculations.
- Removed invalid or empty rows (e.g., rows where `product_type` was `NULL` or `Column1`).

- <img width="560" alt="image21" src="https://github.com/user-attachments/assets/689ae78f-8888-403d-abcb-e53b0fec4cc4" />


### 3. SQL Queries for Analysis
The project involved writing advanced SQL queries to address key business questions:

#### **Sales and Revenue Analysis**
- **Total Revenue by Product Type:** Identify the most profitable product categories.
- 
 <img width="816" alt="image19" src="https://github.com/user-attachments/assets/c284ac46-4506-4213-a718-c076c8feebe5" />

- **Top 5 SKUs by Revenue:** Highlight the highest-performing products.
  
 <img width="816" alt="image19" src="https://github.com/user-attachments/assets/44d016cd-ef1e-491e-a120-5706eb188566" />

  **Average Revenue and Units Sold by Product Type:**
  
  <img width="788" alt="image5" src="https://github.com/user-attachments/assets/3a8250f4-a5c7-4072-90c5-46bf43caa698" />

  #### **Inventory and Stock Management**
  
  **Stock Levels by Product Type:**
  
  <img width="694" alt="image13" src="https://github.com/user-attachments/assets/b37d3c04-2554-4c45-bbdc-9f5979004a96" />

  **Products with Critical Stock Levels (<50 Units):**
  
  <img width="766" alt="image9" src="https://github.com/user-attachments/assets/0666274e-4f6c-4e57-ab30-04d7f474171b" />

  **Inventory Turnover Rate (Units Sold vs Stock Levels):**
  
  <img width="807" alt="image11" src="https://github.com/user-attachments/assets/c5729fce-be19-4f53-8cc1-b00aad769a95" />

  #### **Supplier and Shipping Performance**

  **Average Lead Time by Supplier:**
  
  <img width="730" alt="image6" src="https://github.com/user-attachments/assets/256a8052-e041-4b51-85fe-13d4c1ccd034" />

  **Supplier Performance: Total Revenue and Defect Rates:**
  
  <img width="792" alt="image15" src="https://github.com/user-attachments/assets/4900bc5f-2a65-43b2-8d34-3456acddbd17" />

  **Shipping Costs by Carrier:**
  
  <img width="767" alt="image4" src="https://github.com/user-attachments/assets/bb575a9e-5bab-4f46-8e57-ca8204f80c06" />

  **Efficiency of Shipping Modes:**
  
  <img width="763" alt="image17" src="https://github.com/user-attachments/assets/1bc04909-e6f6-4d98-8813-d24a1436c038" />

  #### **Customer and Market Insights**

  **Revenue by Customer Demographics:**

  <img width="720" alt="image18" src="https://github.com/user-attachments/assets/f1b1130a-a5d8-4312-b7ed-add2f77aeaa0" />

  **Most Popular Products (Highest Units Sold):**

  <img width="634" alt="image20" src="https://github.com/user-attachments/assets/54706f9f-a4fb-47be-97b5-2c741b24296f" />

  **Profit Analysis by Product Type:**

  <img width="729" alt="image2" src="https://github.com/user-attachments/assets/063e3f7a-2f2d-4ffd-b902-f33c39ebe9ef" />

  **Defect Rate Analysis by Product Type:**

  <img width="651" alt="image8" src="https://github.com/user-attachments/assets/710bc62d-fd4b-4223-8c2a-18394d432e2f" />

  **Supplier Performance Summary:**

  <img width="823" alt="image16" src="https://github.com/user-attachments/assets/97c95fc1-614a-42d3-963e-f67df3545900" />

  **Best Performing Routes by Transportation Mode:**

  <img width="748" alt="image3" src="https://github.com/user-attachments/assets/22e188f2-f5b2-463b-a76b-deb5990bd288" />

  **Overall Performance Summary:**

  <img width="762" alt="image10" src="https://github.com/user-attachments/assets/e1b329ef-acec-4f01-a274-5ac3fe6d75ce" />


  

  



  



  


  


  



  


  


  



  


  


  





### 4. Insights Derived
- **Skincare** products generated the highest revenue, followed by haircare and cosmetics.
- Certain suppliers with high defect rates also had slower lead times, indicating potential issues in quality control.
- Products with critical stock levels (<50 units) were flagged for restocking.
- Customer demographics showed non-binary customers contributed the highest revenue.

## Challenges Faced
- Ensuring proper data type conversion during the import process.
- Handling rows with invalid or missing data (e.g., `Column1`).
- Optimizing queries for better performance on large datasets.

## Technologies Used
- **SQLite**: Database management and query execution.
- **DB Browser for SQLite**: Data import, schema management, and query execution.

## Key Takeaways
- Developed a deep understanding of SQL for data manipulation and analysis.
- Gained experience in data cleaning, transformation, and visualization preparation.
- Improved problem-solving skills by addressing real-world business questions using SQL.

## Next Steps
The next phase of this project involves using **Power BI** to visualize the insights derived from the SQL queries. This will include:
- Dynamic dashboards showing revenue, inventory, and supplier performance.
- Interactive filters for product type, location, and customer demographics.
- Advanced charts like bar graphs, pie charts, and heatmaps to present the findings effectively.

## How to Use This Repository
1. Clone the repository.
2. Import the SQL script into your SQLite database.
3. Run the queries to reproduce the results.
