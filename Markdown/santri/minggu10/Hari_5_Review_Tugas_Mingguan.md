## 📆 Hari 5 (Jum'at) - Review & Tugas Mingguan

### Materi Inti (2 Jam)
- Review menyeluruh alur Payment Gateway dari frontend hingga backend dan update status.
- Membahas potensi masalah dan solusi (misal: idempotency, retry mechanism).
- Persiapan Tugas Mingguan.

### Tugas Mingguan (Waktu Pengerjaan: Sisa Minggu + Akhir Pekan)

**Tema Tugas:** Implementasi Integrasi Payment Gateway di Aplikasi E-commerce.

**Persyaratan Fungsional:**
1.  **Integrasi Payment Gateway:** Implementasikan integrasi dengan Midtrans atau Xendit (mode sandbox).
2.  **Endpoint Transaksi Backend:** Buat endpoint di backend untuk membuat transaksi pembayaran dan berkomunikasi dengan Payment Gateway.
3.  **Frontend Payment Flow:** Di frontend React, implementasikan alur untuk memulai pembayaran setelah checkout, mengarahkan user ke halaman pembayaran Payment Gateway.
4.  **Webhook Notifikasi:** Buat endpoint di backend untuk menerima dan memvalidasi notifikasi status pembayaran dari Payment Gateway.
5.  **Update Status Pesanan:** Berdasarkan notifikasi, update status pesanan di database Anda (misal: dari 'pending' menjadi 'paid').
6.  **Dokumentasi (`README.md`):** Perbarui file `README.md` dengan penjelasan alur Payment Gateway dan cara mengujinya.

**Fitur Opsional (Nilai Tambah):**
-   Implementasi halaman sukses/gagal pembayaran di frontend.
-   Penanganan error yang lebih robust saat komunikasi dengan Payment Gateway.
-   Pencatatan log notifikasi pembayaran untuk debugging.
-   Implementasi fitur refund (membutuhkan API Payment Gateway dan logika backend).

**Output Tugas:**
-   Kode sumber aplikasi React dan backend yang sudah terintegrasi Payment Gateway.
-   File `README.md` yang diperbarui.
-   Push semua perubahan ke repositori GitHub pribadi Anda.

## 🗣️ Sesi Presentasi (Waktu disesuaikan)

Siapkan diri Anda untuk sesi presentasi singkat di awal minggu berikutnya. Fokus presentasi adalah:

-   **Demo:** Tunjukkan alur checkout hingga proses pembayaran (simulasi di sandbox) dan bagaimana status pesanan berubah.
-   **Penjelasan Implementasi:** Jelaskan bagaimana frontend dan backend berkomunikasi dengan Payment Gateway, serta bagaimana notifikasi ditangani.
-   **Tantangan & Solusi:** Ceritakan tantangan yang Anda hadapi saat mengerjakan tugas dan bagaimana Anda menyelesaikannya.