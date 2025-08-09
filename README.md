
# 🛒 Full-Stack eCommerce Website (Django + PayPal Integration)

[![Django](https://img.shields.io/badge/Django-4.x-green?logo=django)](https://www.djangoproject.com/)  
[![PayPal](https://img.shields.io/badge/Payments-PayPal-blue?logo=paypal)](https://developer.paypal.com/)  
[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org/)  


---

## 📌 Overview
This project is a **fully functional eCommerce website** built with Django, supporting **both user and guest checkout** capabilities.  

Customers can:
- Browse & add multiple products (physical & digital) to their cart
- Checkout securely as a **registered user** or a **guest**
- Pay via **PayPal** (account or debit/credit card)

The focus is to provide a seamless checkout experience with **no forced account creation**, improving conversion rates.

---

## 🚀 Features

### 🛍 Store & Cart
- Add multiple items to the cart
- Support for physical & digital products
- Edit/remove items before checkout

### 👤 User Checkout
- Login/Sign up to make purchases
- View pending & completed orders
- Access order details anytime

### 👥 Guest Checkout
- Purchase without creating an account
- Items stored in browser cookies
- Option to create an account after purchase

### 💳 Payment Integration
- **PayPal integration** for global payments  
  - Checkout with PayPal account  
  - Checkout with PayPal debit/credit card  

---

## 📑 Checkout Flow

### **Authenticated User**
1. Add item(s) to cart  
2. Edit order  
3. Checkout & pay  
4. View pending & previous orders + details  

### **Guest Checkout**
1. Add item(s) to cart  
2. Edit order  
3. Checkout & pay  
4. (Optional) Create an account to view order  

---


## 🛠 Tech Stack
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (dev)
- **Payments**: PayPal SDK
- **Auth**: Django authentication + cookies for guests

---


## 💡 Motivation
> "A good eCommerce website should always give the user the ability to checkout without creating an account."  


Forcing account creation can **reduce sales**. This project ensures **convenience** and **security** while maximizing user experience.

---

## 🖼 Screenshots
<img width="1899" height="910" alt="image" src="https://github.com/user-attachments/assets/8659f730-4c57-4170-8235-8ad8e92aeb9b" />
<img width="1906" height="909" alt="image" src="https://github.com/user-attachments/assets/5bd938c7-a6a9-4618-bf61-af2a608d4a61" />
<img width="1898" height="776" alt="image" src="https://github.com/user-attachments/assets/b3f2422d-2e94-4d18-831f-d5e5c71997dd" />



---

## ⚙ Installation

### 1️⃣ Clone the repository
```
git clone https://github.com/yourusername/ecommerce-website.git
cd ecommerce-website
```
2️⃣ Create a virtual environment
```
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```
3️⃣ Install dependencies
```
pip install -r requirements.txt
```
4️⃣ Set up environment variables
Create a .env file with:
``
PAYPAL_CLIENT_ID=your_paypal_client_id
PAYPAL_SECRET=your_paypal_secret
DEBUG=True
SECRET_KEY=your_django_secret_key
``
5️⃣ Run migrations
```
python manage.py makemigrations
python manage.py migrate
```
6️⃣ Start development server
```
python manage.py runserver
```
Visit http://127.0.0.1:8000/



---


Developed by [DULA](https://github.com/dulagudeta)
