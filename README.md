# sql-and-data-cheat-sheets

# Visual SQL INNER JOIN Tutorial

This repository holds interactive data analytics cheat sheets designed for students and interview preparation.

### Source Tables
**Users (Left Table)**

| id | name |
|---|---|
| 1 | Alice |
| 2 | Bob |
| 3 | Charlie |

**Orders (Right Table)**

| user_id | item |
|---|---|
| 1 | Laptop |
| 2 | Phone |
| 4 | Tablet |

### The SQL Query
```sql
SELECT Users.id, Users.name, Orders.item 
FROM Users 
INNER JOIN Orders ON Users.id = Orders.user_id;
```

### Result Set (2 rows returned)

| id | name | item |
|---|---|---|
| 1 | Alice | Laptop |
| 2 | Bob | Phone |

---
### 📚 Recommended Data Analytics Interview & Study Resources:
* [Mastering SQL for Data Analytics - Complete Course Referral Link] *(Insert your affiliate link here)*
* [Top Data Science Interview Books Checklist] *(Insert your Amazon affiliate link here)*
