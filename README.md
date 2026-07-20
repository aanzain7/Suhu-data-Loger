# Blog CRUD - Laravel 13

Aplikasi web sederhana untuk manajemen postingan blog dengan operasi CRUD.

## Fitur
- 📋 Daftar postingan
- ✏️ Tambah postingan baru
- 📖 Detail postingan
- 🔄 Edit postingan
- 🗑️ Hapus postingan

## Teknologi
- Laravel 13
- SQLite
- Tailwind CSS
- Vite

## Instalasi
```bash
composer install
npm install
cp .env.example .env
php artisan key:generate
touch database/database.sqlite
php artisan migrate
php artisan serve
npm run dev