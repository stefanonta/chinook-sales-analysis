## 📊 Chinook Sales Analysis

### 🧠 Project Overview

This project analyzes customer purchasing behavior using the Chinook database, a fictional digital music store. The goal is to extract meaningful business insights using SQL and Python, showcasing real-world data querying skills and analytical thinking.

### ❓ Business Questions Answered

* Which music genres are most popular among U.S. customers, and what share of total track sales does each represent?
* How much revenue has each sales support agent generated, and what customer or regional factors might explain their performance?
* Which countries represent our most valuable customer markets, and how should we group low-representation countries for reporting?
* Among invoices that contain tracks from a single album, what proportion represent full album purchases versus partial (individual track) purchases?

### 🛠️ Tools & Technologies

* **SQL (PostgreSQL & SQLite)**: for querying and transforming the data  
* **Python (pandas)**: for supplementary analysis and workflow integration  
* **Jupyter Notebook**: for combining code, narrative, and results  
* **VS Code**: as the development environment  

### 🔍 SQL Concepts Demonstrated

* Common Table Expressions (CTEs)
* Aggregate and window functions
* Subqueries and correlated subqueries
* CASE statements and conditional logic
* Data classification and invoice-level analysis

### 💡 Key Insights

* Among U.S. customers, the **Alternative & Punk** genre leads in track sales, accounting for over 60% among the filtered set of target genres.
* **Sales agent performance varies significantly**, with revenue linked to employee role. Only agents in sales roles generate customer purchases.
* The **USA, Canada, and Brazil** are the top three revenue-generating countries. Countries with a single customer are grouped into “Other” to simplify reporting.
* Around **18.6% of invoices with tracks from a single album** are confirmed full album purchases. This supports the case for licensing individual tracks instead of full albums.

### 📁 Project Structure

    Chinook-SQL-Project/
    ├── Data/
    │   └── chinook.db
    ├── chinook-analysis.ipynb
    ├── README.md
    └── Outputs/
        ├── Vidz/
        └── Data-Exports/