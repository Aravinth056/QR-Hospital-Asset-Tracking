# Hardware

## 📌 Overview

The **Intelligent Hospital Asset Tracking and Management System** is primarily a software-based system.

It does not require dedicated RFID, BLE, GPS, or other tracking hardware.

Users can access the system through a web browser using a smartphone, tablet, or computer.

---

## 💻 User Devices

The system can be accessed using:

- Smartphone
- Tablet
- Desktop computer
- Laptop

---

## 📷 QR Code Scanning

A smartphone or computer with a supported camera can be used to scan QR codes attached to hospital assets.

The QR code provides the asset identification value to the web application.

A manual-code option can also be used when camera scanning is not available.

---

## 🏷️ Physical QR Labels

QR labels are attached to individual hospital assets.

Examples include:

- Wheelchairs
- Stretchers
- Oxygen cylinders
- Infusion pumps
- Portable monitors
- Emergency equipment

QR labels can also be placed at authorised hospital locations.

---

## 🔄 Hardware Interaction

```text
Physical Hospital Asset
        ↓
     QR Label
        ↓
 Smartphone / Computer Camera
        ↓
    Web Application
        ↓
 Flask Backend
        ↓
 SQLite Database

