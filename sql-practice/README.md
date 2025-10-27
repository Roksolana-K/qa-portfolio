# SQL Practice

This project was created as part of SQL practice using **DBeaver** and a local SQLite database (`dev.db`).  
The goal was to demonstrate skills in **database creation, table management, and data manipulation**.


## 🧩 Tasks Completed
1. Connect to the local `dev.db` database via DBeaver.  
2. Created a new table `reviews_test` with columns:
   - `id`
   - `review_name`
   - `review_text`
   - `review_author_id`
   - `article_id`  
3. Insert 5 records into `reviews_test`.  
4. Retrieve data from `reviews_test` and `article` tables using `SELECT`.  
5. Alter the table by adding a `created_at` column.  
6. Update all records with a fixed `created_at` date (`'01-01-2222'`).  
7. Delete the last two records dynamically (without depending on `id`).  
8. Create a new table `reviews` with proper **constraints** (`PRIMARY KEY`, `NOT NULL`, `FOREIGN KEY`, etc.).

---

