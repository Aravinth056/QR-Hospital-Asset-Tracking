# Results

## 📌 Overview

This folder contains the testing and functional results of the **Intelligent Hospital Asset Tracking and Management System**.

The system was evaluated across different user roles, asset states, asset operations, and management functions.

---

## 🧪 Testing Areas

The system was tested for:

- User login
- Role-based access
- QR asset identification
- Asset Take operation
- Asset Return operation
- Asset Transfer operation
- Damage reporting
- Asset availability
- Delayed-return monitoring
- Maintenance status
- Transaction history
- Dashboard functions
- Responsive interface

---

## 🔐 Login and Role Testing

The system was tested with the three user portals:

| Portal | Main Function | Result |
|---|---|---|
| Nurse & Staff | Operational asset management | Tested |
| Office | Asset and system management | Tested |
| Management | Monitoring and reporting | Tested |

Protected pages were checked to ensure that access was restricted according to the user's role.

---

## 🏷️ QR Asset Identification

QR-based asset identification was tested through the browser interface.

The system can identify an asset and display information such as:

- Asset ID
- Asset name
- Current status
- Condition
- Latest confirmed location
- Current holder

---

## 🔄 Asset Operation Testing

### Take Asset

The system verifies that the asset is available and that the user is authorised before recording a Take transaction.

**Expected Result:** Asset changes from `Available` to `In Use`.

---

### Return Asset

The system verifies the current holder before recording the Return transaction.

**Expected Result:** Asset changes from `In Use` to `Available`.

---

### Transfer Asset

The system records the movement of an asset to another authorised location or responsible employee.

**Expected Result:** Asset remains `In Use` while the latest confirmed location or responsible person is updated.

---

### Damage Reporting

A damage report records the reported issue and places the asset into a maintenance-related state.

**Expected Result:** Asset is removed from normal available quantity until the maintenance process is completed.

---

## 📊 Availability Testing

The system monitors available quantities for asset types.

```text
Available Quantity
        ↓
Compare With Minimum Quantity
        ↓
Below Minimum?
    ↙       ↘
  Yes        No
   ↓          ↓
Low        Normal
Availability Status
