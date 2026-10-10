# Mirza — MC & Event Planner (Landing Page)

Proyek ini dibuat untuk memenuhi tugas mata pelajaran **MK3-C Pemrograman Website** (SMK Telkom). Landing page ini berfokus pada personal branding untuk memperkenalkan layanan Master of Ceremony (MC), perencanaan acara (*event planning*), dan koordinasi kegiatan profesional.

---

## 📌 Konsep Proyek
- **Nama Proyek:** Mirza — MC & Event Planner
- **Tujuan:** Membangun *personal branding* dan memperkenalkan kapabilitas serta layanan di bidang pemandu acara dan manajemen event.
- **Target Pengguna:** Panitia acara sekolah/kampus, organisasi, komunitas, serta calon klien umum/perusahaan.
- **Identitas Visual:**
  - *Navy* (`#0A1424`, `#12233D`): Mencerminkan profesionalisme, stabilitas, dan kepercayaan.
  - *Gold* (`#D4AF37`): Memberikan aksen premium, elegan, dan berkelas.
  - *White / Light Gray* (`#FFFFFF`, `#F8F9FA`): Menjaga keterbacaan (*readability*) dan kesan bersih modern.

---

## 📁 Struktur Berkas Proyek

```text
1. landing page/
├── assets/
│   ├── icons/           # Direktori penyimpanan ikon (SVG, PNG)
│   └── images/          # Direktori aset gambar (foto profil, dokumentasi kegiatan)
├── index.html           # Struktur semantik halaman landing page
├── style.css            # Pengaturan gaya tampilan, tipografi, dan palet warna
├── script.js            # Interaktivitas JavaScript (navigasi, event handler, animasi)
└── README.md            # Dokumentasi proyek dan panduan penggunaan
```

---

## ⚙️ Penjelasan Fungsi Berkas

1. **`index.html`**
   - Berisi kerangka struktur HTML5 semantik (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`).
   - Sudah terhubung dengan `style.css` untuk styling dan `script.js` untuk interaksi.
   - Menggunakan placeholder untuk bagian konten yang akan diisi pada tahap desain.

2. **`style.css`**
   - Menggunakan CSS murni (Vanilla CSS) tanpa framework eksternal.
   - Dilengkapi *design tokens* (CSS variables) untuk warna utama, font, dan spasi.
   - Mengatur CSS reset dasar agar tampilan konsisten di berbagai peramban (*cross-browser*).

3. **`script.js`**
   - Menggunakan JavaScript murni (Vanilla JS) dengan penanganan event `DOMContentLoaded`.
   - Menyiapkan fondasi logika interaktif (seperti menu navigasi mobile dan scroll effect) yang akan diimplementasikan pada tahap selanjutnya.

4. **`assets/images/` & `assets/icons/`**
   - Tempat penyimpanan terorganisir untuk seluruh media grafis dan ikon pendukung.

5. **`README.md`**
   - Berfungsi sebagai dokumentasi teknis yang memudahkan pemahaman struktur dan pelaporan tugas sekolah.

---

## 🚀 Cara Menjalankan Proyek
1. Buka berkas `index.html` langsung menggunakan peramban web (Google Chrome, Firefox, Edge), atau
2. Gunakan ekstensi *Live Server* di VS Code / Antigravity untuk menjalankan server lokal.
