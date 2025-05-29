# 📆 Hari 5 (Jum'at) – Tugas & Presentasi

## 🎯 Tujuan Pembelajaran
- Mengimplementasikan aplikasi backend lengkap dengan fitur autentikasi JWT dan otorisasi middleware.
- Menyusun struktur project menggunakan pola MVC yang rapi dan modular.
- Mempresentasikan hasil kerja, menjelaskan arsitektur, dan mendapatkan feedback.

---

## 📝 Tugas Mingguan

### 1. Buat Backend Authentication & Authorization API
- Kembangkan project backend dari minggu sebelumnya.
- Implementasikan alur register dan login menggunakan JWT dan bcrypt untuk hashing password.
- Buat middleware otorisasi untuk melindungi endpoint-endpoint tertentu yang hanya bisa diakses oleh pengguna terautentikasi.
- Pastikan data pengguna (termasuk password yang di-hash) tersimpan di database PostgreSQL.

### 2. Terapkan Struktur Folder MVC
- Refactor project backend Anda untuk mengikuti struktur folder MVC yang telah dipelajari di Hari 4.
- Pisahkan kode ke dalam layer `models/`, `controllers/`, `routes/`, dan `middlewares/`.
- Pastikan file utama (`app.js` atau `index.js`) hanya berisi setup dasar dan penggunaan router.

### 3. Dokumentasi Endpoint dan Proses Autentikasi
- Buat dokumentasi sederhana (misalnya, di file README.md) yang menjelaskan:
  - Endpoint yang tersedia (path, method, deskripsi).
  - Contoh request dan response untuk register, login, dan endpoint yang dilindungi.
  - Penjelasan singkat tentang bagaimana autentikasi JWT dan otorisasi middleware bekerja di aplikasi Anda.

### 4. Persiapan Presentasi
- Siapkan materi presentasi (slide atau penjelasan lisan) yang mencakup:
  - Gambaran umum aplikasi dan fitur autentikasi/otorisasi yang diimplementasikan.
  - Penjelasan struktur folder MVC yang digunakan.
  - Demo aplikasi menggunakan Postman/Insomnia untuk menunjukkan alur register, login, dan akses ke endpoint yang dilindungi/tidak dilindungi.
  - Tantangan yang dihadapi selama pengerjaan dan bagaimana mengatasinya.

---

## 🎤 Presentasi

### 1. Demo Aplikasi (10-15 Menit)
- Gunakan Postman atau Insomnia untuk mendemonstrasikan alur:
  - Register pengguna baru.
  - Login pengguna yang sudah terdaftar.
  - Mengakses endpoint publik (jika ada).
  - Mengakses endpoint yang dilindungi dengan JWT yang valid.
  - Mengakses endpoint yang dilindungi tanpa JWT atau dengan JWT tidak valid/expired.

### 2. Penjelasan Arsitektur dan Kode (10-15 Menit)
- Jelaskan struktur folder MVC yang Anda terapkan.
- Jelaskan alur request dari client, melalui router, middleware, controller, hingga model dan database, lalu kembali ke client.
- Fokus pada bagaimana JWT dibuat saat login, bagaimana middleware memverifikasi JWT, dan bagaimana bcrypt digunakan untuk password.
- Tunjukkan potongan kode kunci di setiap layer (misalnya, kode hashing di controller auth, kode verifikasi di middleware auth).

### 3. Diskusi dan Feedback (10-15 Menit)
- Buka sesi tanya jawab.
- Jelaskan tantangan yang dihadapi dan solusi yang ditemukan.
- Terima feedback dan saran dari mentor dan rekan-rekan.

---

## 💡 Tips untuk Presentasi
- Latihan demo API agar berjalan lancar.
- Siapkan skenario demo (misalnya, pengguna baru, pengguna lama, akses tanpa auth).
- Jelaskan konsep teknis dengan bahasa yang mudah dipahami.
- Fokus pada "mengapa" Anda memilih pendekatan tertentu (misalnya, mengapa menggunakan bcrypt, mengapa struktur MVC).
- Bersiaplah untuk menjawab pertanyaan teknis.

---

## 📚 Referensi
- [Postman Docs](https://learning.postman.com/docs/getting-started/introduction/)
- [Insomnia Docs](https://docs.insomnia.rest/insomnia/get-started)
- [Express.js Best Practices](https://expressjs.com/en/advanced/best-practice-performance.html)
- [Node.js Project Structure Best Practices](https://www.newline.co/blog/node-js-project-structure)