# 📆 Hari 1 (Senin) – Pengenalan PostgreSQL & Instalasi

## 🎯 Tujuan Pembelajaran
- Memahami konsep dasar database relasional
- Mengenal PostgreSQL dan alasan pemilihannya
- Mampu menginstall PostgreSQL dan pgAdmin
- Mengenal struktur dasar database: database, tabel, row, column

---

## 1. Apa itu Database Relasional?
Database relasional adalah sistem penyimpanan data yang menggunakan tabel-tabel terhubung satu sama lain melalui relasi. Setiap tabel terdiri dari baris (row) dan kolom (column), mirip seperti spreadsheet Excel, namun dengan kemampuan relasi antar tabel.

### Analogi:
Bayangkan database relasional seperti lemari arsip:
- **Database** = Lemari besar
- **Tabel** = Laci di dalam lemari
- **Row** = Satu berkas dokumen
- **Column** = Informasi detail di tiap berkas (nama, tanggal lahir, dll)

---

## 2. Kenapa Memilih PostgreSQL?
- Open source, gratis, dan sangat stabil
- Mendukung fitur-fitur canggih (relasi, transaksi, indexing, JSON, dsb)
- Banyak digunakan di industri startup dan enterprise
- Komunitas besar dan dokumentasi lengkap

---

## 3. Instalasi PostgreSQL + GUI (pgAdmin)
### a. PostgreSQL
- Download installer PostgreSQL sesuai OS di https://www.postgresql.org/download/
- Ikuti langkah instalasi hingga selesai

### b. pgAdmin
- pgAdmin adalah GUI (Graphical User Interface) untuk mengelola database PostgreSQL secara visual
- Biasanya sudah termasuk dalam paket installer PostgreSQL
- Jika belum, download di https://www.pgadmin.org/download/

---

## 4. Struktur Dasar Database
- **Database:** Kumpulan tabel yang saling berelasi
- **Tabel:** Tempat menyimpan data dengan struktur baris & kolom
- **Row (Record):** Satu data lengkap dalam tabel
- **Column (Field):** Jenis data yang disimpan (misal: nama, email)

### Contoh Tabel `users`:
| id | nama      | email             |
|----|-----------|-------------------|
| 1  | Budi      | budi@email.com    |
| 2  | Siti      | siti@email.com    |

---

## 5. Praktik Mandiri (8 Jam)
- Install PostgreSQL dan pgAdmin di komputer masing-masing
- Buat database baru (misal: latihan_santri)
- Buat tabel sederhana `users` dengan kolom id, nama, email
- Jelajahi fitur-fitur dasar pgAdmin (buat tabel, insert data, lihat data)
- Buat catatan singkat dari dokumentasi PostgreSQL (https://www.postgresql.org/docs/)

---

## 💡 Tips untuk Pemula
- Pastikan PostgreSQL dan pgAdmin berjalan lancar sebelum lanjut ke materi berikutnya
- Jangan ragu bertanya jika menemui error saat instalasi
- Dokumentasikan setiap langkah yang dilakukan untuk referensi ke depan