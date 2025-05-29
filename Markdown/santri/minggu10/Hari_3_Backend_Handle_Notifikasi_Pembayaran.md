## 📆 Hari 3 (Rabu) - Backend Meng-handle Notifikasi Pembayaran (Webhook)

### Materi Inti (2 Jam)
- Konsep Webhook/Notification URL: Bagaimana Payment Gateway memberitahu backend tentang status pembayaran.
- Pentingnya validasi signature/hash dari notifikasi untuk keamanan.
- Membuat endpoint API di backend untuk menerima notifikasi (misal: `/api/payments/notification`).
- Memparsing data notifikasi dan memahami status pembayaran (success, pending, failed).

### Praktik Mandiri (8 Jam)
- Di backend, buat endpoint POST `/api/payments/notification`.
- Konfigurasi Notification URL ini di dashboard sandbox Payment Gateway Anda.
- Implementasikan logika untuk memvalidasi notifikasi (cek signature key/hash).
- Parsing data JSON yang diterima dari notifikasi.
- Log status pembayaran yang diterima (misal: `transaction_status`, `fraud_status`).
- Lakukan simulasi pembayaran di sandbox dan pastikan notifikasi diterima oleh endpoint backend Anda.