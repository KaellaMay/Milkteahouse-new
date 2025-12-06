# Tea Avenue Milk Tea House

## Description
Tea Avenue is a web-based milk tea ordering system built with PHP and MySQL. It allows users to browse a menu, add items to their cart, place orders, and manage their accounts. The application also includes an admin panel for managing products, users, and orders.

## Features
- User registration and login
- Browse and view product menu
- Add products to cart
- Checkout and order confirmation
- View order history
- Admin panel for managing products, users, and orders
- Responsive design using Bootstrap

## Technologies Used
- **Backend**: PHP
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Icons**: FontAwesome
- **Hosting**: InfinityFree (for database)

## Installation and Setup
1. **Clone the Repository**:
   ```
   git clone <repository-url>
   cd milkteahouse
   ```

2. **Set Up Local Environment**:
   - Install a local web server like XAMPP, WAMP, or MAMP.
   - Ensure PHP and MySQL are enabled.

3. **Database Setup**:
   - Import the SQL file `if0_37821724_crud_milkteahouse.sql` into your local MySQL database.
   - Update database credentials in `connection.php` if necessary (currently set to remote InfinityFree database).

4. **Run the Application**:
   - Place the project folder in your web server's root directory (e.g., htdocs for XAMPP).
   - Start the web server and MySQL.
   - Navigate to `http://localhost/milkteahouse/index.php` in your browser.

## Usage
- **Home Page**: View welcome message and about section.
- **Menu**: Browse available milk tea products.
- **Cart**: Add items, view cart, and proceed to checkout.
- **Login/Register**: Create an account or log in to access personalized features.
- **Admin Panel**: Accessible via `admin index.php` for managing the system (requires admin privileges).

## File Structure
- `index.php`: Home page
- `menu.php`: Product menu
- `cart.php`: Shopping cart
- `checkout.php`: Order checkout
- `login.php` / `register.php`: Authentication
- `admin index.php`: Admin dashboard
- `connection.php`: Database connection
- `db.php`: Additional database functions
- Various PHP files for CRUD operations on products, users, and orders
- Image files for products and backgrounds

## Author
Mark Francis Cullamat  
Email: markfrancis.cullamat@hcdc.edu.ph  
Facebook: [tamingmarkfrancis](https://www.facebook.com/tamingmarkfrancis)  
Instagram: [tamingmarkfrancis](https://www.instagram.com/tamingmarkfrancis/)

## License
This project is for educational purposes. No specific license is applied.
