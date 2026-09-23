# QR-Based Intelligent Hospital Asset Tracking and Management System

A low-cost, browser-based hospital asset tracking and management system that uses QR codes to identify reusable hospital assets, record their latest confirmed location, track responsibility, and manage availability.

## Project Objective

The objective is to develop a browser-based system for managing reusable hospital assets without requiring specialised RFID, BLE, or GPS tracking hardware.

## Key Features

- QR-based asset identification
- Latest confirmed location tracking
- Asset take, return, and transfer
- Role-based access for Nurse & Staff, Office, and Management
- Availability monitoring
- Low-availability warnings
- Return-request and delayed-return handling
- Damage and maintenance tracking
- Internal messaging
- Emergency alerts
- Management dashboards and reports
- Browser-based camera QR scanning

## Technology Stack

- Python 3
- Flask
- SQLite
- HTML5
- CSS3
- JavaScript
- Werkzeug
- PythonAnywhere
- HTTPS

## System Architecture

Browser Interface → Flask Application Server → SQLite Database

## Hardware / Access Requirements

- Smartphone or tablet with camera
- Laptop or desktop computer
- Printed QR code labels
- Printer
- Internet connection
- Cloud-hosted application server

## Project Structure

- `images/` – Application screenshots and project images
- `hardware/` – Access devices and QR label requirements
- `software/` – Application and software files
- `docs/` – Documentation and technical details
- `results/` – Testing and results

## Testing

The system was functionally tested for role-based login, asset take/return/transfer, duplicate-action prevention, damage reporting, maintenance, low availability, delayed returns, messaging, emergency alerts, reports, responsive access, and camera-based QR scanning.

## Applications

- Hospital asset management
- Medical equipment tracking
- Equipment availability monitoring
- Maintenance tracking
- Hospital operational management
