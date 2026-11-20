# 🎬 BingePlay – Streaming Analytics Project

## 📌 Project Overview

BingePlay is a SQL-based data analytics project focused on analysing user behaviour, subscription patterns, revenue, content ratings, engagement and customer churn for a fictional OTT streaming platform.

The project uses MySQL and Python to solve 12 business-oriented analytical questions and generate meaningful insights that can support business decision-making.

## 🎯 Project Objectives

- Analyse active subscriptions and monthly recurring revenue.
- Understand monthly user signup trends.
- Evaluate device-wise viewing behaviour.
- Analyse customer ratings and satisfaction.
- Compare original and acquired content.
- Identify binge-watching behaviour.
- Analyse subscription upgrades.
- Identify customer engagement and churn signals.

## 🛠️ Tools & Technologies

- **Database:** MySQL
- **Database Management:** MySQL Workbench
- **Programming Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:** Pandas, SQLAlchemy, PyMySQL
- **Query Language:** SQL

## 📊 Project Analysis – 12 Questions

### Tier 1 – Basic SQL Analysis

1. **Active Revenue:** Calculate active subscriptions and total monthly recurring revenue.
2. **Signup Momentum:** Analyse monthly user signups.
3. **Device Analytics:** Compare viewing sessions and watch time across devices.
4. **Rating Distribution:** Analyse star ratings and positive rating percentages.
5. **Originals vs Acquired:** Compare original and acquired shows using IMDb ratings.

### Tier 2 – Intermediate SQL Analysis

6. **Binge Day Detection:** Identify users who watch the same show at least five times in a single day.
7. **Q1 Signups Who Never Watched:** Identify registered users who never started watching content.
8. **Over-paying Premium/Family Users:** Identify subscribers whose viewing history contains only Basic-tier shows.
9. **Upgrade Success Cohort:** Analyse users who upgraded from Basic to Premium or Family.
10. **Cliffhanger Comebacks:** Identify users who returned to the same show within seven days after an incomplete session.

### Tier 3 – Advanced SQL Analysis

11. **Consecutive-week Engagement:** Identify users with four or more consecutive weeks of viewing activity.
12. **Churn Signal Detection:** Identify users whose watch time dropped by at least 50% in June compared with May 2024.

## 📈 Key Learnings

Through this project, I gained practical experience in:

- SQL filtering, grouping and sorting.
- Aggregate functions and conditional logic.
- Joins and subqueries.
- Common Table Expressions (CTEs).
- Window functions such as ROW_NUMBER().
- Date and time-based analysis.
- Business-oriented data analysis.
- Connecting MySQL databases with Python.

## 📁 Project Files

- `BingePlay_Mayuri_Nilange.ipynb` – Jupyter Notebook containing all 12 analytical questions, SQL queries and outputs.
- `BingePlay_Setup.sql` – Database setup file .

## 🚀 How to Run the Project

1. Install MySQL and MySQL Workbench.

2. Import the BingePlay database using the provided setup SQL file.

3. Install Python and Jupyter Notebook.

4. Install the required libraries:

   ```bash
   pip install pandas sqlalchemy pymysql
   ```

5. Open the Jupyter Notebook.

6. Configure your local MySQL connection using your own credentials.

7. Execute the notebook cells to run the 12 analytical queries.

**Note:** The notebook uses a local MySQL connection. Update the connection settings with your own database credentials before running it.

## 👩‍💻 Author

**Mayuri Nilange**

Batch: DS_DA Oct_2026

## 🙏 Acknowledgement

This project was completed as part of the Data Analytics training and hands-on project work provided by **The Unlox Academy**.

---

⭐ Thank you for visiting my BingePlay Streaming Analytics Project repository!
