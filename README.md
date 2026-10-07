# personal-learning-hub
========================

# 🚀 Personal Learning Hub

Welcome to my **Personal Learning Hub** repository! This repository tracks my step-by-step learning journey across various tech concepts and practices.

---

## 📌 Week 1: SQL Learning & Practice (MySQL)

During **Week 1**, I covered foundational to intermediate SQL concepts using **MySQL Workbench**. This includes database creation, schema modifications, data manipulation, filtering, built-in string/math functions, sorting, pagination, aggregate functions, and grouped reporting.

---

## 📁 Repository Structure

* `mysql_practice.sql` - Complete practice script containing all DDL, DML, and DQL queries executed during Week 1.
* `README.md` - Documentation and summary of topics learned.

---

## 📚 Week 1 Topics Covered

### 1. Database & Table Management (DDL & DML)
* **Database Creation**: `CREATE DATABASE`, `USE database_name`.
* **Table Creation & Constraints**:
  * `PRIMARY KEY`: Unique row identifier.
  * `AUTO_INCREMENT`: Auto-generating primary IDs.
  * `NOT NULL`: Restricts empty/null values.
  * `UNIQUE`: Guarantees unique values across columns.
  * `CHECK`: Validates column value conditions (e.g., `CHECK (age >= 18)`).
* **Data Insertion**: Inserting single and multi-row records using `INSERT INTO`.

### 2. Table Modifications & Cleanup (`ALTER`, `DELETE`, `TRUNCATE`, `DROP`)
* **Schema Alterations (`ALTER TABLE`)**:
  * Adding new columns (`ADD`).
  * Modifying data types and constraints (`MODIFY`).
  * Renaming columns (`CHANGE COLUMN`).
  * Dropping unused columns (`DROP COLUMN`).
  * Renaming tables (`RENAME TO`).
* **Data Removal Operations**:
  * Row deletion using `DELETE FROM ... WHERE`.
  * Wiping table records while keeping structure using `TRUNCATE`.
  * Permanently deleting entire tables using `DROP TABLE`.

### 3. Data Querying & Filtering (`SELECT` & Operators)
* **Basic Selection**: Retrieving all columns (`SELECT *`) or specific columns.
* **Filtering (`WHERE`)**:
  * **Relational Operators**: `=`, `<>`, `>`, `<`, `>=`, `<=`.
  * **Range Searching**: `BETWEEN ... AND ...`.
  * **Set Selection**: `IN (...)` and `NOT IN (...)`.
* **Pattern Matching (`LIKE`)**:
  * Wildcard `%` for suffix (`'%N'`), prefix (`'N%'`), and substring search (`'%N%'`).
  * Negated pattern matching using `NOT LIKE`.
* **NULL Handling**: `IS NULL` and `IS NOT NULL`.
* **Logical Combinations**: Combining query logic using `AND` and `OR`.

### 4. Sorting & Pagination (`ORDER BY` & `LIMIT`)
* **Sorting**: Ordering results in ascending (`ASC`) or descending (`DESC`) order.
* **Limiting Output**: Retrieving top $N$ or bottom $N$ records using `LIMIT`.
* **Pagination (`LIMIT offset, count`)**:
  * Using 0-based offset syntax to skip rows and extract nth-ranked data (e.g., finding 2nd highest budget department).

### 5. MySQL Built-in Functions
* **String Functions**:
  * Case conversions: `UPPER()`, `LOWER()`.
  * Concatenation: `CONCAT()`.
  * Slicing & Length: `SUBSTRING()`, `LENGTH()`.
  * Whitespace removal: `TRIM()`.
* **Mathematical Functions**:
  * Absolute values: `ABS()`.
  * Remainder division: `MOD()`.

### 6. Aggregations & Grouping (`GROUP BY` & `HAVING`)
* **Aggregate Metrics**: `COUNT()`, `SUM()`, `AVG()`, `MIN()`, `MAX()`.
* **Categorical Grouping (`GROUP BY`)**: Grouping row sets to generate summarized stats per group/location.
* **Group Filtering (`HAVING`)**: Filtering grouped aggregate metrics (unlike `WHERE`, which filters individual rows).

---

## 🛠️ How to Run the Code

1. Open **MySQL Workbench** and connect to your local server.
2. Open the file `mysql_practice.sql` or copy its content into a new Query Tab (`Ctrl + T`).
3. Execute the script (`Ctrl + Shift + Enter`).

---

## 👨‍💻 Git Workflow Commands

Commands used to push this practice to GitHub:

```bash
# Add file to staging
git add mysql_practice.sql README.md

# Commit changes
git commit -m "Add Week 1 SQL practice script and summary documentation"

# Push to main branch
git push origin main
```

---
*Happy Learning! 🎯*
