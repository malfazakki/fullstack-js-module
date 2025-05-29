# 📆 Hari 4 (Kamis) - Deploy Frontend (Vercel/Netlify) & CORS

### Materi Inti (2 Jam)
- Konsep Static Site Hosting untuk deployment frontend.
- Pengenalan Vercel/Netlify: Fitur, kelebihan, dan cara kerjanya.
- Persiapan kode frontend untuk deployment (misal: konfigurasi API_URL).
- Mengatasi masalah CORS (Cross-Origin Resource Sharing) antara frontend dan backend.

### Praktik Mandiri (8 Jam)
- Buat akun di Vercel atau Netlify.
- Siapkan repository GitHub frontend Anda.
- Konfigurasi environment variable di frontend untuk `REACT_APP_API_URL` yang menunjuk ke URL backend yang sudah di-deploy.
- Ikuti panduan deployment Vercel/Netlify untuk menghubungkan repository Anda dan deploy aplikasi frontend.
- Jika terjadi masalah CORS, implementasikan middleware CORS di backend Anda (misal: `cors` package di Express.js) dan konfigurasikan `origin` yang sesuai.
- Setelah deploy, uji coba aplikasi frontend yang sudah di-deploy di browser dan pastikan semua fitur berfungsi dengan baik.