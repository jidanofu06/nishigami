# Lost & Found Center - Rebuild Plan

## Project Structure
```
lostfound_web/
├── index.html         → Halaman utama (daftar laporan)
├── tambah.html        → Form tambah laporan
├── style.css          → Desain tampilan responsif
├── script.js          → Logika interaksi + localStorage
└── assets/            → Folder gambar
```

## Key Features to Implement
1. ✅ **Halaman Utama (index.html)**
   - Navbar sederhana dengan judul "Lost & Found Center"
   - Tombol "+ Tambah Laporan" di pojok kanan atas
   - Grid card responsif (3 kolom desktop, 2 tablet, 1 mobile)
   - Pencarian berdasarkan nama barang/lokasi
   - Mode gelap/terang toggle
   - Pesan "Belum ada laporan saat ini" jika kosong

2. ✅ **Form Tambah Laporan (tambah.html)**
   - Input: nama pelapor, nama barang, lokasi, tanggal
   - Upload gambar dengan preview
   - Tombol "Simpan Laporan"
   - Notifikasi "Laporan berhasil ditambahkan"
   - Redirect ke halaman utama setelah simpan

3. ✅ **Desain Responsif (style.css)**
   - Warna: biru lembut, putih, abu-abu muda
   - Media queries untuk desktop/tablet/mobile
   - Dark/light mode support
   - Modern, bersih, ringan

4. ✅ **JavaScript Logic (script.js)**
   - localStorage untuk penyimpanan data
   - Pencarian dan filter
   - Image upload handling
   - Theme toggle
   - Form validation
   - CRUD operations (Create, Read, Delete)

## Technical Requirements
- HTML, CSS, JavaScript murni
- Bootstrap untuk responsive grid
- jQuery untuk DOM manipulation
- localStorage untuk data persistence
- Offline functionality
- Mobile-first responsive design
