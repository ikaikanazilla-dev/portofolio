# Portfolio Ika Nazilla

Website statis ini siap dihosting sebagai halaman HTML sederhana.

## Struktur Proyek

- `index.html` — halaman utama portofolio
- `image/` — folder berisi gambar yang digunakan pada website

## Cara Menjalankan Lokal

1. Simpan seluruh folder `portofolio_ika` di server web lokal seperti XAMPP atau Live Server.
2. Buka browser dan akses `http://localhost/portofolio_ika/` (atau path yang sesuai).

> Pastikan folder `image/` tetap berada di tempat yang sama dengan `index.html`.

## Hosting Statis

Website ini dapat dihosting pada layanan statis seperti:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages

### GitHub Pages

1. Buat repository baru di GitHub.
2. Upload seluruh isi folder `portofolio_ika` ke repository.
3. Di pengaturan repository, aktifkan GitHub Pages dari `Settings > Pages`.
4. Pilih cabang `main`/`master` dan direktori root `/`.
5. Simpan, lalu buka URL Pages yang diberikan.

### Netlify / Vercel / Cloudflare Pages

1. Buat akun di layanan pilihan.
2. Hubungkan repository GitHub atau upload folder statis.
3. Pilih direktori root project.
4. Deploy dan buka URL yang disediakan.

## Catatan

- Pastikan semua link menggunakan jalur relatif (`image/...`), sehingga tetap berfungsi saat dihosting.
- Jika ada file `index2.html` tambahan, hosting akan memuat `index.html` sebagai halaman utama secara default.
