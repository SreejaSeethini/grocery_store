# 🛒 Grocery Store Application

Welcome to the Grocery Store Application! This web app allows you to manage products, handle orders, and view a comprehensive dashboard to track store activities.

## ✨ Features

- **Product Management**: Easily add, update, delete, and view products.
- **Order Management**: Create and manage customer orders seamlessly.
- **Dashboard**: Get an overview of the store's performance with a user-friendly dashboard.

## 🛠 Technologies

### Frontend

- 🌐 HTML
- 🎨 CSS
- 💻 JavaScript
- 📦 Bootstrap

### Backend

- 🐍 Python
- 🌶 Flask

### Database

- 🗄 MySQL

## 📦 Installation

### Prerequisites

- 🐍 Python 3.x
- 🗄 MySQL
- 📦 Node.js and npm (for Bootstrap and JavaScript dependencies)

### Steps

1. **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/grocery-store.git
    cd grocery-store
    ```

2. **Set up the virtual environment**
    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. **Install backend dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4. **Install frontend dependencies**
    ```bash
    npm install
    ```

5. **Set up the MySQL database**

    - Create a database named `grocery_store`.
    - Run the following command to set up the database schema:
      ```bash
      flask db init
      flask db migrate -m "Initial migration."
      flask db upgrade
      ```

6. **Configure environment variables**

    Create a `.env` file in the root directory and add the following configurations:
    ```env
    FLASK_APP=run.py
    FLASK_ENV=development
    DATABASE_URL=mysql+pymysql://username:password@localhost/grocery_store
    ```

7. **Run the application**
    ```bash
    flask run
    ```

The application will be accessible at `http://127.0.0.1:5000`.

## 🚀 Usage

- Navigate to `http://127.0.0.1:5000` to access the application.
- Use the **Product Management** module to add, update, delete, and view products.
- Use the **Order Management** module to create and manage customer orders.
- Check the **Dashboard** for an overview of store performance.

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. **Fork the repository.**
2. **Create a new branch.**
3. **Make your changes and commit them.**
4. **Push your changes to your fork.**
5. **Create a pull request.**

---

Thank you for visiting our Grocery Store Application repository! We hope you find it useful and easy to use. Happy coding! 😊
