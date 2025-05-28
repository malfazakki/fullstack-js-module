## 📆 Hari 2 (Selasa) - Integrasi Frontend (React) & Backend untuk Transaksi

### Materi Inti (2 Jam)
- Alur integrasi pembayaran: Frontend meminta token transaksi dari backend, backend berkomunikasi dengan Payment Gateway.
- Membuat endpoint API di backend untuk membuat transaksi pembayaran (misal: `/api/payments/create-transaction`).
- Data yang dibutuhkan untuk membuat transaksi (jumlah, detail produk, info user).
- Mengirim permintaan dari frontend (React) ke backend untuk memulai transaksi.
- Menerima response dari backend (token transaksi/redirect URL) dan mengarahkan user ke halaman pembayaran Payment Gateway.

### Praktik Mandiri (8 Jam)
- Di backend, buat endpoint POST `/api/payments/create-transaction`.
- Endpoint ini akan menerima data keranjang/pesanan dari frontend.
- Gunakan library resmi Midtrans/Xendit (misal: `midtrans-client` atau `xendit-node`) untuk membuat transaksi baru.
- Kirimkan `transaction_details` dan `item_details` ke Payment Gateway.
- Kembalikan `transaction_token` (Midtrans) atau `invoice_url` (Xendit) ke frontend.
- Di frontend React, buat fungsi `handlePayment` yang memanggil endpoint backend ini setelah proses checkout.
- Setelah mendapatkan token/URL, arahkan user ke halaman pembayaran Payment Gateway (misal: `snap.pay(token)` untuk Midtrans atau `window.location.href = invoice_url` untuk Xendit).