# Website Desa Tanjung Alai

Website profil dan panduan singkat potensi Desa Tanjung Alai, Kecamatan Koto Kampar XIII.

## Menjalankan

Buka `index.html` langsung di browser. Proyek ini menggunakan HTML, CSS, dan JavaScript tanpa dependensi build sehingga dapat dijalankan dari workspace kosong.

## Publikasi dengan GitHub Pages

Workflow tersedia di `.github/workflows/deploy-pages.yml`. Untuk mendapatkan tautan publik:

1. Unggah berkas proyek ini ke repositori GitHub pada branch `main`.
2. Buka **Settings → Pages** di repositori, lalu pilih **GitHub Actions** sebagai sumber publikasi.
3. Buka tab **Actions** dan tunggu workflow **Deploy website to GitHub Pages** selesai.
4. Gunakan URL yang ditampilkan pada hasil deployment. Format umumnya `https://<username>.github.io/<nama-repositori>/`.

Perubahan kode berikutnya pada branch `main` akan memublikasikan ulang situs secara otomatis.

## Isi halaman

- Profil singkat Desa Tanjung Alai
- Potensi perikanan, agrowisata, UMKM, dan kuliner
- Kartu destinasi wisata dengan filter kategori
- Navigasi responsif untuk perangkat mobile
- Tautan lokasi pencarian Google Maps
- Panel admin untuk memperbarui profil desa termasuk visi, misi, sejarah, struktur, destinasi wisata, dan foto galeri; foto profil, struktur, dan tiap wisata dapat dikelola langsung pada bagian masing-masing
- Informasi kontak, telepon penting, dan sosial media desa yang dapat diatur dari panel admin, beserta penghitung kunjungan lokal

Perubahan dari panel admin disimpan secara lokal di browser yang digunakan. Foto galeri dikompres sebelum disimpan; data tidak tersinkron ke perangkat atau browser lain.
Penghitung kunjungan juga disimpan secara lokal dan hanya mencerminkan kunjungan pada browser/perangkat yang sedang digunakan, bukan jumlah pengunjung keseluruhan.
Karena data admin disimpan di browser, perubahan yang dilakukan admin hanya terlihat pada browser/perangkat tersebut dan tidak dibagikan kepada pengunjung lain.

Gambar pada halaman menggunakan dokumentasi lokal yang tersedia serta sumber foto eksternal sebagai placeholder visual, dan dapat dilengkapi dengan dokumentasi asli desa melalui panel admin.
