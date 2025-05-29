# Rancangan Pembelajaran Mentor - Minggu 10: Express.js Lanjutan & Database Integration

Berikut rencana pembelajaran untuk Minggu 10 yang berfokus pada Express.js Lanjutan & Database Integration dengan intensitas yang lebih menantang, membangun di atas dasar yang telah dipelajari di minggu sebelumnya.

## Senin
### Materi (2 jam):
* RESTful API design
* Status code
* Versioning API

### Belajar Mandiri (8 jam):
* **Latihan (3 jam):**
  * Buat 4 endpoint RESTful untuk entitas tasks:
    * GET /tasks (daftar semua tasks)
    * POST /tasks (buat task baru)
    * PUT /tasks/:id (update task)
    * DELETE /tasks/:id (hapus task)
  * Implementasi status code yang tepat:
    * 200 OK untuk GET sukses
    * 201 Created untuk POST sukses
    * 204 No Content untuk DELETE sukses
    * 400 Bad Request untuk input tidak valid
    * 404 Not Found untuk data tidak ditemukan
* **Proyek Kecil (4 jam):**
  * Tambahkan API RESTful ke portofolio:
    * Implementasi endpoint /api/v1/projects
    * Terapkan status code yang sesuai
    * Dokumentasikan API dengan Postman
  * Commit ke branch baru di Git
* **Review (1 jam):**
  * Uji endpoint dengan Postman
  * Periksa status code
  * Validasi log commit

### Tugas Harian:
* Submit kode 4 endpoint
* Submit portofolio dengan API RESTful
* Submit log branch

## Selasa
### Materi (2 jam):
* Integrasi database dengan Express.js
* ORM dasar (Sequelize)
* Konfigurasi koneksi database

### Belajar Mandiri (8 jam):
* **Latihan (3 jam):**
  * Hubungkan Express.js dengan database SQL:
    * Setup Sequelize dengan MySQL/PostgreSQL
    * Konfigurasi environment variables
  * Buat model untuk 2 tabel:
    * Model Project (id, title, description, created_at)
    * Model Task (id, project_id, name, status, due_date)
* **Proyek Kecil (4 jam):**
  * Integrasikan database ke portofolio:
    * Setup koneksi database
    * Migrasi skema tabel
    * Tambahkan endpoint untuk menyimpan proyek
  * Buat flowchart untuk alur integrasi
  * Commit ke Git
* **Review (1 jam):**
  * Uji koneksi database
  * Validasi flowchart
  * Periksa log commit

### Tugas Harian:
* Submit kode model Sequelize
* Submit flowchart
* Submit portofolio dengan endpoint database

## Rabu
### Materi (2 jam):
* CRUD dengan Express.js dan database
* Query optimasi
* Relasi antar tabel

### Belajar Mandiri (8 jam):
* **Latihan (3 jam):**
  * Implementasi CRUD untuk Project dan Task:
    * Create: Validasi input, relasi tabel
    * Read: Eager loading, pagination
    * Update: Partial update, validasi
    * Delete: Soft delete, cascade
* **Proyek Kecil (4 jam):**
  * Perbarui portofolio dengan CRUD lengkap:
    * Endpoint untuk manajemen proyek
    * Implementasi relasi dengan tasks
    * Optimasi query untuk performa
  * Commit ke branch baru
* **Review (1 jam):**
  * Uji CRUD dengan Postman
  * Periksa performa query
  * Validasi log commit

### Tugas Harian:
* Submit kode CRUD
* Submit portofolio dengan fitur CRUD
* Submit log branch

## Kamis
### Materi (2 jam):
* Flowchart aplikasi backend dengan database
* Error handling API
* Best practices API security

### Belajar Mandiri (8 jam):
* **Latihan (3 jam):**
  * Buat flowchart untuk aplikasi CRUD
  * Tambahkan error handling untuk endpoint:
    * Validasi input dengan Joi/Express-validator
    * Custom error middleware
    * Logging error dengan Winston
* **Proyek Kecil (4 jam):**
  * Tambahkan error handling ke API portofolio:
    * Implementasi error middleware
    * Respons 404 untuk proyek tidak ditemukan
    * Validasi input untuk semua endpoint
  * Push ke GitHub dengan pull request
* **Review (1 jam):**
  * Uji error handling di Postman
  * Validasi flowchart
  * Periksa pull request

### Tugas Harian:
* Submit flowchart
* Submit kode error handling
* Submit link pull request
* Submit portofolio

## Jumat (Ujian):

* **Ujian Praktik (5 jam):**
  * Buat API RESTful untuk manajemen proyek:
    * Implementasi CRUD lengkap
    * Integrasi Sequelize dengan database
    * Error handling komprehensif
    * Dokumentasi API
  * Kelola kode dengan Git:
    * Buat branch
    * 5 commit terstruktur
    * Push ke GitHub
    * Buat pull request
  * Sertakan flowchart alur API
* **Persiapan Presentasi (3 jam):**
  * Validasi kode
  * Validasi flowchart
  * Validasi repositori
  * Siapkan slide untuk demo dan penjelasan
* Sabtu: Presentasi hasil ujian

## Tugas Mingguan:
* Kembangkan portofolio dengan API RESTful:
  * CRUD untuk proyek dan tugas
  * Integrasi database dengan Sequelize
  * Error handling komprehensif
* Kelola dengan Git:
  * Branch
  * Merge
  * Pull request
* Unggah ke GitHub dengan README yang menjelaskan:
  * Struktur API
  * Skema database
  * Cara instalasi dan penggunaan

## Catatan:

* **Koneksi dengan Minggu Sebelumnya:** Portofolio diperluas dengan API RESTful yang terintegrasi dengan database, membangun dari Express.js dasar, dikelola dengan Git.
* **Intensitas Lebih Berat:** Latihan mencakup skenario kompleks (RESTful design, ORM, error handling), proyek kecil mengintegrasikan CRUD ke portofolio, dan pull request untuk kolaborasi.
* **Flowchart:** Digunakan untuk memvisualisasikan alur API dan integrasi database.
* **Git:** Menggunakan branch, commit terstruktur, dan pull request untuk praktik profesional.
* **Database:** Fokus pada penggunaan ORM (Sequelize) untuk manajemen database yang efisien dan terstruktur.
* **Error Handling:** Penerapan error handling yang komprehensif untuk meningkatkan reliabilitas API.