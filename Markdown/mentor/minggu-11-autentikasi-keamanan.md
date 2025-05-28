# Rancangan Pembelajaran Mentor - Minggu 11: Autentikasi & Keamanan

Berikut rencana pembelajaran untuk Minggu 11 yang berfokus pada Autentikasi & Keamanan dengan intensitas yang lebih menantang, membangun di atas dasar yang telah dipelajari di minggu sebelumnya.

## Senin
### Materi (2 jam):
* Pengenalan autentikasi
* JWT (JSON Web Token)
* Login flow

### Belajar Mandiri (8 jam):
* **Latihan (3 jam):**
  * Implementasikan autentikasi JWT untuk login sederhana:
    * Buat endpoint /login
    * Generate token
    * Verifikasi token
  * Uji endpoint dengan Postman
* **Proyek Kecil (4 jam):**
  * Tambahkan endpoint autentikasi ke portofolio:
    * Implementasi /api/v1/login untuk user
    * Integrasi JWT untuk autentikasi
    * Dokumentasikan API dengan Postman
  * Commit ke branch baru di Git
* **Review (1 jam):**
  * Uji endpoint login dengan Postman
  * Periksa token JWT
  * Validasi log commit

### Tugas Harian:
* Submit kode JWT
* Submit portofolio dengan endpoint login
* Submit log branch

## Selasa
### Materi (2 jam):
* Otorisasi
* Role-based access control (admin, user)

### Belajar Mandiri (8 jam):
* **Latihan (3 jam):**
  * Buat middleware untuk otorisasi berdasarkan role:
    * Implementasi middleware role-based
    * Terapkan otorisasi untuk admin
    * Terapkan otorisasi untuk user
* **Proyek Kecil (4 jam):**
  * Terapkan otorisasi ke portofolio:
    * Endpoint /api/v1/projects hanya untuk admin
    * Buat flowchart untuk alur autentikasi/otorisasi
    * Dokumentasikan role-based access
  * Commit ke Git
* **Review (1 jam):**
  * Uji otorisasi dengan Postman
  * Validasi flowchart
  * Periksa log commit

### Tugas Harian:
* Submit kode middleware otorisasi
* Submit flowchart
* Submit portofolio dengan fitur role-based

## Rabu
### Materi (2 jam):
* Keamanan API:
  * CORS
  * Rate limiting
  * Input sanitization

### Belajar Mandiri (8 jam):
* **Latihan (3 jam):**
  * Terapkan keamanan API:
    * Implementasi CORS untuk 2 endpoint
    * Setup rate limiting
    * Sanitasi input untuk mencegah injeksi
* **Proyek Kecil (4 jam):**
  * Tambahkan keamanan ke API portofolio:
    * CORS untuk /api/v1/projects
    * Rate limiting untuk endpoint sensitif
    * Input validation dan sanitization
  * Commit ke branch baru
* **Review (1 jam):**
  * Uji keamanan dengan Postman
  * Validasi CORS dan rate limiting
  * Periksa log commit

### Tugas Harian:
* Submit kode keamanan
* Submit portofolio dengan fitur keamanan
* Submit log branch

## Kamis
### Materi (2 jam):
* Flowchart sistem autentikasi
* Keamanan database (prepared statements)

### Belajar Mandiri (8 jam):
* **Latihan (3 jam):**
  * Buat flowchart sistem autentikasi lengkap
  * Implementasi prepared statements:
    * Query login yang aman
    * Validasi input database
* **Proyek Kecil (4 jam):**
  * Integrasikan autentikasi aman ke portofolio:
    * Login dengan prepared statements
    * Validasi dan sanitasi input
    * Dokumentasi keamanan
  * Push ke GitHub dengan pull request
* **Review (1 jam):**
  * Uji query aman di DBMS
  * Validasi flowchart
  * Periksa pull request

### Tugas Harian:
* Submit flowchart
* Submit kode prepared statements
* Submit link pull request
* Submit portofolio

## Jumat (Ujian):

* **Ujian Praktik (5 jam):**
  * Buat API dengan:
    * Autentikasi JWT
    * Role-based access (admin/user)
    * Keamanan (CORS, rate limiting)
    * Database integration dengan prepared statements
  * Kelola kode dengan Git:
    * Buat branch
    * 5 commit terstruktur
    * Push ke GitHub
    * Buat pull request
  * Sertakan flowchart alur autentikasi
* **Persiapan Presentasi (3 jam):**
  * Validasi kode
  * Validasi flowchart
  * Validasi repositori
  * Siapkan slide untuk demo dan penjelasan
* **Sabtu:** Presentasi hasil ujian

## Tugas Mingguan:
* Kembangkan portofolio dengan sistem autentikasi lengkap:
  * Login dengan JWT
  * Role-based access control
  * Keamanan API (CORS, rate limiting)
  * Integrasi database aman
* Kelola dengan Git:
  * Branch
  * Merge
  * Pull request
* Unggah ke GitHub dengan README yang menjelaskan:
  * Sistem autentikasi
  * Keamanan API
  * Cara instalasi dan penggunaan

## Catatan:

* **Koneksi dengan Minggu Sebelumnya:** Portofolio diperluas dengan autentikasi dan keamanan, mengintegrasikan API Express.js dan database dari minggu sebelumnya, dikelola dengan Git.
* **Intensitas Lebih Berat:** Latihan mencakup skenario kompleks (JWT, role-based middleware, prepared statements), proyek kecil mengintegrasikan keamanan ke portofolio, dan pull request untuk kolaborasi.
* **Flowchart:** Digunakan untuk memvisualisasikan alur autentikasi dan otorisasi.
* **Git:** Menggunakan branch, commit terstruktur, dan pull request untuk praktik profesional.
* **Keamanan:** Fokus pada implementasi best practices keamanan API dan database untuk memastikan aplikasi yang aman dan handal.