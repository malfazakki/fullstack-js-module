# 📆 Hari 1 (Senin) – Dasar HTML

## 🎯 Tujuan Pembelajaran
- Memahami struktur dasar HTML (tag, atribut, elemen)
- Mengenal semantic tags (header, main, footer, nav, section, article)
- Mampu membuat form, list, dan table sederhana
- Mampu membangun kerangka halaman produk dengan HTML

---

## 1. Apa itu HTML?
HTML (HyperText Markup Language) adalah fondasi utama dari setiap halaman web. HTML digunakan untuk membangun struktur dan isi halaman, mulai dari judul, paragraf, gambar, hingga form input.

### Analogi:
Bayangkan HTML seperti "kerangka bangunan" sebuah rumah:
- **Tag** = Komponen bangunan (tembok, pintu, jendela)
- **Atribut** = Properti tiap komponen (warna pintu, ukuran jendela)
- **Elemen** = Satu bagian utuh (misal: <input type="text"> adalah satu elemen form)

---

## 2. Struktur Dasar HTML
Setiap file HTML minimal terdiri dari:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Judul Halaman</title>
  </head>
  <body>
    <!-- Konten utama di sini -->
  </body>
</html>
```

- **Tag**: Penanda awal dan akhir elemen, misal <p>...</p>
- **Atribut**: Informasi tambahan pada tag, misal <img src="gambar.jpg" alt="Deskripsi">
- **Elemen**: Gabungan tag pembuka, isi, dan tag penutup

---

## 3. Semantic Tags
Semantic tags membantu browser dan developer memahami struktur halaman secara logis.
- `<header>`: Bagian atas (judul, navigasi)
- `<nav>`: Navigasi menu
- `<main>`: Konten utama
- `<section>`: Bagian/topik khusus
- `<article>`: Konten mandiri (berita, postingan)
- `<footer>`: Bagian bawah (copyright, kontak)

### Contoh Struktur Semantic:
```html
<body>
  <header>
    <h1>Katalog Produk</h1>
    <nav>...</nav>
  </header>
  <main>
    <section>
      <h2>Daftar Produk</h2>
      <!-- List produk -->
    </section>
  </main>
  <footer>
    &copy; 2024 Toko Santri
  </footer>
</body>
```

---

## 4. Membuat Form, List, dan Table
- **Form**: Untuk input data pengguna
  ```html
  <form>
    <input type="text" placeholder="Cari produk...">
    <button type="submit">Cari</button>
  </form>
  ```
- **List**: Menampilkan data berurutan
  ```html
  <ul>
    <li>Produk A</li>
    <li>Produk B</li>
  </ul>
  ```
- **Table**: Menampilkan data tabular
  ```html
  <table>
    <tr><th>Nama</th><th>Harga</th></tr>
    <tr><td>Produk A</td><td>Rp10.000</td></tr>
  </table>
  ```

---

## 5. Studi Kasus: Kerangka Halaman Produk
Buatlah kerangka halaman katalog produk sederhana yang terdiri dari:
- Header dengan judul dan navigasi
- Form pencarian produk
- List atau table produk
- Footer

---

## 6. Praktik Mandiri (8 Jam)
- Buat halaman HTML dengan struktur semantic lengkap (header, main, footer)
- Tambahkan form pencarian produk di bagian header/main
- Buat list dan table produk sederhana di main section
- Eksplorasi penggunaan atribut (class, id, style, dsb) dan nesting elemen
- Dokumentasikan struktur HTML yang dibuat (misal: diagram, catatan, atau komentar di kode)

---

## 💡 Tips untuk Pemula
- Selalu mulai dengan struktur dasar HTML (doctype, html, head, body)
- Gunakan semantic tags untuk memudahkan pengelolaan dan SEO
- Cek hasil di browser secara berkala
- Komentari kode untuk memudahkan revisi
- Referensi: [MDN HTML Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)