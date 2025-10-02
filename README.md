# 👁️ Task 7 – Creating Views (Library Management System)

## 📌 Overview
This task demonstrates how to create and use **SQL Views** in the **Library Management System** database created in Tasks 1–6.  
Views provide data abstraction, security, and reusability for complex queries.  

---

## 🗂️ Views Demonstrated

### 1. Simple View  
- `vw_books`: Displays all books with authors and publication year.  

### 2. View with JOIN  
- `vw_member_loans`: Shows loans with member, book, and staff details.  

### 3. View with WHERE  
- `vw_available_books`: Displays only books that are currently available.  

### 4. View with Aggregation  
- `vw_books_per_author`: Counts how many books each author has written.  

### 5. View with Security  
- `vw_safe_members`: Hides sensitive member details like email and phone.  

### 6. View with CHECK OPTION  
- `vw_recent_books`: Only includes books from 2020 onwards and enforces this rule for inserts/updates.  

---

## 📂 Files Included
SQL file: [`library_schema_task7.sql`](library_schema_task7.sql)

---

## ✅ Outcome
By completing this task, you will learn how to:  
- Create simple, join, and filtered views.  
- Use views for security and abstraction.  
- Apply aggregation in views.  
- Enforce conditions using `WITH CHECK OPTION`.  

This strengthens your understanding of **views in SQL** and prepares you for advanced database management tasks.  
