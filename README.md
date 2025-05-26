📚 Bookstore Laravel Project – Functionality
This Laravel-based Bookstore web application provides a simple and user-friendly interface for managing and purchasing books online. Below are the main features and functionalities:


https://youtu.be/NBPZvfI-TTk?si=cC5VMogPdSyrAh02

🚀 Features
📖 Book Management

Add, edit, delete, and view books.
Each book includes title, author, ISBN, price, and stock quantity.
Supports pagination and search functionality.
👨‍💼 Author Management

Add, update, or remove authors.
Associate books with authors.
🔎 Advanced Search

Search books by title, author, ISBN.
Filter books by price range and availability in stock.
🛠️ Tech Stack
Backend: Laravel 10+
Database: MySQL / MariaDB
Frontend: Blade templating / Bootstrap / Tailwind CSS (if used)
Others: Laravel Eloquent ORM, Artisan Console, Laravel Validation
---📂 Project Structure ├── app/ │ ├── Models/Book.php │ ├── Models/Author.php │ ├── Http/Controllers/ │ └── ...

├── resources/views/ │ ├── books/ │ ├── authors/ │ └── layouts/ ├── routes/web.php └── database/seeders/

---🙌 Acknowledgements |-Laravel Framework |-Bootstrap |-Community packages and contributors

⚙️ Installation
# Clone the repo
git clone https://github.com/yourusername/bookstore.git
cd bookstore

# Install dependencies
composer install

# Copy .env and configure
cp .env.example .env
php artisan key:generate

# Set your database credentials in .env
DB_DATABASE=your_database
DB_USERNAME=your_username
DB_PASSWORD=your_password

# Run migrations and seeders
php artisan migrate --seed

# Serve the application
php artisan serve


---

## ⚙️ Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/bookstore.git
cd bookstore

# Install dependencies
composer install

# Copy .env and configure
cp .env.example .env
php artisan key:generate

# Set your database credentials in .env
DB_DATABASE=your_database
DB_USERNAME=your_username
DB_PASSWORD=your_password

# Run migrations and seeders
php artisan migrate --seed

# Serve the application
