# 🍽️ Restaurant Management System

Restaurant Management System is a cloud-based web application developed using **HTML, CSS, JavaScript, and Firebase Realtime Database**. The application is deployed on **Amazon EC2** using the **Apache HTTP Server**. It enables customers to browse the menu, place food orders, generate bills, and allows administrators to manage live restaurant orders.

---

# 🚀 Features

- Restaurant Menu Management
- Food Search
- Add to Cart
- Quantity Management
- PDF Bill Generation
- Live Kitchen Orders
- Admin Dashboard
- Firebase Realtime Database
- Responsive User Interface
- AWS EC2 Deployment

---

# 🛠️ Tech Stack

## Frontend
- HTML5
- CSS3
- JavaScript

## Database
- Firebase Realtime Database

## Libraries
- jsPDF
- Google Fonts

## AWS Services
- Amazon EC2
- Amazon VPC
- Internet Gateway
- Route Table
- Security Group
- Elastic IP
- Apache HTTP Server

---

# 📂 Project Structure

```
Restaurant-Management-System/
│
├── index.html
└── README.md
```

---

# ⚙️ Project Workflow

```
Customer
     │
     ▼
Restaurant Website
     │
     ▼
Browse Food Menu
     │
     ▼
Add Items to Cart
     │
     ▼
Place Order
     │
     ▼
Firebase Realtime Database
     │
     ▼
Admin Dashboard
     │
     ▼
Kitchen Staff
     │
     ▼
Generate PDF Bill
```

---

# ☁️ AWS Deployment Architecture

```
User
 │
 ▼
Internet
 │
 ▼
Internet Gateway
 │
 ▼
Amazon VPC
 │
 ▼
Public Subnet
 │
 ▼
Amazon EC2
(Apache HTTP Server)
 │
 ▼
Restaurant Management System
 │
 ▼
Firebase Realtime Database
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/bala172/Restaurant-Management-System.git
```

Move to the project directory

```bash
cd Restaurant-Management-System
```

Copy the project to the Apache web directory

```bash
sudo cp index.html /var/www/html/
```

Start Apache Server

```bash
sudo systemctl enable httpd
sudo systemctl restart httpd
```

Open the application

```
http://<Elastic-IP>
```

---

# ☁️ Deployment

The project is deployed using the following AWS services:

- Amazon EC2
- Amazon VPC
- Internet Gateway
- Route Table
- Security Group
- Elastic IP
- Apache HTTP Server
- Firebase Realtime Database

---

# 🎯 Project Objectives

- Develop a Restaurant Management System.
- Deploy the application on AWS EC2.
- Manage restaurant orders digitally.
- Store order information using Firebase.
- Generate PDF bills automatically.
- Provide an Admin Dashboard for order management.
- Deliver a responsive and user-friendly interface.

---

# 🔮 Future Enhancements

- Online Payment Gateway
- Customer Login System
- Table Reservation
- Inventory Management
- Email Notifications
- QR Code Menu
- Sales Reports
- AI-based Food Recommendation

---

# 👨‍💻 Developed By

**Kadali Bala Nagendra**

B.Tech – Computer Science and Engineering

BVC Engineering College
