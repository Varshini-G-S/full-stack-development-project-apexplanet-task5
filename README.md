# Online Book Store Project (PHP & MySQL)


A **web-based e-book store** built using **PHP, MySQL, HTML, CSS, Bootstrap, and JavaScript**.  
This project allows users to browse and search books, view details, and see books categorized by category and sub-category. Admins can manage books through a simple backend interface.  

---

## ⚡ How It Works
- Users interact with a web interface to search or browse books.  
- PHP handles the backend logic, generates SQL queries, and fetches data from the MySQL database.  
- Books are stored in a structured database with categories, subcategories, and related tables.  
- Admins can add, edit, or remove books via the admin panel.

---

## 🛠 Tools & Technologies Used
- **Backend:** PHP  
- **Database:** MySQL  
- **Frontend:** HTML, CSS, Bootstrap, JavaScript  

---

## Project Dashboard Overview

```mermaid
flowchart LR
    subgraph Frontend
        A[User Interface]
        B[Search & Browse Books]
        C[Book Details Page]
    end

    subgraph Backend
        D[PHP Scripts]
        E[Admin Panel]
    end

    subgraph Database
        F[MySQL Database]
        G[Books Table]
        H[Categories/Subcategories]
        I[Users & Orders]
    end

    %% Connections
    A --> B --> C --> D
    D --> F
    E --> D
    F --> G
    F --> H
    F --> I

    %% Styling
    style Frontend fill:#f0f8ff,stroke:#333,stroke-width:1px
    style Backend fill:#ffe4b5,stroke:#333,stroke-width:1px
    style Database fill:#e0ffe0,stroke:#333,stroke-width:1px

```
---

### ✅ Project Summary

This Online Book Store Project is a **full-stack web application** built with **PHP, MySQL, and Bootstrap**.  

It allows users to **browse, search, and view books** organized by categories and sub-categories. Admins can **manage the book inventory** through a backend panel.  

The system demonstrates **dynamic content rendering**, **database-driven functionality**, and **frontend-backend integration**.  

It is ideal for students and beginners to learn:
- **Web development using PHP**
- **Database design with MySQL**
- **Frontend development using HTML, CSS, and Bootstrap**
- **Basic e-commerce logic and user management**

This project gives a clear overview of how a **real-world online bookstore** works from **user interaction to database management**.


