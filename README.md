###### [(ระบบนี้ Transfer มาจาก Github Account เก่า --> https://github.com/TOEYJIRAKIT/Flutter-InventoryManagement)](https://github.com/TOEYJIRAKIT/Flutter-InventoryManagement)

## 🚀 **Project Name** :

Inventory Management - Inventory Management Mobile Application

## 📌 **Project Overview** :

This Inventory Management application is a cross-platform mobile app built with Flutter and Dart that helps businesses efficiently manage their inventory data. It allows users to store, update, and delete product information through an intuitive user interface. The app connects to a local JSON server for data handling and storage, making it ideal for small businesses, personal projects, or as a learning tool for mobile development.

## 🎯 **Objective** :

- Create a mobile app for inventory management with CRUD functionality.
- Provide a user-friendly interface for managing product catalogs.
- Connect to a lightweight backend (JSON Server) for local data storage.

## ✨ **Key Features** :

- **Add & Manage Products** – Add new items with details like name, description, image, price, and rating.
- **Edit & Delete** – Update product details or remove them from the inventory.
- **Mobile-Friendly UI** – Clean and responsive Flutter UI.

## 🛠 **Tech Stack** :

- **Frontend:** Dart, Flutter
- **Other:** JSON Server

## 📂 **GitHub Repository (Source Code)** :

- [https://github.com/TOEYJIRAKID/Inventory-Management-App](https://github.com/TOEYJIRAKID/Inventory-Management-App)

## ⚙️ **Installation & Setup** :

1. **Clone the repository**  
   ```bash
   git clone https://github.com/TOEYJIRAKID/Inventory-Management-App.git
   ```  
2. **Install json-server**  
   ```bash
   npm install json-server
   ```  
3. **Run the JSON Server**  
   ```bash
   npx json-server data.json --watch --port 3000
   ```  
4. **Open http://localhost:3000 to view the json data.**

## 📃 Example JSON Data :

Here’s a sample of how inventory management data is structured in JSON format:

```json
{
  "users": [
    {
      "id": 1,
      "username": "Jirakit Aiadhet",
      "email": "a@test.com",
      "password": "1q2w3e4r",
      "gender": "Male",
      "address": "999/999 songkhla",
      "birthdate": "2002-04-23",
      "age": "18"
    }
  ],
  "catalogs": [
    {
      "id": 1,
      "itemName": "submarine",
      "detail": "no engine",
      "price": "150",
      "rating": 5,
      "images": "https://images.unsplash.com/photo-1588947130823-db168fa854ac?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80",
      "date": "2023-09-10"
    }
  ]
}
```

## 📽️ **Project Preview** :

![Inventory Management App](https://github.com/user-attachments/assets/536d949f-f5da-470d-a16b-a4cdc97b509b)
