# Karter - Full-Featured Django eCommerce Platform

## Project Overview
Karter is a comprehensive eCommerce web application built using Python Django Framework, offering a robust and feature-rich online shopping experience.

## 🚀 Key Features

### User Management
- Custom user authentication system
- Secure profile management
- Profile picture upload
- Password change functionality

### Product Catalog
- Dynamic product categories
- Detailed product listings
- Unlimited product image gallery
- Interactive review and rating system
  - Supports half-star ratings
  - Comprehensive product feedback mechanism

### Shopping Cart
- Add, increment, decrement, and remove cart items
- Seamless cart management
- Real-time cart updates

### Order Processing
- Complete order workflow
- Secure payment integration
- Automatic post-order functionalities:
  - Inventory quantity reduction
  - Order received email notification
  - Cart clearing
  - Order completion page
  - Invoice generation

## 🛠️ Technology Stack
- **Backend:** Python Django
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite/PostgreSQL
- **Payment Integration:** [PayPal]

## 🔧 Installation

### Prerequisites
- Python 3.8+
- Django 3.2+
- pip

### Setup Steps
1. Clone the repository
```bash
git clone https://github.com/sohailshk/Ecommerce_Website
cd greatkart
```

2. Create virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Run migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

5. Create superuser
```bash
python manage.py createsuperuser
```

6. Run development server
```bash
python manage.py runserver
```

## 📦 Project Structure
```
greatkart/
│
├── accounts/          # User management app
├── carts/             # Shopping cart functionality
├── category/          # Product categories
├── orders/            # Order processing
├── products/          # Product management
├── templates/         # HTML templates
└── greatkart/         # Project configuration
```

## 🔐 Environment Variables
Create a `.env` file with the following:
```
SECRET_KEY=your_secret_key
DEBUG=True
DATABASE_URL=sqlite:///db.sqlite3
PAYMENT_KEY=your_payment_gateway_key
```

## 📜 License
Distributed under the MIT License. See `LICENSE` for more information.

## 🤝 Contact
Your Name - sohailsaif504@gmail.com

Project Link: [https://github.com/sohailshk/Ecommerce_Wesbite](https://github.com/sohailshk/Ecommerce_Website)
