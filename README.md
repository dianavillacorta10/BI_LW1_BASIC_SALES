# Laboratory-Work1-Activity-PowerBI

## Verify Data in Data View
- **Are all columns visible?**  
  Yes, all columns are visible in Power BI’s Data View.

- **Is “Date” formatted as Date?**  
  Yes. The “Date” column is already formatted as Date in my Power BI dataset

- **Is “Sales” formatted as Decimal Number?**  
  Yes. The “Sales” column is formatted as a Decimal Number in Power BI, which allows the visuals to correctly calculate totals, sums, and   other aggregations, like showing $220.23K in the charts.
---

## Quick Visualization
![Quick Visualization](https://github.com/dianavillacorta10/BI_LW1_BASIC_SALES/blob/bac41de41a6ba7bc187dd1acefa2149143a91d18/Quick%20Visualization.png)

**Answers to Questions:**  
- **What type of chart was created?**  
  This is a Bar Chart.  

- **What does it show?**  
  It shows the total sales for each category or region. Specifically, it represents the “Sum of Sales”, meaning the total amount of money   generated, allowing you to easily compare which categories or regions perform better.

---

## Create a Sales by Region Chart
![Region Chart](https://github.com/dianavillacorta10/BI_LW1_BASIC_SALES/blob/bac41de41a6ba7bc187dd1acefa2149143a91d18/Region%20Chart.png)

**Answers to Questions:**  
- **Which region has highest sales?**  
  The West region has the highest sales
---

## Sales by Category
![Sales by Category](https://github.com/dianavillacorta10/BI_LW1_BASIC_SALES/blob/bac41de41a6ba7bc187dd1acefa2149143a91d18/Sales%20by%20Category.png)

**Answers to Questions:**  
- **Which category dominates?**  
  The Electronics category dominates, with the highest sales of 90K, making up 40.82% of the total sales.  

- **Is the distribution balanced?**  
  No, the distribution is not balanced. While Electronics (40.82%) and Furniture (39.19%) are almost equal, Office Supplies only makes up 19.99% of sales, which is about half of the other two categories, making the overall distribution uneven.
---

## Sales Over Time
![Sales Over Time](https://github.com/dianavillacorta10/BI_LW1_BASIC_SALES/blob/bac41de41a6ba7bc187dd1acefa2149143a91d18/Sales%20Over%20Time.png)

**Answers to Questions:**  
- **Is there growth?**  
  There is no growth. Sales went down a lot between the two years.  

- **Any noticeable trend?**  
  Yes, there is a noticeable trend sales are decreasing sharply over time. In the Sales Over Time chart, sales started high in 2024 at around 80K but dropped quickly in 2025 to just above 10K, showing a significant decline year over year.

---

## Basic Data Insight Interpretation
- **Which region contributes most revenue?**  
  The West region contributes the most revenue, totaling approximately $59,000.  

- **Which product category performs best?**  
  The Electronics category performs the best, making $90,000 in sales, which is 40.82% of the total.  

- **Are sales consistent across dates?**  
  No, sales are very inconsistent.

- **Business recommendation:**  
  Investigate why sales dropped almost 87% in 2025. Focus marketing on the West and East regions, and on Electronics and Furniture, since these bring in the most sales.

---

## LABORATORY QUESTIONS

### Part A – Technical Questions
1. **What are the five columns in the dataset?**  
   Region, Category, Year, Sales, and usually a fifth column like Date or Product Name.  

2. **What data type is assigned to the “Sales” column?**  
   Decimal Number.  

3. **Which Power BI view allows you to see raw data?**  
   Data View.  

4. **Which chart type is best for showing trends over time?**  
   Line chart.  

5. **What aggregation is automatically applied to Sales?**  
   Sum aggregation.

---

### Part B – Analytical Questions
6. **Which region has the highest total sales?**  
   West region, nearly $60,000.  

7. **Which category has the lowest performance?**  
   Office Supplies, 19.99% ($44K) of total sales.  

8. **Are sales increasing, decreasing, or stable?**  
   Decreasing from about $80,000 in 2024 to around $10,000 in 2025.  

9. **If you were a manager, which region would you prioritize?**  
   North region for growth ($46K), representing the largest opportunity.  

10. **Provide one actionable recommendation.**  
    Investigate the 2025 sales drop of ~87% to prevent potential business issues.

---

## Add a Card Visualization
![Card Visualization](https://github.com/dianavillacorta10/BI_LW1_BASIC_SALES/blob/26d108111b6e41c878a381cf5f9254d2c05b9660/Card%20%20%20Visualization.png)

**Answers to Questions:**  
- **What is the total sales amount?**  
  220.23K

---

## Add Slicer
![Add Slicer](https://github.com/dianavillacorta10/BI_LW1_BASIC_SALES/blob/26d108111b6e41c878a381cf5f9254d2c05b9660/Add%20Slicer%20(2).png)

**Answers to Questions:**  
- **What happens to other visuals when you click a region?**  
  All other charts update to show only the selected region’s data.  

- **Why is filtering important in BI?**  
  Filtering is crucial in Business Intelligence (BI) because it helps you focus on the most relevant data and extract meaningful insights without being overwhelmed by the full dataset.
---

## Sort Sales

**Answers to Questions:**  
- **Does sorting improve readability?**  
  Yes, sorting improves readability because it makes trends obvious, allows easier comparisons, reduces cognitive load, highlights outliers, and helps communicate insights clearly. 

- **Why?**  
  Sorting improves readability because it organizes data in a logical order, making it easier for the viewer to understand patterns, compare values, and quickly identify important information without having to search through random or unsorted data.
---

## Identify Outliers
- **Which region is significantly higher or lower?**  
  West ($59K) and East ($58K) are higher; North ($46K) is lower.  

- **What might explain that difference?**  
  West and East may have larger markets, stronger demand, or better supply chains; North may have fewer stores, smaller teams, or supply issues.
