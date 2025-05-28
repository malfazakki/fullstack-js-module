# 📆 Hari 3 (Rabu) – JavaScript Dasar: Variabel, Tipe Data, Function

## 🎯 Tujuan Pembelajaran
- Memahami tipe data primitif di JavaScript
- Menguasai cara deklarasi variabel (var, let, const)
- Memahami konsep function, parameter, dan return
- Mampu menampilkan data produk menggunakan function

---

## 1. Apa itu JavaScript?
JavaScript adalah bahasa pemrograman utama untuk membuat halaman web menjadi interaktif. Jika HTML adalah "kerangka" dan CSS adalah "dekorasi", maka JavaScript adalah "mesin" yang membuat rumah bisa bergerak dan berinteraksi.

### Analogi:
- **Variabel** = Laci penyimpanan barang
- **Tipe Data** = Jenis barang di laci (angka, tulisan, lampu menyala/mati)
- **Function** = Mesin otomatis (misal: mesin pembuat kopi, cukup tekan tombol)

---

## 2. Tipe Data Primitif
- **String**: Teks, contoh: "Produk A"
- **Number**: Angka, contoh: 10000
- **Boolean**: true/false
- **Null**: Kosong secara sengaja
- **Undefined**: Belum diisi nilai

### Contoh:
```js
let nama = "Produk A";
let harga = 10000;
let tersedia = true;
let kosong = null;
let belumDiisi;
```

---

## 3. Deklarasi Variabel
- **var**: cara lama, scope function
- **let**: cara modern, scope block
- **const**: nilai tetap, scope block

### Contoh:
```js
var nama = "Produk Lama";
let produkBaru = "Produk Baru";
const PI = 3.14;
```

---

## 4. Function (Deklarasi, Parameter, Return)
Function adalah blok kode yang bisa dipanggil berulang kali.

### Contoh Deklarasi:
```js
function tampilkanProduk(nama, harga) {
  return nama + " - Rp" + harga;
}

console.log(tampilkanProduk("Produk A", 10000));
```

- **Parameter**: input ke function
- **Return**: output dari function

---

## 5. Studi Kasus: Menampilkan Data Produk dengan Function
Misal, kita punya array produk:
```js
const produkList = [
  { nama: "Produk A", harga: 10000 },
  { nama: "Produk B", harga: 15000 }
];

function tampilkanSemuaProduk(list) {
  for (let i = 0; i < list.length; i++) {
    console.log(tampilkanProduk(list[i].nama, list[i].harga));
  }
}

tampilkanSemuaProduk(produkList);
```

---

## 6. Praktik Mandiri (8 Jam)
- Buat file JS terpisah dan hubungkan ke HTML
- Deklarasikan variabel produk (array of object)
- Buat function untuk menampilkan produk ke HTML (misal: innerHTML atau document.write)
- Eksplorasi penggunaan parameter dan return value
- Gunakan console.log untuk debugging dan eksplorasi hasil

---

## 💡 Tips untuk Pemula
- Gunakan let/const untuk variabel modern
- Selalu beri nama function/variabel yang jelas
- Cek hasil di browser console secara berkala
- Pisahkan logika ke dalam function modular
- Referensi: [MDN JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)