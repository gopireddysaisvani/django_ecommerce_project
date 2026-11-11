# OneStop Shopping – Django E-commerce Website

## Project Overview

OneStop Shopping is a Django-based e-commerce web application that allows users to browse products, create accounts, add products to their shopping cart, and place orders online.

The application provides a simple and user-friendly shopping experience with product management, cart functionality, order management, and online payment integration.

## Technologies Used

- **Backend:** Python, Django
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite
- **Image Handling:** Pillow
- **Payment Gateway:** Razorpay
- **Version Control:** Git and GitHub

## Features

- **User Authentication:** User registration, login, and logout.
- **Product Management:** Add, view, update, and manage products.
- **Product Categories:** Organize products into different categories.
- **Shopping Cart:** Add products, update quantities, and remove items.
- **Checkout:** Enter delivery details and place orders.
- **Order Management:** View orders and track delivery status.
- **Payment Integration:** Support for Cash on Delivery and Razorpay online payments.
- **User Profile:** Manage user profile information.

## Project Structure

```text
django_ecommerce_project/
│
├── accounts/
├── cart/
├── ecommerce_sep/
├── orders/
├── products/
├── media/
├── static/
├── templates/
├── manage.py
├── requirements.txt
├── Procfile
└── .gitignore
```

## Installation and Setup

Follow these steps to run the project on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/gopireddysaisvani/django_ecommerce_project.git
```

### 2. Navigate to the Project Folder

```bash
cd django_ecommerce_project
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

For Windows:

```bash
venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Configure Environment Variables

Create a `.env` file in the project root directory and configure the required settings, including:

```text
SECRET_KEY=your_django_secret_key
DEBUG=True
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
```

Use your own development credentials. Never upload your `.env` file or secret keys to GitHub.

### 7. Apply Migrations

```bash
python manage.py migrate
```

### 8. Create a Superuser

```bash
python manage.py createsuperuser
```

### 9. Run the Development Server

```bash
python manage.py runserver
```

Open your browser and visit:

```text
http://127.0.0.1:8000/
```

## Future Improvements

- Add product reviews and ratings.
- Add a wishlist feature.
- Improve product filtering and searching.
- Enhance the user interface and mobile responsiveness.

## GitHub Repository

[OneStop Shopping – Django E-commerce Project](https://github.com/gopireddysaisvani/django_ecommerce_project)

---

**Developed as a Django Full Stack E-commerce Project.**