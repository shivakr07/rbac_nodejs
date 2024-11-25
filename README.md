
# Role Based Access Control Application

This is a **Role-Based Access Control (RBAC)** application built using **Node.js**, **Express**, and **Passport.js**. It serves as a starting point for any project that requires **authentication** and **authorization**.  

## Features
- **Authentication** using Email and Password.
- Easily extendable to support OAuth/OAuth2.0 (e.g., Google, Facebook, GitHub, Apple).
- Based on the **MVC (Model-View-Controller)** design pattern.
- Uses **Mongoose** as an ORM for **MongoDB**.
- **Passport.js** for local authentication.
- Production-ready setup.

## Prerequisites
- **Node.js** installed on your system.
- **MongoDB** installed and running.

---

## Setup Instructions

### Step 1: Clone the Repository
```bash
git clone https://github.com/shivakr07/rbac_nodejs
```

### Step 2: Navigate to the Project Directory
```bash
cd role-based-access-control
```

### Step 3: Install Dependencies
```bash
npm install
```

### Step 4: Configure Environment Variables
Create a `.env` file in the project root and add the following:
```
PORT=3000
MONGODB_URI=YOUR_MONGODB_URI (example: mongodb://localhost:27017)
DB_NAME=YOUR_DB_NAME
```

### Step 5: Install MongoDB
Refer to the [MongoDB Installation Guide](https://docs.mongodb.com/manual/installation/) for your operating system.  

### Step 6: Start MongoDB
On Linux (Ubuntu), start the MongoDB service:
```bash
sudo service mongod start
```

### Step 7: Start the Application
```bash
npm start
```

---

## Technologies Used
- **Node.js**: JavaScript runtime.
- **Express.js**: Web application framework.
- **Passport.js**: Authentication middleware.
- **MongoDB**: NoSQL database.
- **Mongoose**: MongoDB ORM.
- **dotenv**: Environment variable management.

---

## Author
**Truly Mittal**  

---


## License
This project is licensed under the [MIT License](LICENSE).

---