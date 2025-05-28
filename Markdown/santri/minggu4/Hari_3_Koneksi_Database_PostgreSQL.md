# 📆 Hari 3 (Rabu) – Koneksi Database PostgreSQL (pg/Prisma)

## 🎯 Tujuan Pembelajaran
- Memahami instalasi dan setup PostgreSQL (lokal/remote)
- Menggunakan library `pg` atau Prisma untuk koneksi database
- Membaca dan menulis data produk ke PostgreSQL dari Express.js

---

## 🧠 Materi Inti (2 Jam)

### 1. Instalasi PostgreSQL Lokal/Remote
- Download dan install PostgreSQL: https://www.postgresql.org/download/
- Alternatif: gunakan layanan cloud (Supabase, Railway, ElephantSQL)
- Buat database baru, misal: `toko_online`

### 2. Instalasi dan Setup Library `pg` atau Prisma
- Pilihan 1: Native driver `pg`
  ```bash
  npm install pg
  ```
- Pilihan 2: ORM Prisma
  ```bash
  npm install prisma @prisma/client
  npx prisma init
  ```
- Konfigurasi koneksi di `.env`:
  ```env
  DATABASE_URL="postgresql://user:password@localhost:5432/toko_online"
  ```

### 3. Membuat Koneksi ke Database
- Contoh koneksi dengan `pg`:
  ```js
  const { Pool } = require('pg');
  const pool = new Pool({ connectionString: process.env.DATABASE_URL });
  module.exports = pool;
  ```
- Contoh koneksi dengan Prisma:
  ```js
  const { PrismaClient } = require('@prisma/client');
  const prisma = new PrismaClient();
  module.exports = prisma;
  ```

### 4. Studi Kasus: Membaca & Menulis Data Produk
- Buat tabel `products`:
  ```sql
  CREATE TABLE products (
    id SERIAL PRIMARY KEY,
    name VARCHAR(100),
    price INTEGER
  );
  ```
- Contoh query dengan `pg`:
  ```js
  // Ambil semua produk
  const result = await pool.query('SELECT * FROM products');
  // Tambah produk
  await pool.query('INSERT INTO products (name, price) VALUES ($1, $2)', [name, price]);
  ```
- Contoh query dengan Prisma:
  ```js
  // Ambil semua produk
  const products = await prisma.product.findMany();
  // Tambah produk
  await prisma.product.create({ data: { name, price } });
  ```

---

## 📝 Praktik Mandiri (8 Jam)
1. Setup database dan tabel `products` di PostgreSQL
2. Implementasi koneksi database di project Express (pilih pg/prisma)
3. Refactor controller agar CRUD products tersimpan di database, bukan array dummy
4. Dokumentasikan skema database dan query dasar di README atau file terpisah

---

## 💡 Tips untuk Pemula
- Pastikan environment variable `DATABASE_URL` sudah benar
- Gunakan tool GUI seperti DBeaver, TablePlus, atau pgAdmin untuk cek data
- Prisma cocok untuk yang ingin auto-generate model dan migrasi
- `pg` cocok untuk yang ingin query SQL manual
- Selalu handle error koneksi database

---

## 📚 Referensi
- [PostgreSQL Download](https://www.postgresql.org/download/)
- [pg Docs](https://node-postgres.com/)
- [Prisma Docs](https://www.prisma.io/docs/)
- [Prisma vs pg: Perbandingan](https://prisma.io/docs/concepts/database-connectors/postgresql)