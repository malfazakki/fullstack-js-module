# 📆 Hari 2 (Selasa) - Validasi & Error Handling

### Materi Inti (2 Jam)
- Pentingnya validasi input di backend untuk keamanan dan integritas data.
- Menggunakan library validasi (misal: `express-validator` untuk Express.js).
- Strategi error handling yang efektif di backend (middleware error handling).
- Mengirim pesan error yang informatif namun tidak membocorkan detail sensitif ke frontend.

### Praktik Mandiri (8 Jam)
- Identifikasi endpoint-endpoint di backend yang memerlukan validasi input (misal: register, login, tambah produk).
- Implementasikan validasi menggunakan library pilihan Anda (misal: cek format email, panjang password, tipe data).
- Buat middleware error handling global di Express.js untuk menangani error yang tidak tertangkap.
- Uji coba validasi dengan mengirim data yang salah dari Postman dan pastikan pesan error yang sesuai dikembalikan.
- Pastikan error yang terjadi di backend ditangani dengan baik dan tidak menyebabkan aplikasi crash.