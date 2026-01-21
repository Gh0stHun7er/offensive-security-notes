# SQL Injection – PortSwigger Web Security Academy

---

## 🔹 Overview

SQL Injection is a web vulnerability where **user input is directly included in SQL queries**
without proper validation, allowing attackers to manipulate database queries.

---

## 🔹 Impact of SQL Injection
- Authentication bypass
- Sensitive data leakage
- Database modification or deletion

---

## 🔹 Common Types of SQL Injection
- Error-based
- Union-based
- Boolean-based

---

## 🔹 Prevention (Defensive Perspective)
- Prepared / parameterized statements
- Input validation & sanitization
- Least privilege database access

---

# 🧪 Lab Practice

## Lab Name
**SQL injection vulnerability in WHERE clause**

---

## Goal
Exploit SQL Injection to retrieve hidden data from the database.

---

## Vulnerability Description
The application **directly uses unsanitized user input** in a SQL `WHERE` clause,
making it vulnerable to SQL Injection.

---

## Exploitation Approach
- Tested application input for SQL logic manipulation
- Used logical condition injection to bypass filters

---

## Payload Used
