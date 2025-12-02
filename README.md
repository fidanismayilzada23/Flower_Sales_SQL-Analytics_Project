# 🌸 Flower Sales — SQL Analytics Project

This project analyzes a fictional **flower sales business** using SQL to extract meaningful business insights from raw CSV datasets.  
All CSV files were manually imported into the SQL database, tables were created via DDL commands, and business questions were answered using analytical SQL queries.

---

## 📂 Project Flow

### ✔ 1) Import CSV files  
The following datasets were added to the database:

| File | Description |
|------|-------------|
| `Customer.csv` | Customer details |
| `Categories.csv` | Flower category information |
| `FlowerTypes.csv` | Flower type / product list |
| `order.csv` | Order header information |
| `orderdetail.csv` | Item-level order details |
| `inventory.csv` | Stock availability per flower |
| `promotionsss.csv` | Promotion types and discount amounts |
| `Promotion_Categories.csv` | Category-level promotion mapping |

### ✔ 2) Build relational database schema  
All tables were manually created using SQL DDL commands.  
Primary keys, foreign keys, data types, and relationships were defined — ensuring referential integrity.


### ✔ 3) Execute analytical SQL queries  
Queries were produced to answer real-world business questions such as:
- Best-selling flowers
- Customer spending analysis
- Inventory risk detection
- Promotion performance
- Profit & revenue breakdown
- Delivery performance by city
- Customer segmentation by age & gender

All queries are available inside `/Querycode.txt`.

---

## 🔍 Examples of Business Questions Answered

| Focus Area | Question |
|-----------|----------|
| Sales | Which flowers generate the highest revenue? |
| Customers | Which customers spend the most money? |
| Inventory | Which products require urgent restock? |
| Promotions | Which discounts are most effective? |
| Delivery | Which cities have the fastest/slowest delivery? |
| Profit | Which products and categories generate the most profit? |
| Segmentation | Which age & gender groups order the most? |

---

## 📌 (Replace with your real findings)

After running the analytical SQL queries, insights can be added like:

| Metric | Result |
|--------|--------|
| 🏆 Most profitable flower | Red Velvet Rose |
| 💰 Highest revenue category | Roses |
| 📦 Fastest delivery city | Baku |
| 🔥 Most effective promotion | Seasonal Bouquet Discount |


---

## 🧠 SQL Techniques Used

- Relational schema design (DDL)
- Data import from CSV files
- `JOIN` varieties (INNER, LEFT, FULL)
- `GROUP BY` & aggregation functions
- Window functions (`RANK`, `ROW_NUMBER`)
- `CASE WHEN` logic for classification
- Profit calculation formulas
- Delivery speed using date difference
- Segmentation using dynamic age groups

---

## 🚀 Tools & Environment

| Component | Technology |
|----------|------------|
| Database | PostgreSQL |
| GUI Tool | Valentina Studio |
| Files | CSV + XLSX |
| Code Scripts | `.txt` SQL files |

---

## 🛠 How to Run the Project

1. Import all CSV files into PostgreSQL
2. Execute the DDL scripts in `Create_table_code.txt`
3. Run analysis queries from `Querycode.txt`
4. Optional: connect the dataset to Power BI for visual dashboards

---

## 👤 Author
**Fidan Ismayilzada**  
Data Analyst  
🔗 LinkedIn: https://linkedin.com/in/fidan-ismayilzada-529104193

