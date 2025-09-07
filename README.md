# 📊 UPI Transactions Data Analysis Dashboard  

### Comprehensive Insights into Customer Behavior, Payment Patterns, and Merchant Performance  

### 🔗 Dashboard Link: *(https://app.powerbi.com/view?r=eyJrIjoiZDVlODA0OGEtNjQwMy00ZTY5LTg2OTktMjgzNjM2MzI1OGJiIiwidCI6IjEzOWQ5NmE0LWUxMzktNDZkMy05MDkwLTU0ZDMxNTBlM2NhMiJ9)*  

---

![Dashboard Preview](https://github.com/user-attachments/assets/385c50ff-dcd4-4321-bcb3-74a351a2af5d) 

![Dashboard Preview](https://github.com/user-attachments/assets/869e5187-a433-4050-bd50-d2493c6f0828)

![Dashboard Preview](https://github.com/user-attachments/assets/7f7bb284-84cd-4a6f-b1ac-7fd5c69c0b46)

![Dashboard Preview](https://github.com/user-attachments/assets/663a9379-4997-472b-8343-546630a363d8)

![Dashboard Preview](https://github.com/user-attachments/assets/4f8c2dce-dbc8-4b40-abf8-fb1864ba5a48)

![Dashboard Preview](https://github.com/user-attachments/assets/eea3e52c-1ae5-4373-a436-4d1427e3bf90)

![Dashboard Preview](https://github.com/user-attachments/assets/59617081-f476-4058-a2e4-de3bdf4476c0)

---


### 🔗 Dashboard Link: *(https://app.powerbi.com/view?r=eyJrIjoiZDVlODA0OGEtNjQwMy00ZTY5LTg2OTktMjgzNjM2MzI1OGJiIiwidCI6IjEzOWQ5NmE0LWUxMzktNDZkMy05MDkwLTU0ZDMxNTBlM2NhMiJ9 )* 


---

## ❓ Problem Statement  

With the rapid adoption of **UPI (Unified Payments Interface)** in India, millions of digital transactions take place daily across food delivery, shopping, travel, and bill payments.  
While UPI has transformed digital payments, businesses and banks face challenges such as:  

- Understanding **which customer segments** (age, gender, city, device) contribute most to transactions.  
- Tracking **merchant performance** and identifying which platforms (Zomato, Amazon, Flipkart, IRCTC, Swiggy) dominate digital payments.  
- Monitoring **transaction success vs failure rates** to identify bottlenecks in payment processing.  
- Analyzing **monthly trends** to detect seasonal peaks and optimize campaigns.  
- Identifying **key purposes** (shopping, food, travel, bill payments) driving UPI adoption.  

📌 Without structured analysis, stakeholders struggle to make **data-driven decisions** regarding customer targeting, merchant partnerships, and system performance improvements.  

---

## 🎯 Business Objective  

The goal of this project is to design an **interactive analytics dashboard** that provides:  

1. **Customer Behavior Insights** – Breakdown of transaction amounts by age, gender, city, and device type.  
2. **Merchant Performance Analysis** – Identification of top-performing merchants and their contribution to UPI volume.  
3. **Transaction Monitoring** – Success and failure rates to assess payment reliability.  
4. **Monthly Trends & Seasonality** – Visualization of transaction patterns across months to detect peaks and dips.  
5. **Purpose-Based Spending Analysis** – Distribution of UPI usage across shopping, food, travel, bill payments, and others.  

✅ This enables **business leaders, banks, and merchants** to make informed decisions on:  
- Targeting the right customer segments.  
- Optimizing merchant partnerships.  
- Improving payment success rates.  
- Designing marketing campaigns aligned with seasonal demand.  

---

## 🔍 Key Questions Answered  

This dashboard was designed to answer critical business questions such as:  

1. **Customer Demographics**  
   - Which **age group** contributes the highest transaction value?  
   - How does **gender** influence transaction patterns?  
   - Which **cities and device types** dominate UPI usage?  

2. **Merchant Performance**  
   - Which merchants handle the highest transaction volumes?  
   - What share of total transactions does each merchant contribute?  

3. **Transaction Reliability**  
   - What is the **overall success rate** of UPI transactions?  
   - Which banks or payment methods show higher failure rates?  

4. **Monthly & Seasonal Trends**  
   - How do transactions fluctuate across **months of 2024**?  
   - Are there identifiable **peaks during festive or seasonal periods**?  

5. **Purpose of Transactions**  
   - What are the most common use cases of UPI? (Shopping, Food, Travel, Bill Payments, Others)  
   - How much does each purpose contribute to the total transaction value?  

---

## ⚙️ Steps Followed  

### **Step 1 – Data Extraction** 🗄  
- Gathered UPI transaction data (20M+ INR equivalent).  
- Key attributes: Transaction Amount, Date, Purpose, Merchant, Age, Gender, City, Device, Bank.  
- Verified **data completeness and consistency** with transaction totals.  

### **Step 2 – Data Loading in Power BI** 📥  
- Imported dataset into **Power BI Desktop**.  
- Checked data types (date, numeric, categorical).  
- Built relationships between **Customer ↔ Transaction ↔ Merchant ↔ Bank** tables.  

### **Step 3 – Data Quality Check** ✅  
- Used **Power Query** to:  
  - Remove duplicates and nulls.  
  - Standardize merchant and purpose categories.  
  - Normalize currencies for consistent reporting.  

### **Step 4 – Data Transformation** 🔄   
- Built **DAX Measures**:  
  - 💳 Total Transaction Amount = ₹20M+  
  - 🔄 Total Transactions = 20K  
  - 💰 Average Transaction = ₹994  
  - ✅ Success Rate = 80%
 
---

### 👥 Customer Segmentation (Age Groups)  

To better analyze transaction behavior, customers were segmented into age groups:  

- **21–25 (Starters):** Early career, lower spend, exploring digital payments.  
- **26–35 (Young Professionals):** Tech-savvy, lifestyle-driven, highest transaction volume (~₹6.9M).  
- **36–45 (Mid-Career):** Stable income, diversified spending across shopping, travel, and family needs.  
- **46–59 (Mature Consumers):** Experienced users, steady spending, preference for essentials and bill payments.  

📊 *This segmentation allowed for targeted analysis of spending behavior by life stage.*  

---

### **Step 5 – Dashboard Design & Visuals** 📊  
- **KPI Cards** – Key metrics (Amount, Count, Avg, Success %).  
- **Bar Chart** – Age Group vs Transaction Amount.  
- **Merchant Performance** – Transactions by Zomato, Flipkart, IRCTC, Swiggy, Amazon.  
- **Line + Column Chart** – Monthly Transaction Trends vs Balances.  
- **Stacked Bar Chart** – Transaction Purpose (Shopping, Food, Travel, Bill Payments).  
- **Slicers** – City, Gender, Age, Device, Merchant, Bank, Payment Method.  

---

## 📌 Insights  

**1️⃣ Demographics**  
- Young Professionals (26–35 yrs) are the **highest contributors** (~₹6.9M).  
- Starters (21–25 yrs) account for the lowest spend (~₹2.4M).  

**2️⃣ Merchant Performance**  
- Zomato, Flipkart, IRCTC, Swiggy, Amazon capture ~100% combined share.  
- Each contributes ~20% to overall spend.  

**3️⃣ Purpose of Transactions**  
- **Shopping & Food** dominate, followed by Travel and Bill Payments.  

**4️⃣ Monthly Trends**  
- Transactions are **steady at ~1.6M–1.7M per month**.  
- Peak observed in **May (₹1.70M)**.  

**5️⃣ Transaction Success Rate**  
- 80% transactions succeed, failures linked to **bank/server downtime**.  

---

## 💡 Solutions & Business Recommendations  

1. **Target High-Value Age Group**  
   - Focus loyalty programs and cashback offers on 26–35 yrs customers.  

2. **Merchant Partnerships**  
   - Collaborate with top-performing merchants (Zomato, Flipkart, Amazon) for joint promotions.  

3. **Improve Reliability**  
   - Partner with banks to reduce downtime and boost success rates.  

4. **Seasonal Campaigns**  
   - Leverage high-transaction months like May with targeted marketing campaigns.  

5. **Expand Purpose Adoption**  
   - Incentivize UPI use for bill payments and travel bookings to diversify usage.  

---

## 🛠 Tools & Technologies Used  

- **Power BI Desktop** – Dashboard creation & KPIs  
- **Power Query** – Data cleaning & transformation  
- **DAX** – Calculated measures  
- **SQL** – Data extraction & preprocessing  
- **Excel & Python** – Validation & exploratory analysis  

---

## 🚀 How to Run  

1. Clone this repository.  
2. Download and open `UPI_Transactions.pbix` in **Power BI Desktop**.  
3. Use filters (City, Age, Merchant, Bank, Device) for interactive insights.  

---

## 🙋‍♀️ Author  

**Pragati Kumari**  
_Data Analyst | SQL | Python | Power BI | Excel_  

🔗 [LinkedIn](https://www.linkedin.com/in/pragati-kumari-b60352305)  
🔗 [GitHub](https://github.com/Pragati928)  

---

## 📄 License  

Open for learning and portfolio demonstration. Not for commercial use.  
