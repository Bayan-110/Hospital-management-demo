# Hospital-management-demo
a demo project for hospital resource management built with Python and MySQL-使用Python和MySQL开发的医院资源管理演示项目
![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![MySQL](https://img.shields.io/badge/MySQL-8.0+-blue?logo=mysql)
![Flask](https://img.shields.io/badge/Flask-Framework-green?logo=flask)
![License](https://img.shields.io/badge/License-MIT-lightgrey)
**English**|**[中文](#中文)**
---
## Project Overview

A lightweight,demo-ready Hospital Resource Management Systembackend,built to showcaase core competencies in **Python backend development** and **MySQL database design**.this project simulates real-word scenarios like inventory management and user authentication demonstarting my ability to build funtional and well-structured applications for the healthcare domain.

## Key Features

*   **🔐 Role-Based Access Control:** Demonstrates a simple login system with different permissions for 'Admin' and 'Staff' roles.
*   **💊 Inventory Management:** Full CRUD (Create, Read, Update, Delete) operations for medicine records, including tracking stock levels and automatic low-stock alerts.
*   **🗄️ Relational Database Design:** Efficiently structured MySQL database with proper table relationships (e.g., Users, Medicines).
*   **RESTful API Endpoints:** Provides a clear backend API structure (e.g., `/api/medicines`) for potential frontend integration.
*   **📊 Data Validation & Security:** Implements input validation and uses parameterized queries to prevent SQL injection, showcasing an awareness of application security.

## 🛠️ Technology Stack

*   **Backend:** Python
*   **Web Framework:** Flask
*   **Database:** MySQL
*   **ORM:** SQLAlchemy 
*   **Version Control:** Git & GitHub

## 📦 Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/Hospital-management-demo.git
    cd Hospital-management-demo
    ```

2.  **Create a virtual environment and activate it:**
    ```bash
    python -m venv venv
    # On Windows
    venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    *(Create a `requirements.txt` file listing your packages, e.g., `Flask==2.3.3`, `PyMySQL`, `SQLAlchemy`)*

4.  **Database Setup:**
    *   Create a MySQL database named `hospital_demo`.
    *   Configure your database connection in `config.py` or as environment variables.
    *   Run the script to create tables: `python create_tables.py`

5.  **Run the application:**
    ```bash
    python app.py
    ```
    The application will be available at `http://localhost:5000`.

## 🗂️ Project Structure

Hospital-management-demo/
├──app.py              # Main application entry point
├──config.py           # Configuration settings (DB credentials)
├──models.py           # Database models (SQLAlchemy classes)
├──create_tables.py    # Script to initialize the database
├──requirements.txt    # Project dependencies
├──static/             # CSS, JS, images (if any)
├──templates/          # HTML templates (if any)
└──README.md           # This file


## 🔮 Future Enhancements

*   Develop a simple React.js frontend for a full-stack demonstration.
*   Containerize the application using Docker.
*   Add more complex business logic (e.g., patient registration, appointment scheduling).

## 👨‍💻 About the Developer

I am a dedicated **Information Management and Information Systems** student at **China Medical University**, with a strong passion for bridging the gap between **healthcare and technology**. I am proficient in:

*   **Languages:** Python, C
*   **Databases:** MySQL
*   **Languages:** English (Fluent), Chinese (Native), Kazakh (Fluent)

I am actively seeking freelance opportunities and internships where I can apply my technical skills to solve real-world problems in the health-tech sector.

**📫 How to reach me:**
*   **Email:** Ba__Yan@outlook.com.


---

## 中文

## 🚀 项目简介

一个轻量级、可用于演示的医院资源管理系统后端，旨在展示我在 **Python 后端开发** 和 **MySQL 数据库设计** 方面的核心能力。本项目模拟了库存管理和用户认证等真实场景，证明了我有能力为医疗领域构建功能完善、结构清晰的应用程序。

## ✨ 核心功能

*   **🔐 基于角色的访问控制：** 演示了一个简单的登录系统，为“管理员”和“员工”角色提供了不同的权限。
*   **💊 药品库存管理：** 对药品记录完整的增删改查操作，包括库存追踪和自动低库存预警。
*   **🗄️ 关系型数据库设计：** 使用正确表关系的高效MySQL数据库结构。
*   **RESTful API 端点：** 提供清晰的后端API结构，便于潜在的前端集成。
*   **📊 数据验证与安全：** 实现了输入验证并使用参数化查询来防止SQL注入，展示了对应用安全的认知。

## 🛠️ 技术栈

*   **后端：** Python
*   **Web框架：** Flask
*   **数据库：** MySQL
*   **ORM：** SQLAlchemy
*   **版本控制：** Git & GitHub

## 👨‍💻 关于开发者

我是一名中国医科大学**信息管理与信息系统**专业的在校生，对于连接**医疗健康与信息技术**领域充满热情。我熟练掌握：

*   **技术栈：** Python, C
*   **数据库：** MySQL
*   **语言：** 英语（流利），中文（母语），哈萨克语（流利）

我正在积极寻找自由职业和实习机会，希望将我的技术技能应用于解决健康科技领域的实际问题。

**📫 联系方式：**
*   **邮箱：** Ba__Yan@outlook.com


---
*此项目仅用于演示目的。*
