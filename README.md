# 🛒 Target E-commerce SQL Business Case Analysis  

## 📌 Overview  
This project explores the **Target e-commerce dataset** (Brazil region) using SQL to derive **business insights and recommendations**.  
It focuses on **customer behavior, orders, payments, freight, and delivery performance** to help optimize operations, marketing, and logistics.  

---

## 📂 Dataset & Tools  
- **Dataset**: Target E-commerce data (customers, orders, payments, order items).  
- **Tool Used**: Google BigQuery (SQL).  
- **Analysis Type**: Exploratory Data Analysis (EDA) + Business Case Recommendations.  

---

## ⚙️ Analysis Workflow  

### **I. Exploratory Analysis**
- Checked **data types** and missing values.  
- Extracted **time range of orders**.  
- Counted **distinct customer cities & states**.  

**Key Insight**:  
Data spans multiple years with strong geographical coverage across Brazil.  

**Business Recommendation**:  
- Add proper indexing & constraints for better query performance.  
- Strengthen delivery partnerships in top-performing states.  

---

### **II. Order Trends & Seasonality**
- Yearly growth of orders (2016 → 2018).  
- Monthly seasonality patterns.  
- Peak order times (Afternoon, Night).  

**Key Insight**:  
Orders increased **13,600% between 2016–2017**, peaking in afternoons.  

**Business Recommendation**:  
- Align marketing with peak months & time slots.  
- Scale infrastructure for afternoon peak load.  

---

### **III. Customer & Regional Analysis**
- Orders by state (monthly).  
- Distribution of customers across states.  

**Key Insight**:  
Majority from **São Paulo & Rio de Janeiro**; smaller states show emerging growth.  

**Business Recommendation**:  
- Run **geo-targeted ads & localized offers**.  
- Partner with regional influencers.  

---

### **IV. Economic Impact (Sales & Freight)**
- Order cost growth (2017 → 2018).  
- Total & average order price per state.  
- Total & average freight per state.  

**Key Insight**:  
Remote states (Amazonas, Acre, Amapá) have **high freight costs**.  

**Business Recommendation**:  
- Offer **bulk order incentives** in high freight states.  
- Open **regional warehouses** to cut costs.  

---

### **V. Delivery Performance**
- Average delivery times.  
- States with highest & lowest delivery delays.  
- Difference between **estimated vs actual delivery**.  

**Key Insight**:  
Some states deliver **20 days earlier than estimated** → estimation models are off.  

**Business Recommendation**:  
- Update estimated delivery models with **real data**.  
- Promote **fast regions** with next-day delivery campaigns.  

---

### **VI. Payments**
- Orders by **payment method** (Credit, Debit, UPI, Voucher).  
- Orders by **installments**.  

**Key Insight**:  
- **Credit card** dominates, but **UPI is rising fast**.  
- Majority prefer **one-time payment**.  

**Business Recommendation**:  
- Promote **UPI cashback offers**.  
- Introduce **0% EMI for high-ticket items**.  

---

## 📊 Business Outcomes  
✔ Improved **inventory planning** for seasonal spikes.  
✔ Enhanced **marketing strategies** aligned with demand.  
✔ Reduced **freight costs** with regional distribution.  
✔ Better **delivery time accuracy** → higher customer satisfaction.  
✔ Optimized **payment offers** for different customer segments.  

---

## 🚀 How to Run Queries  
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/target-ecommerce-sql-analysis.git
   cd target-ecommerce-sql-analysis
