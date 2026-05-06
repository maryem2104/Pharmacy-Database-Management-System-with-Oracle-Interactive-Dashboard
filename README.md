PharmaCare – Pharmacy Management System
Overview

PharmaCare is a full-stack pharmacy management platform designed to simplify and optimize pharmacy operations through a centralized multi-role system.

The application allows pharmacists, accountants, and sellers to work collaboratively on the same platform while maintaining secure role-based access and privileges.

The system provides real-time inventory management, sales tracking, order management, alerts, and financial monitoring through a modern responsive dashboard.

Features
Authentication & Authorization
Secure login system
Role-based access control (RBAC)
Separate privileges for:
Pharmacist
Accountant
Seller
Pharmacist Features
Manage medicines and products
Monitor stock availability
Track expiration dates
Receive low-stock alerts
Manage suppliers
Accountant Features
Monitor payments and transactions
Access financial records
Generate accounting reports
Track pharmacy revenues
Seller Features
Create and manage customer orders
Process sales
View product availability
Manage customer interactions
General Features
Responsive dashboard
Multi-user centralized platform
Real-time inventory tracking
Order and payment management
Product expiration monitoring
Alert system for critical products
Archive system for old records
Technologies Used
Frontend
React.js
JavaScript
HTML5
CSS3
Backend / Database
Oracle Database
Oracle SQL
System Architecture

The platform follows a client-server architecture:

Frontend (React)→Backend/API→Oracle Database
React handles the user interface and dashboard interactions
Oracle Database manages persistent storage and relational data
Different user roles interact with the same centralized database with controlled permissions
Database Design

The database contains several relational entities such as:

Users
Roles
Products
Suppliers
Orders
Payments
Alerts
Archives

Relationships are managed using Oracle relational modeling and SQL constraints.

Security
Authentication system
Role-based authorization
Restricted access depending on user role
Secure database interaction

Objective
The objective of PharmaCare is to digitalize pharmacy management processes and improve:


Operational efficiency


Data organization


Inventory monitoring


Financial tracking


Multi-user collaboration



Future Improvements


AI-based stock prediction


Sales analytics dashboard


Barcode scanning integration


Cloud deployment


Notification system


Mobile application support



Authors
Developed as an academic/full-stack management project using React and Oracle Database technologies.
