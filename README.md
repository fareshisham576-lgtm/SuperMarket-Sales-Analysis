# ***🛒SuperMarket Sales Analysis***


## *📌 Project Description*

This project uses **Python and Pandas** to clean, prepare, and analyze supermarket sales data.

The dataset used in this project is:

`SuperMarket.csv`

The goal is to clean the data and answer business questions using the available sales and transaction information.

---
## *🛠️ Tools Used*

* Python
* Pandas
* Ydata-Profiling
* Plotly

---
## *🧹 Data Cleaning*

The following data-cleaning steps were performed:

* Checked data types
* Checked missing values
* Checked duplicate records
* Renamed columns
* Removed unnecessary columns
* Corrected data types
* Sorted the data
* Create 3 columns (Day, Month, Year )
* Created the `satisfied` column based on the rating

**Satisfaction Rule:**

<mark>`Rating >= 7 → Satisfied Else  → Not Satisfied`</mark>

---
## *📊 Business Analysis*

### **1. Total Revenue**

**Result:**

> **318,041.9 $**

---
### **2. Revenue by City**

**Highest Revenue City:**

> **Giza**

**Result:**

| Branch | Total Salary |
| :--- | :---: |
| **Giza** | 109,168.70 |
| **Cairo** | 105,266.50 |
| **Alex** | 103,606.70 |
| **Total** | **318,041.90** |

---
### **3. Profit by Branch**

**Most Profitable Branch:**

> **Giza**

**Result:**

| Branch | Total Price |
| :--- | :---: |
| **Giza** | 103,970.20 |
| **Cairo** | 100,253.80 |
| **Alex** | 98,673.00 |
| **Total** | **302,897.00** |

---

### **4. Revenue and Profit by Product Category**

**Top-Performing Category:**

> **Food and beverages**
> 
> ![image_here](Figs/Screenshot%202026-08-12%20151243.png)
**Result:**

| Product Line | Total Salary | Total Price |
| :--- | :---: | :---: |
| **Food and beverages** | 55,518.60 | 52,874.90 |
| **Fashion accessories** | 54,245.10 | 51,662.00 |
| **Sports and travel** | 53,898.00 | 51,331.40 |
| **Home and lifestyle** | 53,089.50 | 50,561.50 |
| **Electronic accessories** | 52,922.60 | 50,402.50 |
| **Health and beauty** | 48,368.10 | 46,064.90 |
| **Total** | **318,041.90** | **302,897.20** |

---

### **5. Spending by Customer Type**

**Customer Type That Spends More:**

> **Member**

---

### **6. Payment Method**

**Most Popular Payment Method:**

> **Cash**

**Result & ScreenShot:**

| Payment Method | Count |
| :--- | :---: |
| **Cash** | 341 |
| **E-Wallet** | 338 |
| **Credit card** | 309 |
| **Total** | **988** |

> ![image_here](Figs/Screenshot%202026-08-12%20151652.png)
---

### **7. Average Transaction Value**

**Average Transaction Value:**

> **321.9 $**

---

### **8. Customer Satisfaction by Branch**

**Branch with the Highest Satisfaction:**

> **('Cairo', 'Not Satisfied')**

**Result:**

| Branch | Not Satisfied (%) | Satisfied (%) |
| :--- | :---: | :---: |
| **Alex** | 47.3% | 52.7% |
| **Cairo** | 54.0% | 46.0% |
| **Giza** | 47.9% | 52.1% |

---

### **9. Sales by Day and Month**

**Highest Sales Day:**

| Day | Total Salary |
| :--- | :---: |
| **Saturday** | 56,013.70 |
| **Tuesday** | 50,645.30 |
| **Thursday** | 44,819.60 |
| **Sunday** | 43,685.50 |
| **Wednesday** | 43,497.60 |
| **Friday** | 42,542.50 |
| **Monday** | 36,837.80 |
| **Total** | **318,041.90** |

**Highest Sales Month:**

| Month | Total Salary |
| :--- | :---: |
| **January** | 115,625.30 |
| **February** | 94,445.40 |
| **March** | 107,971.30 |
| **Total** | **318,041.90** |

**Result**

| Day | January | February | March | Total |
| :--- | :---: | :---: | :---: | :---: |
| **Saturday** | 18,093.70 | 12,256.20 | 25,663.80 | **56,013.70** |
| **Sunday** | 14,356.80 | 15,858.60 | 13,470.20 | **43,685.50** |
| **Monday** | 14,192.70 | 12,851.20 | 9,793.90 | **36,837.80** |
| **Tuesday** | 20,614.10 | 12,419.90 | 17,611.30 | **50,645.30** |
| **Wednesday** | 17,808.40 | 12,172.00 | 13,517.20 | **43,497.60** |
| **Thursday** | 19,340.20 | 12,719.60 | 12,759.80 | **44,819.60** |
| **Friday** | 11,219.50 | 16,167.90 | 15,155.10 | **42,542.50** |
| **Total** | **115,625.30** | **94,445.40** | **107,971.30** | **318,041.90** |

> ![image_here]()
---

### 10. Overall Customer Satisfaction

**Overall Satisfaction Percentage:**

> Update with your result.

---
