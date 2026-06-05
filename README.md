# Student-Registration-System
CRUD-based Student Registration System developed using Python Tkinter and MySQL.


A desktop-based Student Registration System developed using **Python Tkinter** and **MySQL**. This application allows users to manage student records through a simple graphical user interface (GUI) and perform complete CRUD (Create, Read, Update, Delete) operations.

---

## 📌 Features

* Add new student records
* Update existing student information
* Delete student records
* Display all student data in a table
* MySQL database integration
* User-friendly GUI built with Tkinter
* Real-time data management

---

## 🛠️ Technologies Used

* Python
* Tkinter
* MySQL
* MySQL Connector/Python

---

## 📂 Project Structure

```text
Student-Registration-System/
│
├── main.py
├── database.py
├── requirements.txt
├── README.md
├── screenshots/
│   └── dashboard.png
└── sql/
    └── studentdb.sql
```

---

## 🗄️ Database Schema

```sql
CREATE DATABASE studentdb;

USE studentdb;

CREATE TABLE student (
    id INT PRIMARY KEY,
    name VARCHAR(100),
    course VARCHAR(100),
    fee DECIMAL(10,2)
);
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Student-Registration-System.git
```

### 2. Navigate to Project Folder

```bash
cd Student-Registration-System
```

### 3. Install Dependencies

```bash
pip install mysql-connector-python
```

### 4. Configure MySQL Connection

Update your database credentials in the Python file:

```python
conn = mysql.connector.connect(
    host="localhost",
    user="root",
    password="your_password",
    database="studentdb"
)
```

### 5. Run the Application

```bash
python main.py
```

---

## 📸 Application Preview

Student Registration System GUI:

* Student ID Entry
* Name Entry
* Course Entry
* Fee Entry
* Add Button
* Update Button
* Delete Button
* Student Records Table

(Add your project screenshot in the screenshots folder and update the image path below.)

```markdown
![Student Registration System](screenshots/dashboard.png)
```

---

## 🎯 Learning Outcomes

Through this project, I learned:

* Python GUI Development with Tkinter
* MySQL Database Connectivity
* CRUD Operations
* SQL Queries
* Event Handling
* Database Management
* Building Real-World Desktop Applications

---

## 🚀 Future Improvements

* Search Student Feature
* Login Authentication
* Export Data to Excel
* Student Fee Reports
* Dashboard Analytics
* Data Validation
* Dark Mode UI

---

## 👨‍💻 Author

Manas Meher

GitHub: https://github.com/yourusername

LinkedIn: Add your LinkedIn profile link here

---

⭐ If you found this project useful, feel free to star the repository.
