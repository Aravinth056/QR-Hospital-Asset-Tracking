# Working Principle

## 📌 Overview

The **Intelligent Hospital Asset Tracking and Management System** uses QR codes, a browser-based interface, Flask backend, and SQLite database to record and manage hospital asset transactions.

The system records the **latest confirmed location** of an asset through successful scans or transactions.

---

## 🔄 Overall Working Flow

```text
User Login
    ↓
Select Portal
    ↓
Scan / Identify Asset
    ↓
View Asset Information
    ↓
Confirm Location
    ↓
Select Action
    ↓
Validate Permission & Asset Status
    ↓
Save Transaction
    ↓
Update Asset Status
    ↓
Update Availability
    ↓
Display Updated Information
