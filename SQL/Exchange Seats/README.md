# 🪑 Exchange Seats (SQL)

## 🔗 Problem Link  
[Exchange Seats – LeetCode](https://leetcode.com/problems/exchange-seats/description)

---

## 📘 Problem Description  

### 📊 Tables

**Seat**

| Column Name | Type    |
|-------------|---------|
| id          | int     |
| student     | varchar |

- `id` is the primary key (unique) for this table.  
- Each row represents a student with a unique seat ID.  
- IDs **start from 1** and **increase continuously**.

---

### 🎯 Goal

Write a SQL solution to **swap the seat id of every two consecutive students**.  
If the number of students is **odd**, the **last student's seat remains unchanged**.

🔁 The result table should be **ordered by `id` in ascending order**.

---

## 💡 Example

### 🧾 Input

**Seat** table:

| id | student  |
|----|----------|
| 1  | Abbot    |
| 2  | Doris    |
| 3  | Emerson  |
| 4  | Green    |
| 5  | Jeames   |

### 📤 Output

| id | student  |
|----|----------|
| 1  | Doris    |
| 2  | Abbot    |
| 3  | Green    |
| 4  | Emerson  |
| 5  | Jeames   |

### 🧠 Explanation:

- Students with IDs 1 and 2 swap places.
- Students with IDs 3 and 4 swap places.
- Student with ID 5 stays in place (odd count).

---

## 🏷️ Tags  
#SQL #LeetCode #Beginner #Database #InterviewPrep #Joins #CaseStatement
