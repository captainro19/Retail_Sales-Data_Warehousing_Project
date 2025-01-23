## Retail-Sales-Data-Warehousing-Project
### Data Warehouse and Analytical Queries Setup
**Objective**: Designed and implemented a data warehousing solution to analyze retail sales data, enabling efficient inventory management and sales trend forecasting.  

#### **Key Contributions**:  
1. **OLTP Schema Design**:  
   - Created an OLTP schema using SQL to store raw transactional data, including tables for shops, items, item categories, and sales transactions.  
   - Enabled efficient storage and retrieval of retail sales data for further processing and analysis.  

2. **Dimensional Modeling & Data Warehousing**:  
   - Designed a dimensional model schema with dimension tables (`shops_dim`, `item_dim`, `date_dim`) and a fact table (`sales_fact`) to support analytical queries.  
   - Transformed and populated the data warehouse by extracting, cleaning, and loading data from the OLTP schema.  

3. **Analytical Queries & Insights**:  
   - Developed 10+ SQL views for advanced analytics, including:  
     - Monthly, quarterly, and yearly sales trends.  
     - Top-performing shops and items by sales and units sold.  
     - Rolling 3-month sales and year-over-year growth analysis.  
     - Correlation between item price and units sold.  
   - Enabled stakeholders to gain actionable insights into sales performance, customer behavior, and inventory management.  

4. **Predictive Analytics**:  
   - Conducted exploratory data analysis (EDA) and built a machine learning model to forecast future sales, helping retailers optimize inventory and reduce costs.  

#### **Technical Stack**:  
- **Database**: PostgreSQL  
- **Tools**: SQL, Python (for EDA and machine learning), Jupyter Notebooks  
- **Data Sources**: Kaggle datasets (`sales_train.csv`, `items.csv`, `item_categories.csv`, `shops.csv`)  

#### **Impact**:  
- Provided a scalable data warehousing solution for retail sales analysis, improving decision-making and inventory management.  
- Delivered actionable insights through advanced analytics and predictive modeling, reducing inventory costs and increasing sales efficiency.  
![image](https://github.com/user-attachments/assets/885bc85e-f03c-4ad1-a34d-5336a1e250ed)
