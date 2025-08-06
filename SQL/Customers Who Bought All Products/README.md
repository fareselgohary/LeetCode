
## Problem: Customers Who Bought All Products
## Link : https://leetcode.com/problems/customers-who-bought-all-products/description

### Tables:

#### Customer

| Column Name | Type |
|-------------|------|
| customer_id | int  |
| product_key | int  |

- This table may contain duplicate rows.  
- `customer_id` is NOT NULL.  
- `product_key` is a foreign key referencing the `Product` table.

#### Product

| Column Name | Type |
|-------------|------|
| product_key | int  |

- `product_key` is the primary key for this table.

---

### Goal:

Write a solution to report the customer IDs from the `Customer` table that bought **all** the products in the `Product` table.

Return the result table in any order.

---

### Example:

**Input**

`Customer` table:

| customer_id | product_key |
|-------------|-------------|
| 1           | 5           |
| 2           | 6           |
| 3           | 5           |
| 3           | 6           |
| 1           | 6           |

`Product` table:

| product_key |
|-------------|
| 5           |
| 6           |

**Output**

| customer_id |
|-------------|
| 1           |
| 3           |

**Explanation**:  
The customers who boug
