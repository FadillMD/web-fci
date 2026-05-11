# PT. First Cable Industries - Corporate Website

[![Laravel Version](https://img.shields.io/badge/Laravel-11.x-red.svg)](https://laravel.com)
[![TailwindCSS Version](https://img.shields.io/badge/TailwindCSS-3.x-blue.svg)](https://tailwindcss.com)
[![Alpine.js](https://img.shields.io/badge/Alpine.js-3.x-orange.svg)](https://alpinejs.dev)

Website profil perusahaan resmi PT. First Cable Industries yang dibangun menggunakan framework Laravel. Project ini dirancang dengan pendekatan modular menggunakan Blade Components untuk memastikan kode yang bersih, mudah dikelola, dan performa yang optimal.

## 🚀 Fitur Utama

- **Dynamic Product Routing**: Sistem routing otomatis untuk katalog produk kabel.
- **Reusable Blade Components**: Komponen UI (Navbar, Cards, Link) yang dapat digunakan berulang kali untuk efisiensi koding.
- **Responsive Navigation**: Hamburger menu dan dropdown yang dioptimalkan untuk perangkat mobile menggunakan Alpine.js.
- **Dynamic SEO Title**: Judul tab browser yang berubah otomatis sesuai halaman yang aktif.
- **Interactive UI**: Animasi hover dan transisi halus menggunakan Tailwind CSS.

## 🛠️ Tech Stack

- **Framework:** Laravel 11
- **Styling:** Tailwind CSS (via Vite)
- **Interactivity:** Alpine.js
- **Icons:** Heroicons (SVG)

## 📁 Struktur Project (Penting)

Berikut adalah beberapa lokasi file kunci yang dikembangkan dalam project ini:

- `resources/views/components/layout.blade.php` : Master layout website.
- `resources/views/components/nav-link.blade.php` : Komponen link navigasi pintar.
- `resources/views/components/nav-dropdown.blade.php` : Komponen dropdown menu universal.
- `resources/views/produk/` : Folder berisi halaman detail teknis setiap jenis kabel.
- `routes/web.php` : Konfigurasi routing yang efisien dengan grouping.

## ⚙️ Cara Instalasi

1. **Clone Repository**
   ```bash
   git clone [https://github.com/FadillMD/web-fci.git](https://github.com/FadillMD/web-fci.git)
   cd first-cable-web

2. **Instal Dependensi PHP**

```Bash
composer install
Instal Dependensi Frontend

```Bash
npm install
npm run dev
Konfigurasi Environment

```Bash
cp .env.example .env
php artisan key:generate
Jalankan Server

```Bash
php artisan serve
📄 Lisensi
Project ini dibuat untuk tujuan portofolio dan pengembangan internal PT. First Cable Industries.
