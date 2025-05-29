# Rancangan Pembelajaran Mentor - Minggu 8: Database & SQL

Berikut rencana pembelajaran untuk Minggu 8 yang berfokus pada Database & SQL dengan intensitas yang lebih menantang, membangun di atas dasar yang telah dipelajari di minggu sebelumnya.

## Senin
### Materi (2 jam):
* Pengenalan database relasional
* Model ERD
* Dasar SQL (CREATE, INSERT)

### Belajar Mandiri (8 jam):
* **Latihan (3 jam):**
  * Buat diagram ERD untuk sistem sederhana:
    * Sistem manajemen proyek (tabel projects dan tasks)
    * Tulis query SQL untuk membuat tabel
    * Tulis query SQL untuk mengisi data
* **Proyek Kecil (4 jam):**
  * Desain skema database untuk portofolio:
    * Tabel untuk daftar proyek
    * Tabel untuk kategori
  * Implementasi dengan SQL
  * Commit ke branch baru di Git
* **Review (1 jam):**
  * Validasi ERD
  * Periksa query SQL
  * Validasi struktur tabel
  * Periksa log commit

### Tugas Harian:
* Submit diagram ERD
* Submit query SQL
* Submit skema database portofolio

## Selasa
### Materi (2 jam):
* SQL dasar (SELECT, WHERE, ORDER BY)
* Query filtering

### Belajar Mandiri (8 jam):
* **Latihan (3 jam):**
  * Tulis 5 query SELECT dengan filter:
    * Ambil proyek berdasarkan status
    * Ambil proyek berdasarkan tanggal
    * Implementasi ORDER BY untuk pengurutan
* **Proyek Kecil (4 jam):**
  * Tambahkan query SELECT ke portofolio:
    * Query untuk menampilkan daftar proyek aktif
    * Buat flowchart untuk alur query
  * Commit ke Git
* **Review (1 jam):**
  * Uji query di DBMS (MySQL)
  * Validasi flowchart
  * Periksa log commit

### Tugas Harian:
* Submit 5 query SELECT
* Submit flowchart
* Submit portofolio dengan data proyek

## Rabu
### Materi (2 jam):
* SQL lanjutan (JOIN, GROUP BY)
* Fungsi agregasi

### Belajar Mandiri (8 jam):
* **Latihan (3 jam):**
  * Tulis 3 query dengan JOIN dan GROUP BY:
    * Gabung tabel projects dan tasks
    * Hitung jumlah tugas per proyek
    * Implementasi fungsi agregasi
* **Proyek Kecil (4 jam):**
  * Tambahkan fitur ke portofolio:
    * Tampilkan data dengan JOIN
    * Implementasi daftar proyek dengan jumlah tugas
  * Commit ke branch baru
* **Review (1 jam):**
  * Uji query JOIN
  * Periksa hasil agregasi
  * Validasi log commit

### Tugas Harian:
* Submit query JOIN
* Submit portofolio dengan fitur data
* Submit log branch

## Kamis
### Materi (2 jam):
* SQL dan flowchart aplikasi berbasis database
* Normalisasi dasar

### Belajar Mandiri (8 jam):
* **Latihan (3 jam):**
  * Normalisasi skema database portofolio ke 3NF
  * Buat flowchart untuk alur CRUD:
    * Create
    * Read
    * Update
    * Delete
* **Proyek Kecil (4 jam):**
  * Implementasi operasi CRUD untuk portofolio:
    * Tambah proyek
    * Edit proyek
    * Hapus proyek
  * Push ke GitHub dengan pull request
* **Review (1 jam):**
  * Uji operasi CRUD di DBMS
  * Validasi flowchart
  * Periksa pull request

### Tugas Harian:
* Submit skema ternormalisasi
* Submit flowchart CRUD
* Submit link pull request
* Submit portofolio dengan fitur CRUD

## Jumat (Ujian):

* **Ujian Praktik (5 jam):**
  * Buat sistem database untuk aplikasi manajemen proyek:
    * Desain ERD
    * Implementasi query CRUD
    * Implementasi query JOIN
  * Kelola kode SQL dengan Git:
    * Buat branch
    * 5 commit terstruktur
    * Push ke GitHub
    * Buat pull request
  * Sertakan flowchart alur aplikasi
* **Persiapan Presentasi (3 jam):**
  * Validasi ERD
  * Validasi query
  * Validasi flowchart
  * Validasi repositori
  * Siapkan slide untuk demo dan penjelasan
* Sabtu: Presentasi hasil ujian

## Tugas Mingguan:
* Kembangkan portofolio dengan sistem database:
  * Tabel proyek
  * Tabel tugas
  * Tabel kategori
* Implementasikan:
  * Operasi CRUD
  * Query JOIN
* Kelola dengan Git:
  * Branch
  * Merge
  * Pull request
* Unggah ke GitHub dengan README yang menjelaskan:
  * Skema database
  * Query yang digunakan

## Catatan:

* **Koneksi dengan Minggu Sebelumnya:** Portofolio diperluas dengan sistem database untuk mendukung data dinamis, menggantikan data statis dari React, dikelola dengan Git.
* **Intensitas Lebih Berat:** Latihan mencakup skenario kompleks (normalisasi, query JOIN, agregasi), proyek kecil mengintegrasikan CRUD ke portofolio, dan pull request untuk kolaborasi.
* **Flowchart:** Digunakan untuk memvisualisasikan alur query dan operasi CRUD, memperkuat desain database.
* **Git:** Menggunakan branch, commit terstruktur, dan pull request untuk praktik profesional.