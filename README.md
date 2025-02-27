# MoveWiseAI
# 🧠 NLP-Driven Logistics Tracking System

This project integrates **Natural Language Processing (NLP)** with **SQL** to create a seamless logistics tracking system. Users can ask **natural language queries** (e.g., *"How long did Article 1 stay at Sydney?"*), and the system **automatically converts** them into **SQL queries** to fetch results.

---

## 🚀 Features
- ✅ **NLP to SQL Conversion** – Users can query the system in plain English
- ✅ **Tracks Articles & Customers** – `Article_ID` & `Customer_ID`
- ✅ **Timestamp-Based Tracking** – `Start_Timestamp`, `End_Timestamp`
- ✅ **Dwell & Transit Time Calculation** – Accurate shipment analytics
- ✅ **SQLite Integration** – Fast, in-memory database for real-time queries

---

## 📂 Database Schema
| Column Name          | Data Type  | Description |
|----------------------|-----------|-------------|
| `Article_ID`        | INTEGER   | Unique ID for each article |
| `Customer_ID`       | TEXT      | Unique customer ID |
| `Facility`          | TEXT      | Name of the facility |
| `Start_Timestamp`   | DATETIME  | Time when the article arrived at the facility |
| `End_Timestamp`     | DATETIME  | Time when the article left the facility |
| `Processing_Time_Min` | INTEGER | Processing time in minutes |
| `Day`               | TEXT      | Day of the week |
| `Weight`            | FLOAT     | Weight of the shipment (kg) |

---
