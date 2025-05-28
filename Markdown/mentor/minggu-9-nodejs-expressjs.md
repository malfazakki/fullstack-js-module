# Rancangan Pembelajaran Mentor - Minggu 9: Node.js & Express.js Dasar

Berikut rencana pembelajaran untuk Minggu 9 yang berfokus pada Node.js & Express.js Dasar dengan intensitas yang lebih menantang, membangun di atas dasar yang telah dipelajari di minggu sebelumnya.

## Senin
### Materi (2 jam):
* Pengenalan Node.js
* Instalasi Node.js
* Module (built-in dan npm)

### Belajar Mandiri (8 jam):
* **Latihan (3 jam):**
  * Buat 3 script Node.js sederhana:
    * File reader menggunakan fs module
    * HTTP server dasar
    * Implementasi module eksternal (moment)
* **Proyek Kecil (4 jam):**
  * Buat server Node.js sederhana untuk portofolio:
    * API yang mengembalikan data proyek statis
    * Implementasi routing dasar
  * Commit ke branch baru di Git
* **Review (1 jam):**
  * Uji server di localhost
  * Periksa kode
  * Validasi log commit

### Tugas Harian:
* Submit 3 script Node.js
* Submit portofolio dengan server
* Submit log branch

## Selasa
### Materi (2 jam):
* Express.js dasar
* Routing
* HTTP methods (GET, POST)

### Belajar Mandiri (8 jam):
* **Latihan (3 jam):**
  * Buat 4 route Express.js:
    * GET untuk daftar proyek
    * GET untuk detail proyek
    * POST untuk menambah proyek
    * DELETE untuk menghapus proyek
  * Pengujian dengan Postman
* **Proyek Kecil (4 jam):**
  * Tambahkan API dengan 3 route ke portofolio:
    * GET /projects
    * POST /projects
    * GET /projects/:id
  * Buat flowchart untuk alur API
  * Commit ke Git
* **Review (1 jam):**
  * Uji route dengan Postman
  * Validasi flowchart
  * Periksa log commit

### Tugas Harian:
* Submit kode route
* Submit flowchart
* Submit portofolio dengan API

## Rabu
### Materi (2 jam):
* Middleware di Express.js
* Parsing body (JSON, urlencoded)

### Belajar Mandiri (8 jam):
* **Latihan (3 jam):**
  * Buat 2 middleware:
    * Logging waktu request
    * Validasi input sederhana
* **Proyek Kecil (4 jam):**
  * Terapkan middleware ke API portofolio:
    * Logging untuk setiap request ke /projects
    * Validasi input untuk POST /projects
  * Commit ke branch baru
* **Review (1 jam):**
  * Uji middleware di Postman
  * Periksa log
  * Validasi integritas kode

### Tugas Harian:
* Submit kode middleware
* Submit portofolio dengan middleware
* Submit log branch

## Kamis
### Materi (2 jam):
* Flowchart pengembangan aplikasi backend
* Struktur proyek Express

### Belajar Mandiri (8 jam):
* **Latihan (3 jam):**
  * Buat flowchart untuk API manajemen proyek
  * Restrukturisasi kode Express dengan folder terpisah:
    * routes
    * middleware
    * controllers
    * models
* **Proyek Kecil (4 jam):**
  * Perbarui portofolio dengan struktur API modular:
    * Pisahkan routes dan middleware
    * Implementasi controller
    * Integrasi model
  * Push ke GitHub dengan pull request
* **Review (1 jam):**
  * Uji API di Postman
  * Validasi flowchart
  * Periksa pull request

### Tugas Harian:
* Submit flowchart
* Submit kode API modular
* Submit link pull request
* Submit portofolio

## Jumat (Ujian):

* **Ujian Praktik (5 jam):**
  * Buat API sederhana dengan Express.js:
    * Manajemen proyek dengan 4 route:
      * GET /projects
      * POST /projects
      * PUT /projects/:id
      * DELETE /projects/:id
    * Implementasi middleware:
      * Logging
      * Validasi input
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
* Kembangkan portofolio dengan API Express.js:
  * 4 route untuk manajemen proyek
  * Middleware logging
  * Struktur modular
* Kelola dengan Git:
  * Branch
  * Merge
  * Pull request
* Unggah ke GitHub dengan README yang menjelaskan API

## Catatan:

* **Koneksi dengan Minggu Sebelumnya:** Portofolio diperluas dengan backend API menggunakan Express.js, mengintegrasikan data dari database minggu sebelumnya, dikelola dengan Git.
* **Intensitas Lebih Berat:** Latihan mencakup skenario kompleks (middleware kustom, modularisasi), proyek kecil mengintegrasikan API ke portofolio, dan pull request untuk kolaborasi.
* **Flowchart:** Digunakan untuk memvisualisasikan alur API, memperkuat desain backend.
* **Git:** Menggunakan branch, commit terstruktur, dan pull request untuk praktik profesional.