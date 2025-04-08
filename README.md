# 🛍️ E-Commerce Web App – Grothzi Labs

This is a full-featured **E-Commerce Web Application** developed for **Grothzi Labs**, designed to provide a seamless shopping experience with dynamic product management, user accounts, secure checkout, and more.

Built with **HTML, CSS, JavaScript** on the frontend and powered by the **Django** framework on the backend.

---

## 🚀 Key Features

- 🛒 Add-to-cart and real-time cart updates  
- 🔐 Secure user login, signup, and session handling  
- 🧾 Checkout and order placement system  
- 📦 Admin panel for product and order management  
- 💳 Payment gateway integration (optional or customizable)  
- 📬 Order confirmation via email (if configured)  
- 📱 Fully responsive design  

---

## 🧑‍💻 Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla JS)  
- **Backend**: Python, Django (MVT architecture)  
- **Database**: SQLite (default) or PostgreSQL/MySQL (optional)  
- **Templating**: Django Templates  
- **Authentication**: Django Auth System  
- **Admin Interface**: Django Admin Panel  

---

## ⚙️ Setup & Installation

> Follow these steps to run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/grothzi-ecommerce-app.git
cd grothzi-ecommerce-app
```

### 2. Create and Activate a Virtual Environment

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file (if needed) or update `settings.py` for email, payment, etc.

### 5. Run Migrations

```bash
python manage.py migrate
```

### 6. Create a Superuser (Admin)

```bash
python manage.py createsuperuser
```

### 7. Run the Development Server

```bash
python manage.py runserver
```

> Visit `http://127.0.0.1:8000` in your browser to use the app.  
> Visit `http://127.0.0.1:8000/admin/` for the admin panel.


---

## 📸 Screenshots

_Add screenshots here for:_
- Homepage
- Product Page
- Cart
- Checkout
- Admin Panel

---

## 📌 Future Improvements

- Payment integration (Stripe/Razorpay)  
- Wishlist and user reviews  
- Product filtering and sorting  
- Invoice generation (PDF)  
- Progressive Web App (PWA) support  

---

## 🤝 Contributing

Pull requests are welcome! Feel free to fork the repo and submit improvements.

---

## 📜 License

Licensed under the **MIT License**.

---

## 👨‍💻 Developed By

**Aditya Raj**  
Software Developer at Grothzi Labs  
🌐 [Portfolio](https://your-portfolio-link.com) | 🔗 [LinkedIn](https://linkedin.com/in/aditya-raj)
