# 📊 Pizza Place Sales Analysis 📊

This project contains a complete analysis of a fictitious pizza place's sales data over one year. The goal is to extract meaningful insights from the data to improve business decisions using Python and visualizations.

---

## 📁 Dataset Overview

The data consists of **four CSV files**:

- `orders.csv`: Contains order IDs with timestamps.
- `order_details.csv`: Includes which pizzas were ordered in what quantity.
- `pizzas.csv`: Provides details like size and price of each pizza.
- `pizza_types.csv`: Describes pizza names, categories, and ingredients.

These files were merged into a single dataset for analysis.

---

## 📚 Data Dictionary
| Table      | Field         | Description                                     |
|------------|---------------|-------------------------------------------------|
| orders     | order\_id     | Unique identifier for each order                |
| orders     | date          | Date the order was placed                       |
| orders     | time          | Time the order was placed                       |
| order\_det | order\_det\_id | Unique identifier for each order detail record |
| order\_det | order\_id     | Foreign key referencing the orders table       |
| order\_det | pizza\_id     | Foreign key referencing the pizzas table       |
| order\_det | quantity      | Quantity of the pizza in the order detail      |
| pizzas     | pizza\_id     | Unique identifier for each pizza                |
| pizzas     | pizza\_type\_id | Foreign key referencing the pizza\_types table   |
| pizzas     | size          | Size of the pizza                               |
| pizzas     | price         | Price of the pizza                              |
| pizza\_type | pizza\_type\_id | Unique identifier for each pizza type          |
| pizza\_type | name          | Name of the pizza type                          |
| pizza\_type | category      | Category of the pizza type                      |
| pizza\_type | ingredients   | Comma-separated list of ingredients            |

---

## 🧪 Tools Used

- **Python** (Pandas, NumPy)
- **Matplotlib** and **Seaborn** for visualization
- **Jupyter Notebook** for interactive exploration

---

## 🔍 Key Questions Answered

1. ✅ **What is the total revenue?**  
2. ✅ **How many total pizzas were sold?**  
3. ✅ **What is the total number of orders?**  
4. ✅ **How many unique pizza types were sold?**  
5. ✅ **What is the average price of a pizza?**  
6. ✅ **What are the peak hours of sales?**  
7. ✅ **Which day of the week sees the most sales?**  
8. ✅ **What are the top 5 bestselling pizzas?**  
9. ✅ **What trends are noticeable in monthly sales?**  
10. ✅ **Which pizzas are underperforming?**

---

## 📊 Summary of Insights

| Metric                    | Value          |
|--------------------------|----------------|
| **Total Revenue**        | $817,860.05    |
| **Total Quantity Sold**  | 49,574 pizzas  |
| **Total Orders**         | 21,350         |
| **Unique Pizza Types**   | 32             |
| **Average Pizza Price**  | $16.50         |

---

## 📈 Visual Insights

- **Peak Hours:** Sales peak around **12 PM – 1 PM**.
- **Top Day:** **Saturday** generates the most revenue.
- **Top 5 Bestselling Pizzas:** A few pizza types dominate the sales.
- **Monthly Trend:** Slight increase toward the **end of the year**.
- **Underperformers:** Some pizza types have consistently low sales.

---

## 🧠 Recommendations

- Consider promoting low-selling pizzas or reviewing their recipe/pricing.
- Increase staffing or promotional offers during peak hours and weekends.
- Introduce seasonal offers toward the year-end to leverage higher sales momentum.

---

## 📂 Repository Structure

```yaml
📦 pizza-place-sales-analysis
├── data/
│ ├── orders.csv
│ ├── order_details.csv
│ ├── pizzas.csv
│ └── pizza_types.csv
├── sales-analysis.ipynb
└── README.md
```

---

## 📌 How to Run

1. Clone the repository.
2. Open `sales-analysis.ipynb` in Jupyter Notebook or VSCode.
3. Run all cells sequentially