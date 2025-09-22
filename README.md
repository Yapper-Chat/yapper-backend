# 💬 Yapper Chat System Backend (Laravel + MySQL)
This is the backend API for the real-time chat system, built with Laravel and MySQL.
It handles authentication, user management, message storage, and real-time broadcasting.

# 🚀 Features
🔐 User Authentication with Laravel Sanctum
💬 Messaging API – send and receive messages between users
⚡ Real-time Events with Laravel Broadcasting (Pusher or Laravel WebSockets)
🗄 MySQL Database for persisting users and messages
🛡 Secure API endpoints with middleware protection

# 🛠️ Tech Stack
Framework: Laravel 11
Database: MySQL
Authentication: Laravel Sanctum
Real-time: Laravel Broadcasting + Pusher / Laravel WebSockets

# ⚙️ Setup Instructions
1. Clone the repo
git clone https://github.com/yourusername/chat-backend.git
cd chat-backend

2. Install dependencies
composer install

3. Configure environment
Copy .env.example to .env:
cp .env.example .env

Generate app key:
php artisan key:generate

Set your database credentials in .env:
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=chatapp
DB_USERNAME=root
DB_PASSWORD=

4. Run migrations
php artisan migrate

5. Start the server
php artisan serve


Backend will run at http://localhost:8000

# 🔑 Authentication
