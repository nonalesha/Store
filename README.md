# Premium Hub PWA

Katalog penjualan langganan aplikasi premium berbentuk Progressive Web App (PWA), dengan pencarian, kategori, pilihan harga harian/bulanan/tahunan, dan pemesanan melalui WhatsApp admin.

## Menjalankan
- Untuk mencoba di komputer, jalankan server lokal dari folder ini, misalnya `python -m http.server 8000`, lalu buka `http://localhost:8000`.
- Untuk install di Android, unggah seluruh isi folder ke hosting HTTPS (misalnya GitHub Pages/Netlify), buka URL-nya lewat Chrome atau Samsung Internet, lalu tekan Install App atau menu browser > Install app / Tambahkan ke layar utama.
- PWA perlu disajikan melalui HTTPS atau localhost agar dapat di-install. Lihat panduan MDN: https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Guides/Making_PWAs_installable

## Mengubah harga
Edit objek `apps` di `app.js`. Nilai harga dalam rupiah (angka tanpa titik), dalam urutan paket `Harian`, `Bulanan`, `Tahunan`.

## Penting
Harga yang ada adalah contoh awal untuk demonstrasi, bukan harga resmi/terverifikasi dari penyedia layanan. Periksa dan ubah sebelum dipublikasikan. Gunakan metode penjualan dan akses langganan yang resmi serta patuhi ketentuan tiap layanan. Ikon tiap aplikasi saat ini berupa monogram berwarna, bukan logo resmi merek.
