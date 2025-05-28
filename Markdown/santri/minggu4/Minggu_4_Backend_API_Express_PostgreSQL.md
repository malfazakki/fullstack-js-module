# 📅 Breakdown Harian - Minggu 4: Backend API (Express.js + PostgreSQL)

## 🎯 Tujuan Minggu Ini
- Memahami dasar-dasar backend development dengan Node.js dan Express.js
- Mampu membuat REST API sederhana untuk resource products, users, dan carts
- Menghubungkan aplikasi backend ke database PostgreSQL menggunakan pg atau Prisma
- Menerapkan konsep routing, controller, dan middleware pada aplikasi backend

---

## 📆 Hari 1 (Senin) - Instalasi & Setup Node.js + Express.js

### Materi Inti (2 Jam)
- Instalasi Node.js dan npm
- Inisialisasi project backend (npm init, struktur folder)
- Instalasi dan setup Express.js
- Membuat server Express sederhana (hello world)
- Studi kasus: Struktur folder scalable untuk backend

### Praktik Mandiri (8 Jam)
- Setup project backend baru
- Buat endpoint GET `/` yang menampilkan pesan welcome
- Eksplorasi struktur folder (routes, controllers, middlewares, config)
- Dokumentasikan langkah instalasi dan struktur project

---

## 📆 Hari 2 (Selasa) - Routing, Controller, Middleware

### Materi Inti (2 Jam)
- Konsep routing di Express.js (GET, POST, PUT, DELETE)
- Membuat controller terpisah untuk logic endpoint
- Penggunaan middleware (logging, error handling, body parser)
- Studi kasus: Routing dan controller untuk resource products

### Praktik Mandiri (8 Jam)
- Implementasi routing dan controller untuk products (CRUD sederhana, data dummy array)
- Tambahkan middleware logging dan error handler
- Buat dokumentasi endpoint (deskripsi, method, path)

---

## 📆 Hari 3 (Rabu) - Koneksi Database PostgreSQL (pg/Prisma)

### Materi Inti (2 Jam)
- Instalasi PostgreSQL lokal/remote
- Instalasi dan setup library `pg` atau Prisma
- Membuat koneksi ke database
- Studi kasus: Membaca dan menulis data produk ke PostgreSQL

### Praktik Mandiri (8 Jam)
- Setup database dan tabel products
- Implementasi koneksi database di project Express
- Refactor controller agar data CRUD products tersimpan di database
- Dokumentasikan skema database dan query dasar

---

## 📆 Hari 4 (Kamis) - REST API untuk Products, Users, Carts

### Materi Inti (2 Jam)
- Konsep REST API dan resource
- Mendesain endpoint untuk products, users, carts
- Studi kasus: API endpoint dan response JSON
- Best practice naming dan struktur RESTful

### Praktik Mandiri (8 Jam)
- Implementasi endpoint CRUD untuk users dan carts
- Uji endpoint dengan Postman/Insomnia
- Tambahkan validasi sederhana pada input data
- Dokumentasikan seluruh endpoint beserta contoh request/response

---

## 📆 Hari 5 (Jum'at) - Tugas & Presentasi

### Tugas Mingguan:
- Buat backend REST API lengkap untuk products, users, dan carts (CRUD)
- Koneksi ke PostgreSQL (data persistent)
- Struktur project rapi dan modular (routes, controllers, middlewares, config)
- Dokumentasi endpoint dan skema database

### Presentasi:
- Demo API (menggunakan Postman/Insomnia)
- Jelaskan arsitektur project, alur data, dan tantangan
- Review antar kelompok (feedback & saran)

---

## 💡 Tips untuk Pemula
- Selalu gunakan struktur folder yang jelas dan modular
- Pisahkan logic controller, routing, dan middleware
- Gunakan environment variable untuk konfigurasi sensitif (dotenv)
- Dokumentasikan setiap endpoint dan skema database
- Eksplorasi dokumentasi resmi (Express.js, PostgreSQL, Prisma)

---

## 📋 Checklist Mingguan
- [ ] Setup project backend dengan Express.js
- [ ] Implementasi routing, controller, dan middleware
- [ ] Koneksi dan CRUD data ke PostgreSQL
- [ ] Membuat REST API untuk products, users, carts
- [ ] Presentasi dan review tugas