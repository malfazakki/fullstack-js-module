# 📘 Hari 4 - Pengenalan ERD & Relasi Database

## 🎯 Tujuan Pembelajaran
- Memahami konsep dasar Entity Relationship Diagram (ERD) dalam perancangan database
- Mengenal entitas, atribut, dan relasi antar entitas
- Mampu membaca dan membuat ERD sederhana untuk sistem e-commerce
- Melatih kemampuan visualisasi struktur data sebelum implementasi database

---

## 1. Apa itu ERD?
Entity Relationship Diagram (ERD) adalah diagram yang digunakan untuk memodelkan struktur data dan hubungan antar data dalam sebuah sistem. ERD sangat penting sebelum membuat database agar struktur data rapi, konsisten, dan scalable.

### Analogi:
Bayangkan ERD seperti denah rumah:
- **Entitas** = Ruangan (misal: kamar, dapur)
- **Atribut** = Properti ruangan (misal: luas, warna)
- **Relasi** = Pintu/penghubung antar ruangan

---

## 2. Komponen Utama ERD

### a. Entitas
Entitas adalah objek utama yang datanya ingin disimpan. Dalam sistem e-commerce, contoh entitas:
- **User** (pengguna)
- **Produk** (barang dijual)
- **Transaksi** (pembelian)
- **Cart** (keranjang belanja)

### b. Atribut
Atribut adalah data detail yang dimiliki entitas.
- **User:** id, nama, email, password, alamat
- **Produk:** id, nama_produk, harga, stok, deskripsi
- **Transaksi:** id, tanggal, user_id, total, status
- **Cart:** id, user_id, produk_id, qty

### c. Relasi
Relasi adalah hubungan antar entitas. Contoh relasi pada e-commerce:
- **User – Transaksi:** Satu user bisa punya banyak transaksi (one-to-many)
- **Transaksi – Produk:** Satu transaksi bisa melibatkan banyak produk (many-to-many, biasanya lewat tabel detail transaksi)
- **User – Cart:** Satu user punya satu/multiple cart (one-to-many)
- **Cart – Produk:** Satu cart bisa berisi banyak produk (many-to-many)

---

## 3. Contoh Relasi: User – Transaksi – Produk

### Diagram Relasi Sederhana (Deskripsi)
- **User** (1) --- (N) **Transaksi**
- **Transaksi** (N) --- (N) **Produk** (melalui tabel detail_transaksi)
- **User** (1) --- (N) **Cart**
- **Cart** (N) --- (N) **Produk**

### Studi Kasus Mini
Misal: User A membeli 2 produk berbeda dalam 1 transaksi. Sistem harus bisa mencatat siapa user-nya, produk apa saja yang dibeli, dan berapa jumlahnya.

---

## 4. Membaca & Membuat ERD
- Identifikasi entitas utama dari kebutuhan sistem
- Tentukan atribut penting tiap entitas
- Tentukan relasi antar entitas (one-to-one, one-to-many, many-to-many)
- Visualisasikan dengan tools seperti dbdiagram.io, draw.io, atau kertas

### Notasi Umum ERD
- **Kotak**: Entitas
- **Oval**: Atribut
- **Garis**: Relasi
- **Tanda 1/N**: Kardinalitas (jumlah hubungan)

---

## 📌 Tugas Mandiri Hari Ini (8 Jam)
- Rancang ERD untuk sistem e-commerce sederhana (minimal: User, Produk, Transaksi, Cart)
- Tentukan atribut utama tiap entitas
- Visualisasikan ERD menggunakan dbdiagram.io, draw.io, atau kertas
- Pastikan relasi antar entitas sudah benar (one-to-many, many-to-many)
- (Opsional) Tambahkan entitas/atribut lain sesuai kebutuhan (misal: kategori produk, alamat pengiriman)

---

## 💡 Tips untuk Santri
- Mulai dari kebutuhan aplikasi, lalu identifikasi entitas utama
- Jangan terlalu banyak entitas/atribut di awal, fokus pada yang inti dulu
- Pastikan setiap relasi logis dan tidak membingungkan
- Diskusikan ERD dengan mentor/teman sebelum lanjut ke implementasi database
- Simpan hasil ERD sebagai dokumentasi proyek