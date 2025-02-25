# 📚 Library Management System using Django

A robust and user-friendly **Library Management System** designed to streamline library operations for both users and administrators. This web application enables users to borrow and return books seamlessly, while administrators can manage the library’s inventory, monitor user activity, and issue fines for overdue returns.

Built using **Django**, **HTML**, **CSS**, and **JavaScript**, this system ensures a smooth and interactive user experience.

---

## 🚀 Features

### 👥 **User Functionalities**
- 🔍 **Search Books**: Easily search for books by title, author, or genre.
- 📖 **Borrow Books**: Borrow available books and track borrowing history.
- 🔄 **Return Books**: Return borrowed books with automatic due date verification.
- 🔔 **Notifications**: Receive alerts for upcoming due dates and overdue books.
- 💼 **Profile Management**: Manage personal details and view borrowing activity.

### 🔑 **Admin Functionalities**
- 📚 **Manage Books**: Add, update, or remove books from the inventory.
- 👥 **Manage Users**: Create, block, or unblock user accounts.
- 📅 **Track Borrowed Books**: Monitor borrowing history and active loans.
- 💰 **Issue Fines**: Automatically issue fines for overdue books and manage collections.
- 📊 **Reports & Analytics**: Generate reports on book borrowing patterns and user activity.

---

## 💻 **Technologies Used**
- 🐍 **Django** – A high-level Python web framework.
- 🌐 **HTML5**, **CSS3**, **JavaScript** – For responsive and interactive UI.
- 🎨 **Bootstrap** – Responsive design framework.
- 🗄️ **SQLite** – Lightweight database (default Django database).
- 🛠️ **Django Admin Panel** – Simplified backend management.

---

## ⚙️ **How to Run the Project**

### 📋 **Prerequisites**
Ensure you have the following installed:
- Python 3.x
- Django (latest version)

### 🛠️ **Setup Instructions**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/library-management-system.git
   cd library-management-system
   
2. **Create a Virtual Environment Create and activate a virtual environment to manage project dependencies.**
   ```bash
    python -m venv venv
    source venv/bin/activate
   ```

3. **Apply Database Migrations Set up the database schema using Django migrations.**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

4. **Create a Superuser (Admin Account) Create an administrator account to manage the system.**
   ```bash
   python manage.py createsuperuser
   ```

5. **Run the Development Server Start the Django development server to run the application locally.**
   ```bash
   python manage.py runserver
   ```

#### Access the Application

User Panel: http://127.0.0.1:8000/
Regular users can browse books, borrow, and return them through this panel.

Admin Panel: http://127.0.0.1:8000/admin/
Admins can manage books, users, issue fines, and monitor library activities through this panel.


