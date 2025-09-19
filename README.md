 Music Sales Database Project

This project is a **SQL-based analysis of a Music Store database**. The dataset is structured into multiple tables (such as `album`, `artist`, `customer`, `invoice`, etc.), and SQL queries are written to answer business-related questions.

The project helps in understanding **SQL for business analytics** by solving real-world style queries, such as:

* Who is the best customer?
* Which city generates the highest revenue?
* What is the most popular genre by country?
* Which artist earned the most from sales?

---

## 📂 Project Structure

* **Database Files**

  * `Music_Sales_database.sql` → Main SQL database file (schema + data).
  * `MusicDatabaseSchema.png` → Visual schema of the database.
  * `.ods` / `.xls` files (like `album`, `artist`, `customer`) → Dataset tables in spreadsheet format for easy viewing.

* **Query Files**

  * `Music_Sales_Query_.sql` → Contains all SQL queries written for analysis.
  * `Music Sales Create Tables Query.txt` → Duplicate text version of SQL (for easier reading).
  * `SQL Music Questions2.docx` → Word document with questions & queries explained.

* **Insights & Notes**

  * `Music Sales Insights.sql` → Collection of insights generated from queries.
  * `Capture.PNG` → Screenshot of project structure.

---

## ⚙️ How to Use

1. **Set Up Database**

   * Open MySQL (or SQLite/Postgres if adapted).
   * Import the database using:

     ```sql
     SOURCE Music_Sales_database.sql;
     ```

2. **Run Queries**

   * Open `Music_Sales_Query_.sql`.
   * Execute queries step by step to explore:

     * Easy Level (basic aggregations).
     * Moderate Level (joins, subqueries).
     * Advanced Level (CTEs, recursive queries).

3. **Explore the Data**

   * Use spreadsheet files (`album.ods`, `artist.ods`, etc.) to quickly view the raw tables without SQL.

4. **Understand the Business Context**

   * Refer to `SQL Music Questions2.docx` or `Music Sales Create Tables Query.txt` for explanations in plain text.

---

## 💡 Why This Project?

This project is designed to:

* Practice **SQL for analytics & reporting**.
* Understand how to **connect business questions with SQL queries**.
* Learn how to work with **joins, aggregations, window functions, and recursive queries**.

---

## 🚀 Tech Stack

* **Database**: MySQL
* **Data Format**: `.sql`, `.ods` (OpenOffice), `.docx`
* **Tools Used**: MySQL Workbench, OpenOffice/Excel

---

## 📜 Credits

* Dataset inspired by the Chinook Music Store Database.
* Queries & explanations created by Ram Verma.

