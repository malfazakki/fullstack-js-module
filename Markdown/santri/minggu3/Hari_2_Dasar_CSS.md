# 📆 Hari 2 (Selasa) – Dasar CSS

## 🎯 Tujuan Pembelajaran
- Memahami konsep dasar CSS (selector, property, value)
- Menguasai box model dan berbagai jenis display
- Memahami teknik positioning elemen
- Mampu membuat layout dengan Flexbox dan Grid
- Menerapkan styling pada halaman HTML produk

---

## 1. Apa itu CSS?
CSS (Cascading Style Sheets) adalah bahasa yang digunakan untuk mengatur tampilan dan layout halaman web. Jika HTML adalah "kerangka bangunan", maka CSS adalah "cat, dekorasi, dan tata letak ruangan".

### Analogi:
- **Selector** = Alamat ruangan yang ingin dihias (misal: semua pintu, semua jendela)
- **Property** = Jenis dekorasi (warna cat, ukuran, posisi)
- **Value** = Nilai dekorasi (merah, 20px, kanan)

---

## 2. Struktur Dasar CSS
```css
selector {
  property: value;
}
```
Contoh:
```css
h1 {
  color: blue;
  font-size: 32px;
}
```

---

## 3. Box Model
Box model adalah cara browser memandang setiap elemen sebagai kotak yang terdiri dari:
- **Content**: Isi utama (teks/gambar)
- **Padding**: Jarak antara isi dan border
- **Border**: Garis tepi elemen
- **Margin**: Jarak antar elemen

### Visualisasi:
```
+-------------------------+
|       Margin            |
|  +-------------------+  |
|  |     Border        |  |
|  |  +------------+   |  |
|  |  |  Padding   |   |  |
|  |  | +-------+  |   |  |
|  |  | |Content|  |   |  |
|  |  | +-------+  |   |  |
|  |  +------------+   |  |
|  +-------------------+  |
+-------------------------+
```

---

## 4. Display dan Positioning
- **Display**: block, inline, inline-block
- **Position**: static (default), relative, absolute, fixed

### Contoh:
```css
img {
  display: block;
  margin: 0 auto;
}
nav {
  position: fixed;
  top: 0;
  width: 100%;
}
```

---

## 5. Layout dengan Flexbox dan Grid
- **Flexbox**: Untuk layout satu dimensi (baris/kolom)
- **Grid**: Untuk layout dua dimensi (baris dan kolom)

### Contoh Flexbox:
```css
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
```
### Contoh Grid:
```css
.grid-container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 16px;
}
```

---

## 6. Studi Kasus: Styling Halaman Produk
- Terapkan styling pada halaman HTML produk dari Hari 1
- Gunakan Flexbox/Grid untuk layout produk
- Tambahkan warna, padding, margin, dan efek hover pada elemen produk

---

## 7. Praktik Mandiri (8 Jam)
- Styling halaman HTML dari Hari 1 dengan CSS eksternal
- Implementasi layout dengan Flexbox/Grid
- Buat tampilan responsive sederhana (media query)
- Eksplorasi kombinasi selector (class, id, descendant, pseudo-class)
- Simulasi perubahan tampilan dengan hover/focus

---

## 💡 Tips untuk Pemula
- Pisahkan file CSS dari HTML untuk maintainability
- Gunakan developer tools di browser untuk eksperimen styling
- Mulai dari layout sederhana, lalu tingkatkan kompleksitas
- Dokumentasikan class/id yang digunakan
- Referensi: [MDN CSS Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)