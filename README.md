# 🐱 MimiMind AI — PABWE P2

MimiMind AI adalah website studi kasus perusahaan jasa **Artificial Intelligence (AI)** dengan konsep visual **cute, pastel pink, dan virtual cat**. Website ini dibuat untuk memenuhi praktikum PABWE P2 dengan tiga pendekatan styling yang berbeda.

> **Tema:** AI yang ramah dan menyenangkan bersama Mimi, kucing virtual MimiMind AI.

## 👩‍💻 Identitas

- **Nama:** Miftahul Jannah Siregar
- **Program Studi:** S1 Informatika
- **Institusi:** Institut Teknologi Del
- **Organisasi:** Departemen Agama dan Sosial, Badan Eksekutif Mahasiswa

## 📁 Struktur Project

```text
username-kamu-pabwe-p2/
│
├── index.html                 # Landing page — HTML + CSS murni
├── blog.html                  # Daftar blog — Bootstrap 5 + Icons
├── blog-detail.html           # Detail blog — Bootstrap 5 + Icons
├── cv.html                    # CV digital — Tailwind CSS 4
├── README.md
│
└── assets/
    ├── css/
    │   └── style.css          # External CSS untuk landing/blog
    └── img/
        ├── ai-generative.svg
        ├── prompt-engineering.svg
        ├── etika-ai.svg
        ├── machine-learning.svg
        └── mimi-avatar.svg
```

## 🛠️ Teknologi

### 1. Landing Page — `index.html`
- Semantic HTML5: `header`, `nav`, `main`, `section`, `article`, `footer`
- **External CSS** pada `assets/css/style.css`
- CSS Variables
- Flexbox dan CSS Grid
- Hover dan transition
- Responsive desktop/mobile
- Form kontak sederhana
- Tidak menggunakan Bootstrap/Tailwind pada halaman ini

### 2. Blog — `blog.html` dan `blog-detail.html`
- **Bootstrap 5.3.8** melalui CDN
- **Bootstrap Icons 1.13.1**
- Navbar responsive
- Grid dan card
- Badge kategori
- Metadata artikel dengan Bootstrap Icons
- Minimal 4 artikel bertema AI
- Detail artikel berisi lebih dari 3 paragraf
- Blockquote, list, alert, artikel terkait, dan form komentar
- Cover artikel menggunakan aset SVG lokal agar halaman tidak bergantung pada gambar eksternal

### 3. Curriculum Vitae — `cv.html`
- **Tailwind CSS 4** melalui Play CDN
- `@theme` untuk token warna MimiMind
- Responsive utility classes
- Flexbox dan Grid
- Hover dan transition
- Profile, contact, about, education, organization, projects, skills, interests, dan achievement

## 🧭 Integrasi Navigasi

Semua halaman saling terhubung melalui navbar dan footer:

```text
index.html
├── blog.html
│   └── blog-detail.html
└── cv.html
```

Dari `blog.html`, seluruh tombol **Baca selengkapnya** membuka `blog-detail.html` sesuai requirement praktikum.

## 🎨 Konsep UI

MimiMind AI menggunakan:

- Pastel pink sebagai warna utama
- Lavender sebagai aksen
- Kucing virtual Mimi sebagai identitas visual
- Rounded cards dan pill buttons
- Hierarki heading yang jelas
- Whitespace yang cukup
- Fokus keyboard yang terlihat
- Kontras teks yang diperhatikan untuk aksesibilitas
- `alt` text pada gambar
- Skip link untuk membantu pengguna keyboard/screen reader
- `prefers-reduced-motion` pada halaman CSS

## ♿ Aksesibilitas

Beberapa perbaikan yang diterapkan setelah pengecekan accessibility:

- Warna teks utama dan tombol menggunakan warna pink yang lebih gelap agar memenuhi kontras WCAG AA.
- Badge menggunakan teks gelap di atas background pastel.
- Link footer menggunakan warna teks gelap.
- Heading dan section memiliki struktur semantik.
- Form mempunyai label yang terhubung dengan input melalui `for`/`id`.
- Icon dekoratif diberi `aria-hidden="true"`.
- Navbar mempunyai label navigasi.
- Current page diberi `aria-current="page"`.
- Tombol navbar Bootstrap mempunyai `aria-label` dan relasi `aria-controls`.

## ⚡ Optimasi Performa

- Cover blog menggunakan SVG lokal berukuran ringan.
- Gambar artikel kedua dan seterusnya menggunakan `loading="lazy"`.
- Ukuran gambar ditentukan dengan atribut `width` dan `height` untuk mengurangi layout shift.
- Script Bootstrap menggunakan `defer`.
- Font eksternal tidak digunakan agar tidak menambah request dan render-blocking resource.
- Bootstrap dan Tailwind tetap menggunakan CDN karena merupakan bagian dari requirement praktikum.

## ▶️ Cara Menjalankan

Tidak membutuhkan server khusus untuk tampilan dasar. Buka `index.html` di browser atau gunakan extension **Live Server** pada VS Code.

Urutan pengujian yang disarankan:

1. Buka `index.html`.
2. Coba navigasi ke `blog.html`.
3. Klik **Baca selengkapnya** pada salah satu artikel.
4. Pastikan halaman terbuka ke `blog-detail.html`.
5. Coba navigasi ke `cv.html`.
6. Uji tampilan desktop dan mobile melalui DevTools.
7. Jalankan accessibility audit setelah seluruh halaman dimuat.

## 📝 Catatan Data Kontak

Nomor telepon/WhatsApp dan username GitHub pada CV masih menggunakan placeholder. Ganti bagian tersebut dengan data pribadi sebelum pengumpulan.

## ✅ Checklist Studi Kasus

- [x] Landing page jasa AI dengan external CSS
- [x] Minimal 3 layanan AI
- [x] Tentang/keunggulan
- [x] CTA dan form kontak
- [x] Footer dan link cepat
- [x] Daftar blog AI minimal 4 artikel
- [x] Bootstrap 5
- [x] Bootstrap Icons
- [x] Detail blog AI
- [x] Cover artikel
- [x] Metadata artikel
- [x] Komentar sederhana
- [x] CV dengan Tailwind CSS 4
- [x] Pendidikan
- [x] Pengalaman/organisasi minimal 2 item
- [x] Technical skills
- [x] Minimal 2 proyek
- [x] Responsive desktop dan mobile
- [x] Semua halaman saling terhubung melalui navigasi
- [x] Identitas visual MimiMind AI konsisten
