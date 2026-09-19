# MimiMind AI — PABWE P2

Website studi kasus praktikum PABWE untuk perusahaan jasa Artificial Intelligence (AI) dengan konsep virtual cat yang cute dan ramah.

## Identitas Proyek

- **Nama proyek:** `mimimind-pabwe-p2`
- **Brand:** MimiMind AI
- **Tema:** Jasa Artificial Intelligence dengan virtual cat
- **Bahasa konten:** Bahasa Indonesia, kecuali istilah teknis yang umum

## Teknologi

### 1. Landing Page — `index.html`
Menggunakan:
- Semantic HTML5
- HTML + CSS murni
- External CSS: `assets/css/style.css`
- CSS variables
- Flexbox dan CSS Grid
- Hover/transition
- Media query responsive

**Tidak menggunakan Bootstrap atau Tailwind pada landing page.**

### 2. Blog — `blog.html`
Menggunakan:
- Bootstrap 5.3.8
- Bootstrap Icons
- Navbar
- Grid/row/col
- Card
- Badge
- Footer
- Metadata artikel lengkap: penulis, tanggal, dan waktu baca

Terdapat 4 artikel bertema AI.

### 3. Detail Blog — `blog-detail.html`
Menggunakan:
- Bootstrap 5.3.8
- Bootstrap Icons
- Cover artikel
- Metadata
- Isi artikel minimal 3 paragraf
- Blockquote
- List
- Alert
- Artikel terkait
- Form komentar

Semua link artikel dari `blog.html` membuka `blog-detail.html`.

### 4. CV — `cv.html`
Menggunakan:
- Tailwind CSS 4 melalui Play CDN
- Utility classes
- Responsive prefixes
- Flexbox dan Grid
- Hover dan transition
- `@theme` untuk brand color

Isi CV mencakup:
- Miftahul Jannah Siregar
- Periode pendidikan: 2024 – Sekarang
- Mahasiswa S1 Informatika
- Departemen Agama dan Sosial — Badan Eksekutif Mahasiswa
- HTML
- CSS
- Web Design
- UI Design
- Video Editing
- Content Creator
- Bootstrap
- Tailwind CSS
- Git

## Struktur Folder

```text
mimimind-pabwe-p2/
├── index.html
├── blog.html
├── blog-detail.html
├── cv.html
├── README.md
├── vercel.json
└── assets/
    ├── css/
    │   ├── style.css
    │   └── bootstrap-custom.css
    └── img/
        ├── ai-generative.png
        ├── prompt-engineering.png
        ├── etika-ai.png
        ├── machine-learning.png
        └── mimi-avatar.png
```

## Integrasi Navigasi

Semua halaman saling terhubung menggunakan path relatif:

```text
index.html
├── blog.html
│   └── blog-detail.html
└── cv.html
```

Navbar/footer menggunakan:
- `index.html`
- `blog.html`
- `blog-detail.html`
- `cv.html`

Untuk deployment Vercel, `vercel.json` menyediakan rewrite `/blog`, `/blog-detail`, dan `/cv` ke file HTML terkait. Link internal tetap menggunakan path file relatif agar aman saat dijalankan di Live Server.

## Cara Menjalankan

1. Buka folder proyek di VS Code.
2. Pastikan struktur folder tidak berubah.
3. Buka `index.html`.
4. Jalankan dengan Live Server atau buka langsung di browser.
5. Uji semua link:
   - Landing Page → Blog
   - Landing Page → CV
   - Blog → Detail Blog
   - Detail Blog → Blog
   - Semua halaman → Landing Page/CV/Blog

## Checklist Studi Kasus

- [x] Semantic HTML5
- [x] Responsive desktop dan mobile
- [x] Landing page dengan external CSS
- [x] Tanpa framework CSS pada landing page
- [x] Minimal 3 layanan AI
- [x] Blog menggunakan Bootstrap 5
- [x] Bootstrap Icons digunakan
- [x] Minimal 4 artikel AI
- [x] Detail blog menggunakan Bootstrap 5
- [x] Detail blog memiliki minimal 3 paragraf
- [x] CV menggunakan Tailwind CSS 4
- [x] Semua halaman memiliki navigasi
- [x] Brand MimiMind AI konsisten
- [x] `blog.html` terhubung ke `blog-detail.html`
- [x] Aset gambar tersedia secara lokal
- [x] Struktur kode diberi komentar singkat pada bagian penting
- [x] Layout responsive
