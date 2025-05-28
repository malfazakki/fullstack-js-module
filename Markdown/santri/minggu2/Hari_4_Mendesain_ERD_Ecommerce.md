# 📆 Hari 4 (Kamis) – Mendesain ERD E-Commerce

## 🎯 Tujuan Pembelajaran
- Memahami konsep Entity Relationship Diagram (ERD) dan komponennya
- Mampu mendesain ERD untuk sistem e-commerce sederhana
- Mengenal tools visualisasi ERD (dbdiagram.io, draw.io)

---

## 1. Apa itu ERD?
ERD (Entity Relationship Diagram) adalah diagram yang menggambarkan struktur data dan hubungan antar entitas dalam sistem. ERD membantu developer memahami bagaimana data saling terhubung sebelum membuat database.

### Analogi:
Bayangkan ERD seperti denah toko:
- **Entitas** = Ruangan (misal: kasir, gudang, etalase)
- **Atribut** = Properti ruangan (misal: luas, fungsi)
- **Relasi** = Pintu/penghubung antar ruangan

---

## 2. Komponen ERD
- **Entitas:** Objek utama (User, Produk, Cart, Order, Payment)
- **Atribut:** Detail data tiap entitas (nama, harga, stok, dsb)
- **Relasi:** Hubungan antar entitas (one-to-many, many-to-many)

### Contoh Entitas & Atribut
| Entitas  | Atribut Utama                |
|----------|------------------------------|
| User     | id, nama, email, password    |
| Produk   | id, nama, harga, stok        |
| Cart     | id, user_id, produk_id, qty  |
| Order    | id, user_id, tanggal, total  |
| Payment  | id, order_id, metode, status |

---

## 3. Studi Kasus: ERD E-Commerce
### a. Identifikasi Entitas
- User, Produk, Cart, Order, Payment

### b. Tentukan Relasi
- User (1) – (N) Order
- Order (1) – (N) Payment
- User (1) – (N) Cart
- Cart (N) – (N) Produk (melalui tabel Cart)
- Order (N) – (N) Produk (melalui tabel Order_Items)

### c. Visualisasi ERD
Gunakan tools seperti dbdiagram.io atau draw.io untuk menggambar ERD berdasarkan entitas dan relasi di atas.

---

## 4. Praktik Mandiri (8 Jam)
- Mendesain ERD untuk sistem e-commerce (minimal: User, Produk, Cart, Order, Payment)
- Visualisasikan ERD menggunakan dbdiagram.io atau draw.io
- Bahas relasi one-to-many dan many-to-many
- Review desain teman (peer review) dan diskusikan logika relasi

---

## 💡 Tips untuk Pemula
- Mulai dari kebutuhan aplikasi, lalu identifikasi entitas utama
- Jangan terlalu banyak entitas/atribut di awal, fokus pada yang inti dulu
- Pastikan setiap relasi logis dan tidak membingungkan
- Simpan hasil ERD sebagai dokumentasi proyek