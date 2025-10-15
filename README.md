# 🍽️ Kitchen Inventory Database - MySQL Project

## 📖 Overview
**Kitchen InventoryDB** is a MySQL-based database project designed to manage kitchen inventory efficiently.  
It tracks **items, daily stock, suppliers, and supplier-item relationships**, ensuring proper inventory control, reorder management, and expiry tracking.

---

## 🧩 Features
- Manage kitchen **items** with categories, units, reorder levels, and expiry dates  
- Track **daily stock** with opening, received, used, and closing stock automatically calculated  
- Maintain **supplier information** and link items to suppliers  
- Supports **many-to-many relationships** between items and suppliers  
- Ideal for **restaurant, catering, or home kitchen inventory management**

---

## 🗄️ Database Schema
| Table Name | Description |
|-------------|--------------|
| **ITEMS** | Stores item details: name, category, unit, reorder level, expiry |
| **DAILY_STOCK** | Tracks stock movements and calculates closing stock automatically |
| **SUPPLIER** | Contains supplier details including contact and city |
| **SUPPLIER_ITEMS** | Many-to-many relationship connecting suppliers to items |

---

## ⚙️ Technologies Used
- **Database:** MySQL  
- **Language:** SQL  
- **Tools:** MySQL Workbench / Command Line  

---

## 📥 How to Run the Project
1. **Clone this repository**
   ```bash
   git clone https://github.com/prawin5557/Kitchen_inventoryDB.git
