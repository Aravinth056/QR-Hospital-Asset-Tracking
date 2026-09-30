# System Overview

## 📌 Introduction

The **Intelligent Hospital Asset Tracking and Management System**, called **Asset Track**, is a browser-based system developed to manage reusable hospital assets.

The system uses **QR codes** to identify assets and records their movements, responsible users, locations, availability, and maintenance status.

---

## 🏥 Hospital Asset Management

Hospitals use many movable assets, such as:

- Wheelchairs
- Stretchers
- Oxygen cylinders
- Infusion pumps
- Portable monitors
- Emergency equipment
- Diagnostic equipment

These assets can move between different hospital locations.

The system provides a centralized method to record these movements.

---

## 🔧 Main System Components

```text
QR Code
   ↓
Browser / Camera
   ↓
Flask Web Application
   ↓
SQLite Database
   ↓
Role-Based Dashboards
   ↓
Asset Monitoring & Reports
