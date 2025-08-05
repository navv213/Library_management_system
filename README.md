

# **Library Management System**

This project presents a fully functional **Library Management System** designed to streamline the daily operations of a library. Built using **SQL**, the system manages critical data related to books, customers, employees, and branch operations. It efficiently tracks book inventories, rentals, returns, and provides insights through analytical queries.

---

## **Database Initialization**

Start by creating a database named **`Library`** to serve as the central repository for all system data.

---

## **Core Features**

### 📚 **Book Inventory Management**

* Add, modify, or delete books from the collection.
* Maintain detailed records for each book, including:

  * Title
  * Genre
  * Rental price
  * Availability status
  * Author and publisher information

### 👤 **Customer Records**

* Store and manage customer profiles with data such as:

  * Full name and contact address
  * Registration date
  * Book issuance history

### 🧑‍💼 **Employee Management**

* Keep track of staff information:

  * Names, job titles, salaries
  * Assigned branch locations

### 🔄 **Book Lending System**

* Record the lending and return of books to customers
* Monitor which books are checked out and due for return

### 🏢 **Branch Administration**

* Organize information about library branches, including:

  * Branch ID and address
  * Manager details
  * Contact information

---

## **SQL Queries & Data Insights**

A range of SQL queries have been implemented to derive meaningful insights from the data. Key analytical tasks include:

1. **Fetch book titles, categories, and rental prices** for all currently available books.
2. **List all employees along with their salaries**, sorted in descending order of pay.
3. **Match issued books with customers** to show who has borrowed which books.
4. **Count the number of books in each category** to evaluate collection size by genre.
5. **Identify employees earning over Rs. 50,000**, showing their names and job roles.
6. **Find customers registered before January 1, 2022** who haven't borrowed any books.
7. **Report branch-wise employee distribution**, listing branch IDs and number of staff members.
8. **Retrieve names of customers who borrowed books in June 2023**.
9. **List all books categorized under "history"** from the book table.
10. **Show branches with more than 5 employees**, along with their employee counts.

---

Let me know if you want this version exported as a **PDF or Word file**, or if you need **ER diagrams or schema scripts** to go along with it.
