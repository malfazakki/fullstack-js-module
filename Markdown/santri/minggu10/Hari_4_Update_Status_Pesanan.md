## 📆 Hari 4 (Kamis) - Update Status Pesanan

### Materi Inti (2 Jam)
- Pentingnya mengupdate status pesanan di database setelah pembayaran berhasil.
- Logika untuk menangani berbagai status pembayaran (pending, success, expire, cancel).
- Menggunakan ID transaksi dari Payment Gateway untuk mencocokkan dengan pesanan di database Anda.
- Penanganan kasus edge: notifikasi duplikat, notifikasi yang terlambat.

### Praktik Mandiri (8 Jam)
- Di database Anda, tambahkan kolom `payment_status` (misal: 'pending', 'paid', 'failed', 'expired') dan `payment_gateway_transaction_id` di tabel `orders` atau `transactions`.
- Di endpoint notifikasi backend (`/api/payments/notification`), setelah validasi, update status pesanan di database Anda berdasarkan `transaction_status` dari notifikasi.
- Pastikan untuk mencocokkan pesanan menggunakan `order_id` atau `transaction_id` yang Anda kirimkan ke Payment Gateway.
- Implementasikan logika untuk mengupdate stok produk jika pembayaran berhasil (opsional).
- Uji coba berbagai skenario pembayaran (sukses, pending, gagal) di sandbox dan verifikasi status pesanan di database Anda.