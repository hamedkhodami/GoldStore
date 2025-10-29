# 🛍️ GoldStore | Online Gold & Silver Platform

GoldStore is a web-based platform designed to display, manage, and calculate real-time prices of gold and silver. Built with Django and Django Templates, the system supports two primary user roles: Customer and Admin.

---

## 🎯 Project Goals

- Display real-time buy/sell prices for gold and silver
- Provide a precise calculator for converting weight ↔ price
- Manage educational and market-related articles
- Offer an admin panel for price control, user management, and content publishing
- Deliver a fast, intuitive, and reliable user experience

---

## 👥 User Roles

### 1. Customer
- Register and log in
- View live prices of gold and silver
- Use the price calculator based on metal type and purity
- Access weekly price charts
- Read published articles
- Submit support tickets
- Manage personal profile

### 2. Admin
- Access admin dashboard
- View user list and support tickets
- Publish new articles
- Manage prices (manual or via external API)
- Toggle between manual and automatic price display modes

---

## 🧮 Core Features

### 🔐 Authentication & Role Management
- Role-based registration and login
- Redirect to appropriate dashboard based on role

### 💰 Pricing System
- Buy/sell prices for gold and silver
- Manual entry or API-based price fetching
- Calculate other purities based on 18K reference
- Real-time price updates via WebSocket or AJAX

### 🧠 Price Calculator
- Gold: 18K, 20K, 21K, 22K, 24K + Melted Gold + Jewelry
- Silver: 925 and another type (TBD)
- Convert between weight ↔ price for both buy and sell

### 📊 Charts & History
- Weekly price history list
- Interactive price trend charts
- Display of latest published articles

### 📝 Content & Public Pages
- Article detail pages
- Archive of all articles
- "About Us" page

### 🎫 Support System
- Submit and track support tickets
- Admin responses and notifications

---


## 👨‍💻 Lead Developer

**Hamed Khodami**  
Backend Developer | Python & Django Specialist  
[GitHub](https://github.com/hamedkhodami) | [Website](http://hamedkhodami.ir)

---