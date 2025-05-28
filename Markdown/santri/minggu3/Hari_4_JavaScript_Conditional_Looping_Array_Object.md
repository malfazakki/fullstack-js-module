# 📆 Hari 4 (Kamis) – JavaScript Dasar: Conditional, Looping, Array & Object

## 🎯 Tujuan Pembelajaran
- Memahami konsep conditional (if, else, switch) untuk pengambilan keputusan
- Menguasai teknik looping (for, while, forEach) untuk proses berulang
- Mengenal array & object, serta cara manipulasi dan penggunaan method dasarnya
- Mampu mengimplementasikan filter dan manipulasi data produk secara dinamis

---

## 🧠 Konsep Dasar

### 1. Conditional (if, else, switch)
- **Analogi:** Conditional seperti lampu lalu lintas—keputusan diambil berdasarkan kondisi tertentu.
- **Sintaks:**
  ```js
  if (kondisi) {
    // aksi jika kondisi benar
  } else {
    // aksi jika kondisi salah
  }
  // Switch
  switch (nilai) {
    case 'A':
      // aksi
      break;
    case 'B':
      // aksi
      break;
    default:
      // aksi default
  }
  ```
- **Studi Kasus:** Menentukan kategori produk berdasarkan stok ("tersedia" atau "habis").

### 2. Looping (for, while, forEach)
- **Analogi:** Looping seperti memeriksa satu per satu barang di rak toko.
- **Sintaks:**
  ```js
  // For
  for (let i = 0; i < array.length; i++) {
    // aksi
  }
  // While
  let i = 0;
  while (i < array.length) {
    // aksi
    i++;
  }
  // forEach
  array.forEach(function(item) {
    // aksi
  });
  ```
- **Studi Kasus:** Menampilkan daftar produk ke HTML.

### 3. Array & Object
- **Array:** Kumpulan data berurutan (misal: daftar produk)
  ```js
  const produk = ['Baju', 'Celana', 'Sepatu'];
  produk.push('Topi'); // tambah
  produk.pop(); // hapus terakhir
  produk.filter(...), produk.map(...)
  ```
- **Object:** Data dengan pasangan key-value (misal: detail produk)
  ```js
  const produk = { nama: 'Baju', harga: 100000, kategori: 'Fashion' };
  produk.stok = 10; // tambah properti
  delete produk.harga; // hapus properti
  ```
- **Studi Kasus:** Array of object untuk data produk:
  ```js
  const daftarProduk = [
    { nama: 'Baju', kategori: 'Fashion', harga: 100000 },
    { nama: 'Laptop', kategori: 'Elektronik', harga: 5000000 }
  ];
  ```

### 4. Studi Kasus: Filter & Manipulasi Data Produk
- **Filter produk berdasarkan kategori:**
  ```js
  const produkFashion = daftarProduk.filter(p => p.kategori === 'Fashion');
  ```
- **Tambah produk:**
  ```js
  daftarProduk.push({ nama: 'Jam Tangan', kategori: 'Aksesoris', harga: 250000 });
  ```
- **Hapus produk:**
  ```js
  daftarProduk.splice(index, 1);
  ```

---

## 📝 Praktik Mandiri (8 Jam)
1. Implementasi filter produk berdasarkan kategori (gunakan array filter dan event handling pada select dropdown)
2. Tambahkan fitur tambah/hapus produk secara dinamis (form input + manipulasi array + render ulang ke HTML)
3. Eksplorasi event handling (onclick untuk tombol, onchange untuk input/select)
4. Simulasi validasi form sederhana (misal: nama produk tidak boleh kosong)
5. Refactor kode agar lebih modular (pecah function: renderProduk, tambahProduk, hapusProduk, filterProduk)

---

## 💡 Tips untuk Pemula
- Gunakan `console.log` untuk debugging
- Modularisasi kode: pisahkan logic ke dalam function
- Selalu cek dokumentasi resmi: [MDN JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- Jangan takut bereksperimen dan gagal, belajar dari error!

---

## 📚 Referensi
- [MDN JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- [JavaScript Array Methods](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
- [JavaScript Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)