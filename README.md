
# 🚀 Minerva Mobiles – Stock Management using RAP (SAP S/4HANA)

## 📌 Project Overview

This project implements a **Stock Management System** using the **RESTful ABAP Programming Model (RAP)** in SAP S/4HANA. It enables efficient handling of stock data including creation, update, deletion, and real-time visibility through modern OData services.

The solution follows a **clean architecture approach** using CDS views, behavior definitions, and service bindings to build a scalable and enterprise-ready application.

---

## 🎯 Key Features

✨ Create, Update, Delete stock records
📊 Real-time stock visibility
🔒 Data validation (e.g., negative quantity restriction)
⚡ High-performance data access using CDS Views
🌐 OData V4 service exposure for UI/Fiori integration
🏗️ Clean RAP-based layered architecture

---

## 🧱 Architecture Overview

The project is built using RAP layers:

```
Database Table → CDS View → Behavior Definition → Service Definition → Service Binding → UI
```

### 🔹 Layers Explained

* **Database Table**: Stores stock data (`ZMINERVA_STOCK`)
* **CDS View (ZI_MINERVA_STOCK)**: Defines data model
* **Behavior Definition**: Handles CRUD operations
* **Behavior Implementation**: Business logic & validations
* **Service Definition**: Exposes CDS entity
* **Service Binding**: Publishes OData V4 service

---

## 🗂️ Data Model

| Field Name    | Description     |
| ------------- | --------------- |
| STOCK_ID      | Unique Stock ID |
| MATERIAL_ID   | Material Number |
| MATERIAL_NAME | Material Name   |
| QUANTITY      | Available Stock |
| PLANT         | Plant Location  |

---

## ⚙️ Technologies Used

* SAP S/4HANA
* ABAP (Advanced Business Application Programming)
* RAP (RESTful ABAP Programming Model)
* CDS Views
* OData V4 Services
* Eclipse (ABAP Development Tools)

---

## 🔄 Functional Flow

1. User interacts with UI / API
2. Request hits OData Service
3. Service calls CDS View
4. Behavior Definition processes logic
5. Data is stored/retrieved from database

---

## 🛠️ Implementation Highlights

✔ Managed RAP scenario used for faster development
✔ Standard CRUD operations enabled
✔ Validation implemented to prevent invalid data
✔ Service binding allows direct preview/testing
✔ Clean and modular code structure

---

## 🧪 Testing

* Service tested using **Service Binding Preview**
* CRUD operations validated via OData interface
* Data consistency verified at database level

---

## 📈 Future Enhancements

🚀 Low stock alert system
🚀 Integration with Purchase Order module
🚀 Fiori UI application
🚀 Stock analytics dashboard
🚀 Role-based access control

---

## 💼 Use Case

This system can be used by:

* Inventory Managers
* Warehouse Teams
* Procurement Departments

To efficiently manage and monitor stock levels in real-time.

---


## ⭐ Project Value

This project demonstrates:

* Strong understanding of **modern SAP development (RAP)**
* Hands-on experience with **enterprise-level architecture**
* Ability to build **scalable and production-ready applications**

---

## 👨‍💻 Author

**Kumar Gaurav**
SAP & AI Enthusiast







