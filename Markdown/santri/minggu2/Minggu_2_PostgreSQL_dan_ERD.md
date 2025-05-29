
# 📅 Breakdown Harian - Minggu 2: PostgreSQL & ERD

## 🎯 Tujuan Minggu Ini
- Memahami dasar-dasar database relasional dan SQL
- Menguasai perintah CRUD di PostgreSQL
- Mampu merancang ERD sederhana untuk sistem e-commerce
- Mengenal dan menggunakan tools visualisasi database

---

## 📆 Hari 1 (Senin) - Pengenalan PostgreSQL & Instalasi

### Materi Inti (2 Jam)
- Apa itu Database Relasional?
- Kenapa memilih PostgreSQL?
- Instalasi PostgreSQL + GUI (pgAdmin)
- Struktur dasar database: database, table, row, column

### Praktik Mandiri (8 Jam)
- Install PostgreSQL dan pgAdmin di lokal
- Membuat database baru
- Membuat table sederhana: `users`
- Menjelajahi pgAdmin UI
- Membuat catatan dari dokumentasi PostgreSQL

---

## 📆 Hari 2 (Selasa) - Dasar SQL: CREATE, INSERT, SELECT

### Materi Inti (2 Jam)
- Perintah SQL dasar:
  - `CREATE TABLE`
  - `INSERT INTO`
  - `SELECT`
- Tipe data umum di PostgreSQL (VARCHAR, INT, BOOLEAN, TIMESTAMP)
- Studi kasus: membuat dan membaca data user

### Praktik Mandiri (8 Jam)
- Buat table `products`, `categories`
- Isi data dummy menggunakan `INSERT`
- Menampilkan data dengan `SELECT`
- Filter menggunakan `WHERE`, urutkan dengan `ORDER BY`
- Simulasi membuat laporan data sederhana

---

## 📆 Hari 3 (Rabu) - SQL Lanjutan: UPDATE, DELETE, RELASI

### Materi Inti (2 Jam)
- Relasi antar tabel (foreign key)
- Perintah `UPDATE`, `DELETE`
- JOIN antar tabel: `INNER JOIN`, `LEFT JOIN`
- Studi kasus: update data produk, relasi user & order

### Praktik Mandiri (8 Jam)
- Buat tabel `orders` dan `order_items`
- Praktikkan relasi antar tabel
- Coba JOIN untuk mengambil data pesanan dengan nama user dan produk
- Simulasi soft delete dengan kolom `is_deleted`

---

## 📆 Hari 4 (Kamis) - Mendesain ERD E-Commerce

### Materi Inti (2 Jam)
- Apa itu ERD? (Entity Relationship Diagram)
- Komponen ERD: entitas, atribut, relasi
- Studi kasus: users, products, cart, orders, payments
- Tools: dbdiagram.io, draw.io

### Praktik Mandiri (8 Jam)
- Mendesain ERD untuk sistem e-commerce
- Gunakan dbdiagram.io untuk visualisasi
- Bahas relasi one-to-many dan many-to-many
- Review desain teman (peer review)

---

## 📆 Hari 5 (Jum'at) - Tugas & Presentasi

### Tugas Mingguan:
- Buat ERD final proyek e-commerce (format dbdiagram.io atau draw.io)
- Buat skrip SQL untuk membuat tabel sesuai ERD
- Insert minimal 5 data dummy ke setiap tabel

### Presentasi:
- Presentasikan ERD dan jelaskan alur data
- Review antar kelompok (feedback & saran)
