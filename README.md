# 🚀 Python + SQL Mini Lesson: Real-World Data Workflow

## 💡 Why This Matters
Want to stand out in tech?

The real power comes from combining:
- SQL → to extract & transform data  
- Python → to analyse & visualize it  

This is exactly how real-world data teams work.

---

## 🧠 What You'll Learn
- How to query top-performing products using SQL  
- How to load results into Pandas  
- How to visualize insights using Python  

---

## ⚙️ Tech Stack
- SQL  
- Python  
- Pandas  
- Matplotlib / Seaborn  

---

## 📊 Example Workflow

1. Query the data (SQL)
```sql
SELECT product_name, SUM(sales) AS total_sales
FROM sales_data
GROUP BY product_name
ORDER BY total_sales DESC
LIMIT 10;
