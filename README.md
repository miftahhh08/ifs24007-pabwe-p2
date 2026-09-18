# 🐱 MimiMind AI — PABWE P2

Website studi kasus praktikum **Pemrograman Aplikasi Berbasis Web (PABWE)** dengan tema perusahaan jasa **Artificial Intelligence (AI)** yang dikemas dengan identitas cute, pastel pink, dan karakter **virtual cat** bernama Mimi.

## 📌 Identitas Proyek

- **Nama website:** MimiMind AI
- **Tema:** Jasa Artificial Intelligence dengan virtual cat
- **Bahasa:** Bahasa Indonesia
- **Konsep visual:** Cute, pastel pink, lavender, dan cat
- **Nama folder:** `{username-kamu}-pabwe-p2`

> Ganti `{username-kamu}` pada nama folder dengan username/NIM sesuai ketentuan praktikum.

## 📁 Struktur Folder

```text
username-kamu-pabwe-p2/
│
├── index.html              # Landing Page - HTML + CSS murni
├── blog.html               # Daftar Blog - Bootstrap 5
├── blog-detail.html        # Detail Blog - Bootstrap 5
├── cv.html                 # Curriculum Vitae - Tailwind CSS 4
├── README.md               # Dokumentasi proyek
│
└── assets/
    ├── css/
    │   └── style.css       # External CSS landing page
    └── img/                # Folder aset gambar (opsional)
```

## 🛠️ Teknologi yang Digunakan

### 1. Landing Page — CSS Murni

File: `index.html` dan `assets/css/style.css`

- Semantic HTML5: `header`, `nav`, `main`, `section`, `article`, `footer`
- External CSS
- CSS variables
- Flexbox
- CSS Grid
- Box model
- Typography
- Hover dan transition
- CSS animation sederhana
- Responsive media query
- Tidak menggunakan Bootstrap, Tailwind, atau framework CSS lain

### 2. Blog — Bootstrap 5 + Bootstrap Icons

File:

- `blog.html`
- `blog-detail.html`

Digunakan:

- Bootstrap 5
- Bootstrap Icons
- Navbar responsive
- Container, row, dan column
- Card
- Badge
- Pagination
- Form
- Alert
- Responsive utility classes

Konten blog membahas topik AI seperti:

- Generative AI
- Prompt Engineering
- Etika AI
- Machine Learning

### 3. CV — Tailwind CSS 4

File: `cv.html`

Menggunakan Tailwind CSS 4 melalui Play CDN dengan:

- `@theme`
- Flexbox
- CSS Grid
- Spacing utilities
- Typography utilities
- Responsive prefixes (`sm:`, `md:`, `lg:`)
- Hover dan transition
- Badge/chip keahlian

## 🔗 Integrasi Navigasi

Semua halaman dibuat saling terhubung:

```text
index.html
   ├── blog.html
   │      └── blog-detail.html
   └── cv.html
```

Navigasi utama tersedia pada setiap halaman.

- Landing Page → Blog
- Landing Page → CV
- Blog → Landing Page
- Blog → Detail Blog
- Blog → CV
- Detail Blog → Daftar Blog
- Detail Blog → Landing Page
- Detail Blog → CV
- CV → Landing Page
- CV → Blog

## 🎨 Konsep Desain

MimiMind AI menggunakan konsep **AI yang friendly dan menyenangkan**.

Elemen visual utama:

- 🐱 Virtual cat sebagai karakter Mimi
- 🌸 Pastel pink
- 💜 Lavender/purple
- ✨ Sparkle dan elemen cute
- 🐾 Microcopy bertema kucing
- 📚 Nuansa belajar yang ramah untuk pemula

Identitas visual tetap konsisten pada seluruh halaman walaupun teknologi styling yang digunakan berbeda.

## ▶️ Cara Menjalankan

Tidak membutuhkan server khusus.

1. Buka folder proyek menggunakan VS Code.
2. Pastikan struktur folder tidak berubah.
3. Buka `index.html` menggunakan browser atau Live Server.
4. Coba seluruh menu navigasi.
5. Uji tampilan desktop dan mobile menggunakan browser DevTools.

## ✅ Checklist Studi Kasus

- [x] Landing page AI dengan external CSS
- [x] Tidak menggunakan CSS framework pada landing page
- [x] Minimal 3 layanan AI
- [x] Semantic HTML5
- [x] Responsive desktop dan mobile
- [x] Blog list menggunakan Bootstrap 5
- [x] Bootstrap Icons digunakan
- [x] Minimal 4 artikel AI
- [x] Judul artikel terhubung ke `blog-detail.html`
- [x] Detail blog menggunakan Bootstrap 5
- [x] Detail blog memiliki minimal 3 paragraf
- [x] Detail blog memiliki metadata dan ikon
- [x] Form komentar sederhana
- [x] CV menggunakan Tailwind CSS 4
- [x] CV responsive
- [x] Semua halaman memiliki navigasi
- [x] Identitas MimiMind AI konsisten
- [x] Tema konten landing page dan blog tetap berkaitan dengan AI
- [x] Kode diberi komentar pada bagian penting

## 👩‍💻 Data CV

CV berisi profil mahasiswa Informatika dengan fokus dan pengalaman pada:

- HTML
- CSS
- Web Design
- UI Design
- Video Editing
- Content Creation
- Bootstrap
- Tailwind CSS
- Organisasi: Departemen Agama dan Sosial, Badan Eksekutif Mahasiswa

## 📝 Catatan Pengembangan

Form kontak dan komentar pada proyek ini merupakan tampilan frontend untuk memenuhi kebutuhan studi kasus. Form belum terhubung ke database atau backend.

Folder `assets/img/` disediakan apabila nantinya ingin menambahkan foto profil atau aset ilustrasi lokal.
