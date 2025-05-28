# 📘 Hari 3 - Studi Kasus: Login Sistem & Transaksi Sederhana

## 🎯 Tujuan Pembelajaran
- Memahami alur sistem login dan transaksi sederhana dalam aplikasi
- Mampu menganalisis dan memetakan input user, proses validasi, dan respon sistem
- Menulis pseudocode dan flowchart untuk proses login dan transaksi
- Melatih kemampuan berpikir kritis melalui studi kasus nyata

---

## 1. Studi Kasus: Sistem Login

### Deskripsi Kasus
Sebuah aplikasi membutuhkan fitur login agar hanya user terdaftar yang bisa mengakses dashboard. Proses login melibatkan input user, validasi data, dan respon sistem.

### Alur Login (Input-Proses-Output)
- **Input:** Email & Password dari user
- **Proses:**
    1. Sistem menerima input
    2. Validasi format email & password tidak kosong
    3. Cek kecocokan data di database
- **Output:**
    - Jika valid: tampilkan dashboard
    - Jika tidak: tampilkan pesan error

### Contoh Pseudocode Login
```
Mulai
Input email
Input password
Jika email kosong atau password kosong
    Tampilkan "Email dan password wajib diisi"
Jika tidak
    Jika email dan password sesuai di database
        Tampilkan "Login berhasil, tampilkan dashboard"
    Jika tidak
        Tampilkan "Login gagal, cek kembali data"
Selesai
```

### Flowchart Login (Deskripsi)
1. Mulai
2. Input email & password
3. Cek input kosong?
    - Ya: tampilkan error
    - Tidak: lanjut cek database
4. Cek data cocok?
    - Ya: tampilkan dashboard
    - Tidak: tampilkan error
5. Selesai

---

## 2. Studi Kasus: Transaksi Sederhana (Pembelian Produk)

### Deskripsi Kasus
User yang sudah login dapat melakukan pembelian produk. Proses transaksi melibatkan input data produk, validasi stok, dan respon sistem.

### Alur Transaksi (Input-Proses-Output)
- **Input:** Pilihan produk & jumlah beli
- **Proses:**
    1. Sistem menerima input
    2. Validasi produk tersedia & stok cukup
    3. Hitung total harga
    4. Update stok
- **Output:**
    - Jika sukses: tampilkan struk pembelian
    - Jika gagal: tampilkan pesan error (misal stok kurang)

### Contoh Pseudocode Transaksi
```
Mulai
Input nama_produk
Input jumlah_beli
Jika nama_produk tidak ditemukan di database
    Tampilkan "Produk tidak tersedia"
Jika tidak
    Jika stok < jumlah_beli
        Tampilkan "Stok tidak cukup"
    Jika tidak
        total = harga_produk * jumlah_beli
        Kurangi stok produk
        Tampilkan "Pembelian sukses, total: " + total
Selesai
```

### Flowchart Transaksi (Deskripsi)
1. Mulai
2. Input produk & jumlah
3. Cek produk tersedia?
    - Tidak: tampilkan error
    - Ya: cek stok cukup?
        - Tidak: tampilkan error
        - Ya: proses transaksi, update stok, tampilkan struk
4. Selesai

---

## 3. Pembahasan Input User, Validasi, dan Respon Sistem

- **Input User:**
    - Data yang dimasukkan user harus dicek validitasnya (format, tidak kosong, dll)
    - Hindari menerima data mentah tanpa validasi
- **Validasi:**
    - Cek format data (misal email valid, angka positif)
    - Cek data di database (apakah user/produk ada, stok cukup)
- **Respon Sistem:**
    - Berikan feedback yang jelas (sukses/gagal, alasan error)
    - Jangan tampilkan data sensitif ke user

### Studi Kasus Mini: Validasi Transaksi
- User ingin beli 3 produk A, stok hanya 2 → sistem harus menolak dan beri pesan jelas
- User input nama produk salah → sistem beri info produk tidak ditemukan

---

## 📌 Tugas Mandiri Hari Ini (8 Jam)
- Implementasikan flowchart login dan transaksi di atas ke dalam bentuk pseudocode (boleh dikembangkan lebih detail)
- Uji pseudocode ke teman/mentor: diskusikan apakah logikanya sudah benar dan mudah dipahami
- Buat diagram flow transaksi (misal pembelian produk) menggunakan draw.io/lucidchart/kertas
- (Opsional) Tambahkan validasi tambahan (misal: password minimal 8 karakter, jumlah beli tidak boleh negatif)

---

## 💡 Tips untuk Santri
- Selalu mulai dari pemetaan alur (flowchart) sebelum menulis pseudocode
- Validasi input user adalah kunci aplikasi yang aman dan nyaman
- Diskusikan logika dengan teman/mentor untuk menemukan celah atau perbaikan
- Visualisasikan proses dengan diagram agar lebih mudah dipahami
- Jangan takut merevisi pseudocode jika menemukan logika yang kurang tepat