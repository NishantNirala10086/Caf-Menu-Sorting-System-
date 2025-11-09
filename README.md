# ☕ Café Menu Sorting System

### 📝 Overview

The **Café Menu Sorting System** is an interactive desktop application designed to digitalize and simplify café or restaurant menu management. Built using **Python (Tkinter)** for the front end and **MySQL** for the backend, the system allows users to **add**, **view**, **delete**, and **sort** menu items efficiently using the **Quick Sort algorithm**.

This project demonstrates how sorting algorithms and database connectivity can be integrated to create real-world applications with user-friendly interfaces.

---

### 🚀 Features

✅ Add, view, and delete menu items
✅ Sort items by **price (Low → High / High → Low)** using **Quick Sort**
✅ Category-based filtering of menu items
✅ Real-time database updates with MySQL
✅ Search bar for quick item lookup
✅ Clean and interactive **Tkinter GUI**

---

### 🧰 Tech Stack

* **Frontend:** Python (Tkinter)
* **Backend:** MySQL
* **Algorithm Used:** Quick Sort
* **Database Connector:** mysql-connector-python

---

### 💾 Database Setup

Create a database in MySQL before running the project:

```sql
CREATE DATABASE cafe_menu_db;
USE cafe_menu_db;

CREATE TABLE menu_items (
    id INT AUTO_INCREMENT PRIMARY KEY,
    category VARCHAR(100),
    item_name VARCHAR(100),
    price FLOAT
);
```

You can manually insert some records for testing:

```sql
INSERT INTO menu_items (category, item_name, price) VALUES
('Juice', 'Orange Juice', 50),
('Juice', 'Apple Juice', 60),
('Coffee', 'Cappuccino', 120),
('Coffee', 'Espresso', 100),
('Snacks', 'Sandwich', 80);
```

---

### ⚙️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Cafe-Menu-Sorting-System.git
   cd Cafe-Menu-Sorting-System
   ```

2. Install dependencies:

   ```bash
   pip install mysql-connector-python
   ```

3. Update the MySQL connection details in the code (host, user, password).

4. Run the application:

   ```bash
   python cafe_menu_app.py
   ```

---

### 📸 Screenshots

*(You can add GUI screenshots here)*

* Home Interface
* Menu Sorting Example
* Add/Delete Item Screen

---

### 🧠 Algorithm Used

The system uses the **Quick Sort Algorithm** to sort menu items by price efficiently.
Quick Sort is chosen for its high performance and divide-and-conquer approach, ensuring fast sorting for large datasets.


---

### 🏁 Conclusion

The Café Menu Sorting System demonstrates the effective integration of **Python, MySQL, and algorithms** to develop a practical, real-world application. It simplifies the management of café menus and provides an easy-to-use, efficient system for sorting and organizing menu items.

---


Would you like me to include **screenshot placeholders and badges** (like Python version, license, and MySQL used) at the top to make it look more professional for GitHub?
