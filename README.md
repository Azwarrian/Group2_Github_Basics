# Project UTS 1 — GitHub Basics & Personal Portfolio

Repositori proyek tugas **PROJECT UTS 1: GITHUB BASICS & PERSONAL PORTFOLIO** untuk mata kuliah **Sistem Basis Data**, Program Studi **Teknik Informatika (Kelas 3D)**, **UIN Syarif Hidayatullah Jakarta**.

Repositori ini mengintegrasikan portal direktori bersama dan tiga situs portofolio personal anggota Kelompok 2, dibangun menggunakan standar web modern (HTML5, CSS3 murni, dan JavaScript vanilla) yang responsif, performan, serta dideploy secara otomatis.

---

## 👥 Identitas Kelompok 2

| No | Nama Lengkap | Peran / Fokus Bidang | Tautan Portofolio |
| :---: | :--- | :--- | :--- |
| **1** | **Danuardi Saputro** | Machine Learning & AI | [Lihat Portofolio](./Tugas%20Project%20Github/Danuardi%20Saputro/index.html) |
| **2** | **Anugrah Linson Putra Aditama** | UI/UX & Desain Visual | [Lihat Portofolio](./Tugas%20Project%20Github/Anugrah%20Linson%20Putra%20Aditama/index.html) |
| **3** | **Azwar Riansyah** | Data Engineering & ML | [Lihat Portofolio](./Tugas%20Project%20Github/Azwar-Riansyah/index.html) |

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

<p align="center">
  <b>Sistem Basis Data — Teknik Informatika UIN Syarif Hidayatullah Jakarta</b><br>
  Dibuat dengan dedikasi oleh Kelompok 2 © 2026
</p>
