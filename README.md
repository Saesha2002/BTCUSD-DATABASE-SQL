# BTCUSD Database SQL

![MySQL](https://img.shields.io/badge/MySQL-8.4-blue)
![GitHub last commit](https://img.shields.io/github/last-commit/Saesha2002/BTCUSD-DATABASE-SQL)

A SQL database project that fetches, stores, and manages *XAUUSD (Gold/US Dollar)* financial data from 2021 to 2025. This repository includes the SQL file for easy setup and integration.

---

## 📋 Table of Contents
- [Project Overview](#-project-overview)
- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Repository Structure](#-repository-structure)
- [Contributing](#-contributing)
- [Contact](#-contact)

---

## 🚀 Project Overview

This project focuses on:
- Fetching historical *XAUUSD* data (Date, Time, Open, High, Low, Close) from 2021 to 2025.
- Using *MySQL Workbench 8.4* to design and upload the database.
- Exporting the SQL file for portability and sharing.
- Hosting the SQL file in this repository for public access.

---

## ✨ Features

- *Data Columns*:
  - Date: Trading date (YYYY-MM-DD)
  - Time: Trading time (HH:MM:SS)
  - Open: Opening price
  - High: Daily high price
  - Low: Daily low price
  - Close: Closing price

- *Tools Used*:
  - MySQL Workbench 8.4 for database design and management.
  - SQL file export for seamless deployment.

- *Time Range: Data spans from **January 2021 to December 2025*.

---

## 📥 Installation

1. *Clone the Repository*:
   ```bash
   git clone https://github.com/Saesha2002/BTCUSD-DATABASE-SQL


2. *Import the SQL File:*
- Open MySQL Workbench.
- Connect to your server.
- Use File > Run SQL Script to execute xauusd_data.sql.

---

## 🛠 Usage

Query the database to analyze historical XAUUSD data. Example query:

```sql
SELECT * FROM xauusd_data 
WHERE Date BETWEEN '2023-01-01' AND '2023-12-31';

Thank you for the opportunity to complete this task! Your support and collaboration have made this project a rewarding experience.
