# 📊 Blinkit Dashboard Analysis  
### Sales, Inventory & Customer Insights using Google Looker Studio  

---

## 🟡 Introduction  
In the quick-commerce industry, data plays a crucial role in optimizing operations, improving customer satisfaction, and maximizing revenue.  

This project focuses on building a **multi-page interactive dashboard** to analyze Blinkit’s business performance across:  
- Sales & Revenue  
- Inventory & Stock Efficiency  
- Customer Behavior & Feedback  

---

## 💻 Tech Stack  
- Data Source: Blinkit Dataset  
- Data Preparation: Google Sheets  
- Visualization Tool: Google Looker Studio  

---


## Data Dictionary

 | **Column Name**    | **Description**                                 | **Data Type** |
| ------------------ | ----------------------------------------------- | ------------- |
| order_id           | Unique identifier for each order                | String        |
| customer_id        | Unique identifier for each customer             | String        |
| product_id         | Unique identifier for each product              | String        |
| product_name       | Name of the product                             | Categorical   |
| category           | Product category (Dairy, Snacks, Grocery, etc.) | Categorical   |
| order_date         | Date when the order was placed                  | Date          |
| quantity           | Number of units ordered                         | Integer       |
| price              | Price per unit of product                       | Float         |
| total_amount       | Total order value (price × quantity)            | Float         |
| payment_method     | Mode of payment (UPI, Card, Wallet, Cash)       | Categorical   |
| delivery_time      | Time taken for delivery (in minutes)            | Integer       |
| delivery_status    | Order status (Delivered, Cancelled, Pending)    | Categorical   |
| stock_available    | Available stock for the product                 | Integer       |
| stock_received     | Quantity of stock received                      | Integer       |
| damaged_stock      | Quantity of stock damaged                       | Integer       |
| warehouse_location | Location of warehouse                           | Categorical   |
| customer_rating    | Rating given by customer (1–5)                  | Float         |
| feedback_category  | Type of feedback (Delivery, Service, Product)   | Categorical   |
| customer_segment   | Customer type (New, Regular, Premium, Inactive) | Categorical   |


---- 

## 📄 Dashboard Pages  

---

### 🔹 Page 1: Executive Overview & KPI Metrics  

![Inventory](inventory_stock/page2.png)

**Key Metrics:**  
- Total Revenue: ₹4.97M  
- Total Orders: 5,000  
- Average Order Value: ₹994.48  

**Insights:**  
- Essential products dominate revenue  
- Strong customer demand  
- Opportunity in low-performing categories  

---

### 🔹 Page 2: Inventory & Stock Performance  

![Customer](customer_insights/page3.png)

**Key Metrics:**  
- Total Stock: 7.7M+  
- Damaged Stock: 80K+  

**Insights:**  
- High damage in perishable goods  
- Logistics issues affect even non-perishables  
- Inventory inefficiency leads to revenue loss  

---

### 🔹 Page 3: Customer Insights & Behavior  
![Executive Overview](executive_overview/page1.png)

**Key Metrics:**  
- Total Customers: 5,328  
- Total Orders: 55,905  
- Average Rating: 3.34  

**Insights:**  
- High engagement but moderate satisfaction  
- Delivery & service are key issues  
- Retention opportunity exists  

---

## 🛠️ Tools & Workflow  

1. Data Collection – Blinkit dataset  
2. Data Cleaning – Google Sheets  
3. Dashboarding – Google Looker Studio  
4. Analysis – Business insights & trends  

---

## 📈 Key Insights  

- Essential goods drive revenue  
- Inventory damage causes losses  
- Customer satisfaction needs improvement  

---

## 🚀 Recommendations  

- Improve inventory handling  
- Optimize delivery operations  
- Focus on customer retention  

---

## 🔗 Project Links  

- Live Dashboard: (https://datastudio.google.com/u/0/reporting/726c6be0-f06b-4b6c-965a-bf0d3fd2e0de/page/ZXawF)  
- Dataset: (https://www.kaggle.com/datasets/akxiit/blinkit-sales-dataset)  

---

## ⭐ If you like this project  
Give it a ⭐ on GitHub!
