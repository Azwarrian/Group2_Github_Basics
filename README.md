# Project UTS 1 — GitHub Basics & Personal Portfolio

Repositori proyek tugas **PROJECT UTS 1: GITHUB BASICS & PERSONAL PORTFOLIO** untuk mata kuliah **Sistem Basis Data**, Program Studi **Teknik Informatika (Kelas 3D)**, **UIN Syarif Hidayatullah Jakarta**.

Repositori ini mengintegrasikan portal direktori bersama dan tiga situs portofolio personal anggota Kelompok 2, dibangun menggunakan standar web modern (HTML5, CSS3 murni, dan JavaScript vanilla) yang responsif, performan, serta dideploy secara otomatis.

---

## 👥 Identitas Kelompok 2

| No | Nama Lengkap | NIM | Peran / Fokus Bidang | Tautan Portofolio |
| :---: | :--- | :---: | :--- | :--- |
| **1** | **Danuardi Saputro** | `125420128` | Machine Learning & AI | [Lihat Portofolio](./Tugas%20Project%20Github/Danuardi%20Saputro/index.html) |
| **2** | **Anugrah Linson Putra Aditama** | — | UI/UX & Desain Visual | [Lihat Portofolio](./Tugas%20Project%20Github/Anugrah%20Linson%20Putra%20Aditama/index.html) |
| **3** | **Azwar Riansyah** | — | Data Engineering & ML | [Lihat Portofolio](./Tugas%20Project%20Github/Azwar-Riansyah/index.html) |

- **Mata Kuliah:** Sistem Basis Data
- **Kelas / Semester:** 3D — Teknik Informatika
- **Dosen Pengampu:** Rizal Broer Bahaweres, S.Kom., M.Sc. (`rizalbroer@uinjkt.ac.id`)

---

## 🌐 Tautan Live Website (Deployment)

Aplikasi telah dikonfigurasi untuk deployment publik otomatis melalui **Vercel** dan **GitHub Actions (GitHub Pages)**:

- 🚀 **Portal Bersama (Landing Directory):**  
  [https://group2-github-basics-rh6x.vercel.app](https://group2-github-basics-rh6x.vercel.app)
- 🤖 **Portofolio Danuardi Saputro:**  
  [https://group2-github-basics-rh6x.vercel.app/Danuardi%20Saputro/index.html](https://group2-github-basics-rh6x.vercel.app/Danuardi%20Saputro/index.html)
- 🎨 **Portofolio Anugrah Linson Putra Aditama:**  
  [https://group2-github-basics-rh6x.vercel.app/Anugrah%20Linson%20Putra%20Aditama/index.html](https://group2-github-basics-rh6x.vercel.app/Anugrah%20Linson%20Putra%20Aditama/index.html)
- 📊 **Portofolio Azwar Riansyah:**  
  [https://group2-github-basics-rh6x.vercel.app/Azwar-Riansyah/index.html](https://group2-github-basics-rh6x.vercel.app/Azwar-Riansyah/index.html)

---

## 📁 Struktur Direktori

```text
Group2_Github_Basics/
├── .github/
│   └── workflows/
│       └── deploy.yml                  # Konfigurasi otomatisasi GitHub Pages CI/CD
├── Tugas Project Github/
│   ├── index.html                      # Portal utama direktori Kelompok 2
│   ├── style.css                       # Styling tema katalog portal utama
│   │
│   ├── Danuardi Saputro/
│   │   ├── index.html                  # Portofolio personal Danuardi Saputro
│   │   ├── style.css                   # Styling Crystal Glassmorphism & Themes
│   │   ├── CV_Danuardi_Saputro.pdf     # Berkas Curriculum Vitae resmi (PDF)
│   │   └── Screenshot 2026-09-24...    # Aset foto profil
│   │
│   ├── Anugrah Linson Putra Aditama/
│   │   ├── index.html                  # Portofolio personal Anugrah Linson
│   │   └── style.css                   # Styling Riso-print Poster & Sticker Studio
│   │
│   └── Azwar-Riansyah/
│       ├── index.html                  # Portofolio personal Azwar Riansyah
│       └── style.css                   # Styling Data Engineering CLI & Terminal
│
└── README.md                           # Dokumentasi resmi proyek repositori
```

---

## 🎨 Konsep Desain & Fitur Unggulan

Setiap anggota memiliki diferensiasi desain visual unik yang mencerminkan spesialisasi keahlian masing-masing, namun tetap terhubung dalam satu ekosistem:

### 1. Portal Direktori Utama (`/index.html`)
- **Konsep:** *Exhibition Catalog Directory* bergaya minimalis elegan.
- Menampilkan daftar anggota dengan indikator warna aksen masing-masing personil (*Cyan* untuk Danuardi, *Flame* untuk Anugrah, dan *Teal* untuk Azwar).
- Layout responsif, bebas distraksi, dan navigasi instan satu klik.

### 2. Portofolio Danuardi Saputro (`Machine Learning & AI`)
- **Konsep:** *Crystal Glassmorphism with Dynamic Luminous Ambient Mesh*.
- **Mode Gelap & Mode Terang:** Toggle instan dengan penyimpanan preferensi pengguna via `localStorage`.
- **Efek Kaca Reflektif (Tactile Glass):** Dibuat dengan `backdrop-filter: blur(28px) saturate(200%)`, specular inner highlight bevel, dan directional light sheen `135deg`.
- **Interactive Cursor Lighting:** Cahaya pendaran dinamis yang mengikuti kursor mouse dan membiaskan warna neon menembus kartu kaca.
- **Download CV Button:** Tautan langsung unduh berkas resume resmi [`CV_Danuardi_Saputro.pdf`](./Tugas%20Project%20Github/Danuardi%20Saputro/CV_Danuardi_Saputro.pdf).
- **One-Click Copy Contact:** Salin Email, No. HP, dan Profil LinkedIn dengan notifikasi toast.
- **Navigasi Terintegrasi:** Tombol melingkar `[ ← ]` untuk kembali ke portal utama.

### 3. Portofolio Anugrah Linson Putra Aditama (`UI/UX & Desain Visual`)
- **Konsep:** *Riso-print Poster Studio*.
- Estetika kertas hangat (`#FAF5EA`), tipografi tegas *Bricolage Grotesque*, serta kartu berbayang offset tegas (*hard sticker shadow* `box-shadow: 6px 6px 0`).
- Tombol kembali `[ ← ]` berbentuk stiker bulat dengan efek hover warna kuning poster (`#FFC93C`).

### 4. Portofolio Azwar Riansyah (`Data Engineering & ML`)
- **Konsep:** *Data Engineering Schema & Terminal CLI*.
- Latar belakang slate gelap bertekstur dot-grid, kartu mock-terminal interaktif, font *JetBrains Mono*, serta aksen sinyal data merah dan teal.
- Tombol kembali `[ ← ]` berbentuk panel CLI dengan efek hover glow teal.

---

## 🛠️ Menjalankan Proyek Secara Lokal

Tidak memerlukan instalasi package manager atau build tools yang kompleks. Cukup gunakan HTTP server statis bawaan:

1. **Clone Repositori:**
   ```bash
   git clone https://github.com/Azwarrian/Group2_Github_Basics.git
   cd Group2_Github_Basics
   ```

2. **Jalankan Local Web Server (Contoh menggunakan Python):**
   ```bash
   python -m http.server 8080 --directory "Tugas Project Github"
   ```

3. **Buka di Browser:**
   Akses `http://localhost:8080/` pada peramban web Anda.

---

## 📌 Alur Pengerjaan Tugas (Milestones)

Proyek ini diselesaikan mengikuti 4 tahapan utama tugas UTS:

1. **Episode 1 — GitHub Student Developer Pack:**  
   Pendaftaran dan verifikasi akun akademik mahasiswa melalui portal GitHub Education menggunakan email resmi kampus (`@mhs.uinjkt.ac.id`) guna mendapatkan akses fitur GitHub Pro, Copilot, serta cloud tools.
2. **Episode 2 — Transformasi Resume ke Website Portofolio:**  
   Penyusunan kode HTML5 dan CSS3 semantik berdasarkan data resume riil, mencakup riwayat pendidikan, ringkasan kompetensi teknis, portofolio proyek teruji, dan sertifikasi keahlian.
3. **Episode 3 — Kolaborasi Git Terpusat:**  
   Penggabungan berkas seluruh anggota tim ke dalam satu repositori bersama, pengaturan kolaborator (termasuk mengundang Dosen Pengampu), serta penerapan branching workflow (`danuardi-portfolio-update`) dan pull request.
4. **Episode 4 — Continuous Deployment (CI/CD):**  
   Pengaturan pipeline deployment otomatis menggunakan integrasi Vercel serta GitHub Pages Workflow (`deploy.yml`) agar portal dapat diakses secara live oleh publik.

---

<p align="center">
  <b>Sistem Basis Data — Teknik Informatika UIN Syarif Hidayatullah Jakarta</b><br>
  Dibuat dengan dedikasi oleh Kelompok 2 © 2026
</p>
