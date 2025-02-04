# iGnosis-Tech-ML-Assignment
# **Customer Segmentation & Product Analysis**
## **Identifying Profitable Products and Loyal Customer Characteristics**

### **Overview**
This project aims to help iGnosis Tech’s marketing department identify the most profitable products and key customer segments. By analyzing transaction data, we determine which products generate the highest revenue and what characteristics define the most loyal customers. This analysis provides insights into customer purchasing behavior and assists in refining marketing strategies.

### **Objectives**
- Identify the **top 3 most profitable products**.
- Analyze customer segmentation based on **lifestage, spending behavior, and brand preferences**.
- Understand factors influencing **customer loyalty and repeat purchases**.
- Provide actionable insights for **marketing and promotional strategies**.

### **Dataset**
The dataset consists of two files:
1. **transaction_data.csv** – Contains sales transaction details.
2. **purchase_behaviour.csv** – Provides customer information including loyalty card numbers, life stage, and premium status.

### **Implementation Steps**
1. **Data Loading & Cleaning**:
   - Load both datasets.
   - Handle missing values and ensure correct data types.
2. **Data Merging**:
   - Combine transaction and customer data based on loyalty card numbers.
3. **Profitability Analysis**:
   - Identify the top 3 products generating the highest sales revenue.
4. **Customer Segmentation**:
   - Analyze the purchasing behavior of the most loyal customers.
   - Determine the distribution of customer life stages and spending patterns.
5. **Visualization**:
   - Use bar plots and count plots to present insights.

### **Key Findings**
1. **Brand Loyalty & Product Preference**:
   - Popular brands like **Dorito and Smiths** dominate sales, indicating strong brand loyalty.
   - Customers prefer **classic flavors** like **Original and Salt & Vinegar**.
   
2. **Family-Oriented Purchasing Trends**:
   - **Older families and young families** make up the majority of repeat buyers.
   - These groups often purchase in **bulk**, aligning with the larger pack sizes of top-selling products.

3. **Spending Behavior**:
   - **Budget-conscious customers** are the largest segment, emphasizing affordability.
   - **Premium buyers** tend to prefer gourmet/exclusive flavors, though these are not the top-selling items.

4. **Impact of Promotions & Discounts**:
   - **High sales** of certain products may be driven by **discounts and promotional offers**.
   - Budget buyers are particularly influenced by **seasonal discounts and combo deals**.

### **Technologies Used**
- **Python** (Pandas, NumPy)
- **Data Visualization** (Matplotlib, Seaborn)
- **Jupyter Notebook**
