# SiagaKita — Rancangan Website Kesiapsiagaan Bencana

Paket ini adalah **prototipe front-end** berbahasa Indonesia untuk edukasi kesiapsiagaan. Dibuat agar bisa dicoba di GitHub Pages dan disematkan ke Google Sites melalui URL yang sudah dipublikasikan.

## Isi
- `index.html` — halaman utama
- `style.css` — gaya responsif untuk desktop dan ponsel
- `script.js` — interaksi pencarian wilayah demo
- `google-sites-guide.md` — langkah penerapan di Google Sites
- `data-and-safety.md` — batasan data dan daftar integrasi yang perlu dikerjakan

## Jalankan lokal
Buka `index.html` di browser. Koneksi internet dibutuhkan untuk font web dan tautan sumber resmi; konten utama tetap tersedia tanpa feed data langsung.

## Publikasikan dengan GitHub Pages
1. Buat repository baru di akun GitHub Anda, misalnya `siagakita`.
2. Unggah semua file dari folder paket ini ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/(root)`, lalu Save.
5. Tunggu proses publikasi. URL biasanya berbentuk `https://USERNAME.github.io/siagakita/`.
6. Buka URL tersebut dan uji tampilan ponsel serta seluruh tautan.

## Sematkan di Google Sites
Google Sites bukan tempat menjalankan seluruh file HTML/CSS/JS secara langsung. Publikasikan situs di GitHub Pages dahulu, lalu di Google Sites pilih **Insert → Embed → By URL**, masukkan URL GitHub Pages, lalu sesuaikan ukuran embed. Alternatifnya gunakan **Embed code** untuk menyematkan iframe ke URL situs yang sudah dipublikasikan, jika diizinkan oleh pengaturan platform. Pratinjau dan uji di perangkat seluler.

## Peringatan keselamatan
Ini **bukan** sistem peringatan dini dan belum mengambil data real-time. Jangan menafsirkan zona ilustrasi, elevasi kosong, atau nilai demo sebagai informasi aktual. Sebelum dipakai publik, libatkan BPBD/instansi terkait, verifikasi nomor kontak lokal, dan lakukan pengujian aksesibilitas serta keamanan.
