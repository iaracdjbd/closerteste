# 🎓 Academic Portal - SQL Database Test

This project represents a complete SQL-based database design for a university or academic portal system. It simulates the core functionalities required to manage students, professors, courses, enrollments, tuition, and user access.

## 📚 Project Structure

The system is logically divided into **business schemas**:

- **pessoal** – Student and professor data
- **academico** – Courses, disciplines, enrollments, and classes
- **financeiro** – Tuition and payment control
- **administrativo** – User access and activity logs

## 🗃️ Features

- Complete **data model** with primary keys, foreign keys, and additional constraints (`CHECK`, `UNIQUE`, `DEFAULT`)
- Sample **data inserts** for demonstration
- Fully functional **stored procedures**:
  - `INSERT`, `UPDATE`, `DELETE` for all entities
- Analytical **views** for reports:
  - Students per course
  - Enrollments per discipline
  - Payments overdue
  - User access history
- Generated **class diagram**
- Designed for SQL Server

## 🧑‍💻 Technologies

- SQL Server (T-SQL)
- SSMS (SQL Server Management Studio)
- Draw.io (for diagrams)

## 📊 Diagrams

- Class Diagram with relationships

## 🚀 How to Use

1. Clone the repository.
2. Run the `CREATE TABLE` scripts.
3. Run the `INSERT` and `VIEW` scripts.
4. Execute stored procedures as needed for your use case.

## 👩‍🎓 Example Use Case

A university system where:
- Students enroll in courses via disciplines.
- Professors manage classes.
- Payments are tracked for each student.
- Admins can log into the system and track usage.

## 📂 Folder Structure
📦academic-portal ┣ 📜 create_tables.sql ┣ 📜 insert_data.sql ┣ 📜 views.sql ┣ 📜 procedures.sql ┣ 📜 diagrams/ ┃ ┗ 📊 er_diagram.png ┃ ┗ 📊 class_diagram.png ┗ 📘 README.md

## 🧠 Author

**Iara Claudia de Jesus Chagas**  
Data Analyst 
