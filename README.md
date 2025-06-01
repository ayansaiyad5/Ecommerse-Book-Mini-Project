# Bookly 
# E-Commerce Book Platform

A full-featured e-commerce platform specifically designed for selling and managing e-books, built with PHP and MySQL.

## 🌟 Features

- User Authentication System
- E-Book Browsing and Search
- Shopping Cart Functionality
- Secure Checkout Process
- Order Management System
- Admin Dashboard
  - E-Book Management
  - User Management
  - Order Management
  - Contact Management
- Responsive Design

## 🔧 Requirements

- PHP 7.0 or higher
- MySQL Database
- Web Server (Apache/Nginx)

## 📥 Installation

1. Clone the repository:
```bash
git clone https://github.com/ayansaiyad5/Ecommerse-Book-Mini-Project.git
```

2. Import the database:
- Create a new MySQL database
- Import the `shop_db.sql` file into your database

3. Configure the database connection:
- Open `config.php`
- Update the database credentials:
```php
$conn = mysqli_connect('localhost','your_username','your_password','your_database_name');
```

4. Set up your web server:
- Point your web server to the project directory
- Ensure the `uploaded_img` directory has write permissions

## 👥 Access Credentials

### Admin Access
- Email: admin@gmail.com
- Password: 123

### Demo User Access
- Email: ayansaiyad5@gmail.com
- Password: 123

## 🚀 Usage

1. Access the website through your web browser
2. Register a new account or login with existing credentials
3. Browse e-books, add items to cart, and complete the checkout process

## 📱 Admin Features

1. Login with admin credentials
2. Access the admin dashboard at `/admin_page.php`
3. Manage:
   - E-Books (Add/Edit/Delete)
   - Users
   - Orders
   - Contact Messages

## 📁 File Structure

- `*.php` - Main application files
- `css/` - Stylesheet files
- `js/` - JavaScript files
- `images/` - Static images
- `uploaded_img/` - E-Book cover images
- `shop_db.sql` - Database structure

## 🔒 Security Features

- Password hashing
- SQL injection prevention
- XSS protection
- Session management

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

For any queries or support, please contact:
- Email: ayansaiyad5@gmail.com
- GitHub: [ayansaiyad5](https://github.com/ayansaiyad5)
