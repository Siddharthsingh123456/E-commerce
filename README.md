# PHP & MySQL E-Commerce Application

A full-stack e-commerce learning project built with PHP, MySQL, HTML, CSS, and JavaScript. The repository includes a customer shopping area, product catalog, cart and checkout flows, and an administrative interface.

## Features represented in the source
- Product listing, search, and product detail pages
- Shopping cart and checkout-related pages
- Customer registration, login, profile, and order pages
- Admin login and product/category/brand management pages
- Order and payment management pages
- MySQL database script
- Bootstrap-based frontend assets

## Technology
- PHP
- MySQL/MariaDB
- HTML, CSS, JavaScript
- Bootstrap

## Requirements
- PHP-enabled local web server (XAMPP, WAMP, or equivalent)
- MySQL or MariaDB
- Browser
- phpMyAdmin or another SQL client for database import

## Local setup
1. Clone the repository and place the `E-Commerce/` directory in your web server document root.
2. Create a database in MySQL.
3. Import `E-Commerce/Database/ecommerce_1.sql`.
4. Review `E-Commerce/includes/connect.php` and configure local database host, database name, username, and password.
5. Start Apache and MySQL.
6. Open the project through your local server, for example `http://localhost/E-Commerce/`.

Use the actual database settings and table definitions in the supplied SQL/configuration files; do not assume production credentials.

## Screenshots
The `E-Commerce/ui/` folder contains interface screenshots, including the home page, products, cart, and admin screens. Open those files on GitHub to preview the existing UI.

## Security checklist before deployment
- Replace default or hardcoded credentials.
- Hash passwords using a modern password-hashing API.
- Use prepared SQL statements to prevent SQL injection.
- Validate and authorize every admin action server-side.
- Protect sessions and checkout/payment flows.
- Validate uploaded images and restrict file types and sizes.
- Use HTTPS and environment-based secrets in production.

This repository is an educational project and should receive a security review before public deployment or real transactions.

## License
No license file is currently specified. Contact the repository owner before reuse.
