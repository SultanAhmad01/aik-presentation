# Presentasi AIK — MKCHM & Kepribadian Muhammadiyah

Website presentasi satu halaman (*single-page website*) untuk mata kuliah Al-Islam dan Kemuhammadiyahan (AIK), disusun mengikuti makalah terbaru Kelompok 6. Desain menggunakan pendekatan editorial terang, tipografi tegas, ruang kosong, dan aksen biru serta emas.

## Isi Website

1. **Hero / Sampul** — judul, identitas kelompok, logo Trio Savagos, dan navigasi.
2. **Pendahuluan** — peran Muhammadiyah dalam pendidikan, kesehatan, pelayanan sosial, penanggulangan bencana, dan pemberdayaan ekonomi umat.
3. **Pokok MKCHM** — lima pokok ringkasan tentang landasan Islam, sumber ajaran, pengamalan, dan cita-cita sosial Muhammadiyah.
4. **Visi Berkemajuan** — tauhid, ilmu pengetahuan dan teknologi, akhlak, keadilan sosial, serta sikap kritis terhadap taklid buta.
5. **Sejarah dan Tokoh** — faktor eksternal/internal, gagasan K.H. Faqih Usman, kursus pimpinan di Yogyakarta, perwakilan wilayah, tim penyempurna, Sidang Tanwir Agustus 1962, Muktamar ke-35, serta keterangan MKCHM pada Muktamar ke-37 tahun 1968 sebagaimana disebut dalam makalah terbaru.
6. **Sepuluh Sifat Kepribadian Muhammadiyah** — ringkasan sepuluh sifat dan contoh penjelasannya berdasarkan bagian baru pada makalah terbaru.
7. **Relevansi Era Digital** — literasi informasi, dakwah digital, etika bermedia, dan inovasi sosial.
8. **Referensi** — sembilan rujukan yang tercantum dalam makalah terbaru, dengan tautan ke DOI atau katalog/sumber daring yang tersedia.
9. **Kesimpulan dan Penutup** — rangkuman landasan, pedoman, dan pengamalan.

## Catatan Akademik

- Bagian sistematika MKCHM adalah ringkasan penjelas untuk kebutuhan presentasi. Makalah terbaru tidak menyebutkan butir sistematika satu per satu. Cocokkan dengan naskah MKCHM resmi atau modul AIK yang digunakan dosen.
- Sepuluh sifat Kepribadian Muhammadiyah telah disebutkan dalam makalah terbaru dan diringkas untuk layar. Jika diperlukan, gunakan redaksi persis dari referensi utama.
- Kronologi di website mengikuti makalah terbaru: Kepribadian Muhammadiyah dibahas dalam rentang 1961–1962 dan disahkan pada Muktamar ke-35 tahun 1962; bagian pendahuluan makalah menyebut rumusan akhir MKCHM pada Muktamar ke-37 tahun 1968 di Yogyakarta. Periksa redaksi serta rujukan sejarahnya sebelum presentasi.
- Bibliografi website mengikuti referensi [1]–[9] pada makalah terbaru. Metadata buku/katalog ditampilkan berdasarkan informasi di makalah, sehingga sebaiknya dicocokkan kembali sebelum pengumpulan akhir.

## Teknologi

- HTML5
- CSS3
- JavaScript murni (*vanilla JavaScript*)
- Tailwind CSS melalui CDN
- Google Fonts: DM Sans dan DM Serif Display

Tidak dibutuhkan framework JavaScript, backend, atau proses build untuk menjalankan versi statis ini.

## Struktur Folder

```text
aik-presentation/
├── index.html             # Struktur, materi, dan referensi
├── styles.css             # Warna, layout, responsivitas, dan animasi
├── script.js              # Menu mobile, progres, navigasi aktif, reveal
├── triosavagos-logo.png   # Logo pada navigasi
└── README.md              # Dokumentasi proyek
```

Pastikan semua file berada dalam folder yang sama. File `triosavagos-logo.png` digunakan pada navigasi kiri atas.

## Menjalankan Secara Lokal

1. Ekstrak ZIP atau kloning repositori.
2. Buka folder proyek di VS Code.
3. Buka `index.html` di browser atau gunakan ekstensi Live Server.
4. Periksa navigasi, file CSS/JavaScript, dan tampilan mobile.

Koneksi internet diperlukan untuk memuat Tailwind CSS dan Google Fonts melalui CDN.

## Deploy ke GitHub Pages

1. Unggah kelima file ke direktori utama (*root*) repositori GitHub: `index.html`, `styles.css`, `script.js`, `triosavagos-logo.png`, dan `README.md`.
2. Buka **Settings → Pages**.
3. Pilih **Deploy from a branch**, branch `main`, dan folder `/(root)`, lalu simpan.
4. Setelah deployment selesai, buka URL yang diberikan GitHub Pages.

### Memperbarui Website

Tidak perlu *undeploy* untuk mengubah konten. Edit file yang sesuai, lalu commit perubahan ke GitHub. Jika menggunakan Git:

```bash
git add .
git commit -m "Perbarui materi presentasi AIK"
git push
```

GitHub Pages akan menerbitkan pembaruan dari branch yang dikonfigurasi.

## Kustomisasi

- **Materi, susunan section, dan navigasi:** `index.html`.
- **Warna, tipografi, jarak, layout, dan responsivitas:** `styles.css`.
- **Menu mobile, progres membaca, navigasi aktif, dan animasi masuk:** `script.js`.
- **Logo navigasi:** ganti `triosavagos-logo.png` dengan file baru bernama sama, atau ubah `src` gambar pada `index.html`.

## Lisensi

Materi disiapkan untuk kebutuhan pembelajaran dan presentasi. Pastikan penggunaan kutipan dan aset pihak ketiga mengikuti ketentuan sumber masing-masing.
