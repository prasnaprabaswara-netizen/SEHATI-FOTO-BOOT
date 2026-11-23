FRAME PHOTOBOOTH — INSTALASI XAMPP

1. Pastikan XAMPP sudah terpasang.
2. Ekstrak folder bernama photobooth-xampp.
3. Salin folder tersebut ke:
   C:\xampp\htdocs\
   (Lokasi bisa berbeda jika XAMPP dipasang di drive/folder lain.)
4. Buka XAMPP Control Panel.
5. Klik Start pada modul Apache.
   MySQL tidak diperlukan untuk versi frontend ini.
6. Buka browser dan kunjungi:
   http://localhost/photobooth-xampp/

STRUKTUR FOLDER
photobooth-xampp/
  index.html
  css/style.css
  js/script.js
  README-XAMPP.txt

PENGATURAN WHATSAPP
Buka js/script.js, cari baris:
const WHATSAPP_ADMIN = "6281234567890";
Ganti dengan nomor WhatsApp admin Anda, format kode negara tanpa +, spasi, atau strip.
Contoh: 6281234567890

CATATAN
- Website ini bisa dijalankan melalui Apache XAMPP sebagai frontend statis.
- MySQL belum diperlukan dan belum ada backend/database.
- Form booking membuka WhatsApp setelah nomor admin dikonfigurasi.
- Harga, nama brand, dan blok gambar galeri masih contoh dan dapat diganti.
