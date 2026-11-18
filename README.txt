FORK Tunjungan - Web Pemesanan
================================
Buka index.html di browser (folder 'assets' harus satu folder dengan index.html).

Ubah data:
- Menu & harga : array M di dalam index.html (harga dalam ribuan rupiah, 55 = Rp55.000)
- Foto         : taruh file di assets/ lalu daftarkan di objek IMG (id menu -> assets/xxx.jpg)
- Rekening, e-wallet, QRIS, kode promo, nomor WhatsApp : objek CFG di bagian atas <script>
- Pesanan dikirim ke WhatsApp FORK Tunjungan (0822-4177-6257).

Catatan: tidak ada backend/dashboard admin. Untuk itu perlu server + database.
Untuk online: upload seluruh folder ke hosting statis (Netlify, Vercel, GitHub Pages, dll).
