# **Supermarket Inventory and Supply Management System**

## **Overview**
This project is an **Information System** for managing supermarket inventory and supplier relationships. It provides tools to efficiently manage product stock, supplier orders, and optimize supply processes.

The system includes:  
- **SQLite** database for persistent storage  
- **Command-Line Interface (CLI)** for quick interaction  
- **Swing-based GUI** for an intuitive graphical interface  
- **Object-Oriented Programming (OOP)** principles  
- **Layered Architecture** for clean separation of concerns  
- **Design Patterns** (Singleton, Observer, DAO, Factory)  
- **Unit Testing** using **JUnit**

---

## **Features**

### **Inventory Management**
- **Add, Update, and Delete Products**: Manage product details like cost, price, quantity, location, and discounts.  
- **Stock Tracking**:  
   - Automatic alerts for **low stock levels**.  
   - Manage **expired products** and **damaged goods**.  
- **Reports**: Generate detailed reports, including:  
   - Inventory Report  
   - Low Stock Report  
   - Expired and Damaged Products Report  
- **Price History**: View historical price changes and applied discounts.  
- **Manual Stock Updates**: Input manual stock counts for reconciliation.  
- **Periodic Orders**: Update recurring supply orders to maintain inventory levels.  

### **Supplier Management**
- **Supplier Details**: Manage supplier data such as contact information, payment terms, and delivery schedules.  
- **Product-Supplier Relationship**:  
   - Link suppliers to products with specific unit prices and quantities.  
- **Discounts and Offers**:  
   - Apply cash discounts for bulk purchases.  
   - Free product offers for meeting purchase thresholds.  
- **Order Optimization**:  
   - Automatically identifies suppliers offering the best price.  
   - Combines suppliers when exact quantities aren’t available.
