# 🛒 Django Backend E-Commerce Project

Hey guys 👋,  
Welcome to my **Django Advanced E-Commerce Backend Project**!  
This project demonstrates advanced Django concepts including **payment integration**, **email-based password reset**, **secure authentication**, and much more.

---

## 📽 Project Video / Learning Purpose
In this project (and tutorial video), we cover:
- **Django advanced concepts**
- How to **integrate a payment gateway** (like Razorpay or Stripe)
- How to **send account activation emails**
- How to **reset password via email**
- Building a **fully functional e-commerce backend** from scratch

---

## ✨ Features
- **User Authentication**
  - Sign up, log in, log out
  - Email verification for account activation
- **Password Management**
  - Reset password via secure token email link
- **Product Management**
  - Add, edit, delete products
  - Category-based filtering
- **Shopping Cart**
  - Add/remove products
  - Quantity management
- **Payment Gateway Integration**
  - Secure payment processing
- **Order Tracking**
  - Order history and details for users
- **Responsive Backend**
  - Works with any front-end framework (React, Angular, Vue, etc.)

---

## 🛠 Tech Stack
- **Backend:** Django (Python 3)
- **Database:** SQLite (can be upgraded to PostgreSQL/MySQL)
- **Frontend:** Django Templates (HTML, CSS, JS)
- **Payment Gateway:** Razorpay / Stripe
- **Email Service:** SMTP (Gmail) for sending activation & reset links

---

## 📂 Project Structure
ecommerce/
│
├── authcart/ # Authentication app (login, signup, reset password)
├── products/ # Product management app
├── orders/ # Order & payment handling
├── ecommerce/ # Project settings & URLs
├── templates/ # HTML templates
├── static/ # Static files (CSS, JS, images)
└── manage.py



---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/prem-cre/e-commerce.git
cd e-commerce


EMAIL_HOST_USER=your_email@gmail.com
EMAIL_HOST_PASSWORD=your_app_password
PAYMENT_GATEWAY_KEY=your_payment_gateway_key


Run Development Server
bash
Copy code
python manage.py runserver
