# 📘 Hari 2 - Dasar Algoritma & Pseudocode

## 🎯 Tujuan Pembelajaran
- Memahami konsep dasar algoritma dan pentingnya dalam pemrograman serta kehidupan sehari-hari
- Menjelaskan alur logika sederhana: input, proses, output, dan mengenali pola berpikir algoritmik
- Mengenal dan menulis pseudocode dasar dengan berbagai variasi kasus
- Membaca, memahami, dan mengoreksi pseudocode orang lain
- Melatih kemampuan logika dengan soal bertingkat (if-else, loop, nested logic)

---

## 1. Apa itu Algoritma?
Algoritma adalah urutan langkah logis yang disusun untuk menyelesaikan suatu masalah. Dalam dunia pemrograman, algoritma menjadi fondasi utama sebelum menulis kode.

### Mengapa Algoritma Penting?
- Membantu memecah masalah besar menjadi langkah-langkah kecil yang terstruktur
- Membiasakan berpikir sistematis dan efisien
- Mengurangi trial-error saat coding
- Digunakan di semua bidang: teknologi, bisnis, bahkan kehidupan sehari-hari (misal: resep masakan, prosedur administrasi)

### Analogi:
Bayangkan algoritma seperti resep masakan:
- Ada bahan (input)
- Ada langkah-langkah memasak (proses)
- Ada hasil akhir (output)

### Contoh Sederhana:
- **Input:** Dua angka
- **Proses:** Menjumlahkan kedua angka
- **Output:** Hasil penjumlahan

### Studi Kasus Algoritma Sehari-hari
- **Membuat teh:**
    1. Masukkan teh ke gelas
    2. Tambahkan air panas
    3. Aduk
    4. Tambahkan gula jika ingin manis
    5. Selesai
- **Berangkat sekolah:**
    1. Bangun tidur
    2. Mandi
    3. Sarapan
    4. Berangkat

---

## 2. Alur Logika: Input-Proses-Output

| Tahap   | Penjelasan                        | Contoh pada Login           |
|---------|-----------------------------------|-----------------------------|
| Input   | Data yang dimasukkan user         | Email & Password            |
| Proses  | Logika/aturan yang dijalankan     | Validasi data ke database   |
| Output  | Hasil akhir ke user               | Sukses: dashboard, Gagal: error |

### Studi Kasus Mini
Misal kamu ingin membuat fitur cek usia:
- **Input:** Umur
- **Proses:** Jika umur >= 17, boleh daftar; jika tidak, tolak
- **Output:** Pesan "Boleh daftar" atau "Belum cukup umur"

### Latihan: Identifikasi IPO
1. Membeli pulsa di konter
2. Menghitung luas persegi panjang
3. Mengisi formulir online
Tuliskan input, proses, dan output untuk masing-masing kasus di atas.

---

## 3. Pseudocode Dasar
Pseudocode adalah cara menuliskan algoritma menggunakan bahasa sehari-hari yang terstruktur, bukan syntax pemrograman tertentu. Tujuannya agar logika mudah dipahami sebelum diubah ke kode asli.

### Aturan Umum Pseudocode:
- Gunakan bahasa yang jelas dan konsisten
- Setiap langkah ditulis berurutan
- Gunakan indentasi untuk blok logika (if, loop)
- Hindari syntax bahasa pemrograman spesifik

### Contoh Pseudocode Penjumlahan
```
Mulai
Input angka1
Input angka2
jumlah = angka1 + angka2
Tampilkan jumlah
Selesai
```

### Contoh Pseudocode Login Sederhana
```
Mulai
Input email
Input password
Jika email dan password sesuai di database
    Tampilkan "Login berhasil"
Jika tidak
    Tampilkan "Login gagal"
Selesai
```

### Contoh Pseudocode dengan Loop
```
Mulai
Set i = 1
Selama i <= 5 lakukan
    Tampilkan i
    i = i + 1
Selesai
```

### Contoh Pseudocode Bersarang (Nested)
```
Mulai
Input nilai
Jika nilai >= 75
    Jika nilai >= 90
        Tampilkan "Nilai A"
    Jika tidak
        Tampilkan "Nilai B"
Jika tidak
    Tampilkan "Nilai C"
Selesai
```

---

## 4. Membaca & Menulis Pseudocode
- Bacalah setiap langkah secara runut, bayangkan prosesnya di kepala
- Coba tulis ulang pseudocode dari soal cerita
- Latihan: Ubah soal logika sehari-hari menjadi pseudocode
- Review pseudocode teman, diskusikan logika dan kemungkinan perbaikan
- Biasakan menulis pseudocode sebelum coding agar logika lebih matang

---

## 5. Latihan Logika Bertingkat
- Buat pseudocode untuk:
    1. Menentukan bilangan ganjil/genap
    2. Menampilkan deret angka 1-10
    3. Mengecek password minimal 8 karakter
    4. Menghitung total belanja dengan diskon jika belanja > 100 ribu
    5. Menampilkan "FizzBuzz" untuk angka 1-20 (jika kelipatan 3: Fizz, kelipatan 5: Buzz, keduanya: FizzBuzz)

---

## 📌 Tugas Mandiri Hari Ini (8 Jam)
- Tulis pseudocode sederhana untuk proses login dan logout (sertakan validasi sederhana)
- Buat flowchart login sederhana (gunakan draw.io, lucidchart, atau kertas)
- Latihan logika: Buat 3 soal if-else dan 2 soal loop (for/while), tulis pseudocode-nya
- (Opsional) Tukar hasil pseudocode dengan teman, lalu review dan diskusikan
- (Opsional) Implementasikan salah satu pseudocode ke kode JavaScript sederhana

---

## 💡 Tips untuk Santri
- Fokus pada logika, bukan syntax bahasa pemrograman
- Jangan takut salah, revisi pseudocode itu wajar
- Diskusikan logika dengan mentor atau teman jika bingung
- Visualisasikan alur dengan diagram agar lebih mudah dipahami
- Latihan rutin menulis pseudocode akan mempercepat pemahaman coding