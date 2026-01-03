
# 📊 Sales Tracker CLI System (STCS)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![CLI](https://img.shields.io/badge/Interface-Command_Line-orange)
![CSV](https://img.shields.io/badge/Export-CSV-green)
![Status](https://img.shields.io/badge/Status-Production_Ready-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)
![License](https://img.shields.io/badge/License-MIT-success)

---

## 📖 Table of Contents
- [Overview](#-overview)
- [Quick Start](#-quick-start)
- [System Requirements](#-system-requirements)
- [Installation Guide](#-installation-guide)
- [Getting Started](#-getting-started)
- [Features](#-features)
- [User Guide](#-user-guide)
- [Reports & Visualization](#-reports--visualization)
- [Troubleshooting](#-troubleshooting)
- [Data Backup & Export](#-data-backup--export)
- [Development Roadmap](#-development-roadmap)
- [Technical Details](#-technical-details)
- [FAQ](#-faq)
- [Support](#-support)
- [License](#-license)

---

## 🎯 Overview

**Sales Tracker CLI System (STCS)** is a lightweight Python-based command-line application designed to help individuals and small businesses **record, manage, and analyze sales data** efficiently.

It replaces notebooks and spreadsheets with a structured digital workflow while remaining simple, fast, and fully offline.

### ✨ Key Benefits
- ✅ Simple CLI interface (no GUI needed)
- ✅ Secure user login system
- ✅ Accurate sales record keeping
- ✅ Easy editing of past records
- ✅ CSV export for Excel analysis
- ✅ ASCII-based sales performance graphs
- ✅ Works completely offline

---

## 🚀 Quick Start

### **Run the Application**
```bash
python main.py
````

---

## 💻 System Requirements

### **Minimum Requirements**

* **Operating System:** Windows, macOS, or Linux
* **Python Version:** Python 3.8 or higher
* **Storage:** 20MB free space
* **Memory:** 1GB RAM

### **Verify Python Installation**

```bash
python --version
```

Expected output:

```text
Python 3.8.x or higher
```

---

## 📦 Installation Guide

### **Step 1: Download the Project**

1. Download or clone the repository
2. Extract the folder to your preferred location

### **Step 2: Install Dependencies (if any)**

```bash
pip install -r requirements.txt
```

### **Step 3: Run the Program**

```bash
python main.py
```

---

## 🎮 Getting Started

### **First Launch**

On first run, the system will:

* Create required data files
* Prompt for user login or registration
* Initialize sales storage

### **Login Example**

```
Username: admin
Password: ******
```

---

## 🏆 Features

### **1. User Authentication 🔐**

* Secure login system
* Multiple user support
* Session-based access

### **2. Sales Management 💰**

* Record daily sales
* Edit past sales entries
* Automatically calculate totals

### **3. Reporting System 📑**

* Daily sales summary
* Monthly performance overview
* Total revenue calculations

### **4. CSV Export 📤**

* Export sales data to CSV
* Open seamlessly in Excel or Google Sheets

### **5. ASCII Sales Graph 📈**

* Terminal-based visual representation
* Quick performance insight without external tools

---

## 📖 User Guide

### **Typical Workflow**

```
1. Login
2. Record a new sale
3. Edit or review past records
4. View sales reports
5. Export to CSV if needed
6. View ASCII sales graph
```

### **Menu Navigation**

* Enter numbers to select options
* `0` to go back
* `Y/N` for confirmations
* `Ctrl + C` to exit safely

---

## 📊 Reports & Visualization

### **Sample ASCII Graph**

```
Sales Performance:
Mon: ****
Tue: ******
Wed: ***
Thu: ********
Fri: *****
```

### **Available Reports**

| Report  | Description                 |
| ------- | --------------------------- |
| Daily   | Sales for the current day   |
| Weekly  | 7-day sales overview        |
| Monthly | Monthly performance summary |
| Total   | Overall sales and revenue   |

---

## 🛠️ Troubleshooting

### **Common Issues**

#### **1. Python not recognized**

```bash
# Solution:
Install Python from https://python.org
Ensure "Add Python to PATH" is checked
```

#### **2. Program crashes on start**

* Ensure correct Python version
* Check required files exist
* Reinstall dependencies

#### **3. CSV file not opening**

* Open manually with Excel
* Ensure file is not already in use

---

## 💾 Data Backup & Export

### **CSV Export**

* Data can be exported anytime
* Stored in `/exports/` directory

### **Manual Backup**

```bash
copy data/sales_data.json backup/
```

---

## 🗺️ Development Roadmap

### **Phase 1 – Core CLI (v1.0) ✅**

* User login
* Sales recording
* Basic reports

### **Phase 1.5 – Enhanced Features (v1.5) ✅**

* Record editing
* CSV export
* ASCII graph visualization

### **Phase 2 – Planned 🚀**

* Date range filtering
* Role-based access
* Database (SQLite) integration
* Advanced analytics

---

## 🔧 Technical Details

### **Architecture**

```
CLI Interface
   ↓
Business Logic
   ↓
Data Storage (CSV / JSON)
```

### **File Structure**

```
sales_tracker/
├── main.py                 # Application entry point
├── README.md               # Project documentation
├── letters.txt             # Character / symbol reference file
├── sales.db                # Sales database file
├── SMS/                    # Core application package
│   ├── SalesRecord.py      # Sales recording & editing logic
│   ├── Database.py         # Database connection & queries
│   ├── Inventory.py        # Inventory management
│   ├── Report.py           # Reports & ASCII graph generation
│   ├── Utils.py            # Helper / utility functions
│   ├── Help.py             # Help & documentation system
│   ├── User.py             # User authentication & management
│   └── __init__.py         # Package initializer
└── data/                   # Data storage & backups


```

### **Performance**

* Fast startup
* Low memory usage
* Handles thousands of records smoothly

---

## ❓ FAQ

**Q: Does this work offline?**
Yes. Internet is not required.

**Q: Can I open the data in Excel?**
Yes. Exported CSV files open directly in Excel.

**Q: Is this for large businesses?**
It is best suited for individuals and small businesses.

**Q: Is my data secure?**
Yes. Data is stored locally on your computer.

---

## 🆘 Support

### **Before Asking for Help**

* Check this README
* Verify Python version
* Restart the application

### **Contact**

* **Telegram:** @ENJ_digitalhub
* **WhatsApp:** +2347078804953

---

## 📄 License

**MIT License**

You are free to:

* Use
* Modify
* Distribute

With attribution.

---

## 👨‍💻 Author Information

**Maintainer:** ENJ Digital Hub
**Project:** Sales Tracker CLI System
**Version:** 1.5
**Status:** Production Ready
**Language:** Python

---

### 🎯 Project Philosophy

> “Simple tools, clear data, better decisions.”

---

**Built with simplicity and efficiency in mind. 📊🐍**

```
