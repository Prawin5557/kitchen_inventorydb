# kitchen_inventorydb
MySQL Kitchen Inventory Database — includes table structures, relationships, and sample data for managing kitchen stock, suppliers, and daily usage.
# 🍽️ Kitchen Inventory Database (MySQL)

A complete **MySQL-based kitchen inventory management system** for tracking items, suppliers, daily stock, and reorder levels.  
This project includes SQL scripts to create tables, relationships, and sample data for analysis and practice.

---

## 📋 Features
- Organized database schema with **foreign key relationships**
- Auto-calculated **closing stock**
- Sample **insert data** for quick setup
- Includes **supplier and item management**
- Easy to use for **college projects or learning SQL**

---

## 🧱 Database Schema Overview

### 🗂️ Tables Included
| Table Name | Description |
|-------------|--------------|
| `ITEMS` | Master list of kitchen items, category, unit, and expiry date |
| `DAILY_STOCK` | Tracks daily opening, received, used, and closing stock |
| `SUPPLIER` | Supplier details with contact information |
| `SUPPLIER_ITEMS` | Mapping between suppliers and items they provide |

---

## 🧰 Technologies Used
- **MySQL 8.0+**
- **SQL Workbench / phpMyAdmin**
- **Excel / Power BI (optional for reporting)**

---

## 🚀 How to Set Up

### 1️⃣ Clone the repository
```bash
git clone https://github.com/YOUR-USERNAME/kitchen-inventory.git
cd kitchen-inventory
