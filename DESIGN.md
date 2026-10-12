# DESIGN.md — Group Multi-Portfolio Platform: Kelompok 2 (Tugas Github Basics)

## 1. Product Overview & Identity
- **Product Name:** Kelompok 2 Multi-Portfolio Hub — Tugas Project Github (UTS Sistem Basis Data)
- **Institution:** Program Studi Teknik Informatika, Fakultas Sains dan Teknologi, UIN Syarif Hidayatullah Jakarta.
- **Product Architecture:** A centralized group landing portal (`index.html`) serving as an interactive gateway to three distinct, specialized student portfolios:
  1. **Danuardi Saputro** — *Machine Learning & Applied AI*
  2. **Anugrah Linson Putra Aditama** — *UI/UX Design & Visual Design*
  3. **Azwar Riansyah** — *Data Engineering & Machine Learning*
- **Target Audience:** Course lecturers (Pak Rizal Broer Bahaweres), academic evaluators, tech recruiters, and industry partners.
- **Core Value Proposition:** Demonstrating collaborative Git workflow, modern frontend development, and personal branding for three specialized computing disciplines within a unified cloud-deployed platform.

---

## 2. Visual Theme & Multi-Archetype Aesthetics

### A. Central Hub / Portal (The Directory Gateway)
- **Concept:** Minimalist, editorial directory inspired by modern tech collective showcases.
- **Layout:** High-contrast index with numbered interactive rows (`01`, `02`, `03`), dynamic hover accents, and clean micro-interactions.
- **Accent Signals:** Distinct color accents per member (Amber/Teal for Danuardi, Coral/Violet for Anugrah, Emerald/Cyan for Azwar).

### B. Member Portfolio 1: Danuardi Saputro (ML & AI)
- **Archetype:** *"Research Notebook & Interactive Model Card"*.
- **Style:** Technical paper background (`#EEF1F6`), deep navy typography (`#17213D`), teal badges (`#106B6B`), Newsreader serif headings, and monospace metric chips (3.96 GPA, 3 ML models, 0.81 ROC-AUC).

### C. Member Portfolio 2: Anugrah Linson Putra Aditama (UI/UX)
- **Archetype:** *"Playful Creative Studio & Visual Canvas"*.
- **Style:** Dynamic geometric shapes/blobs, vibrant warm gradients, human-centered layout, Figma & Canva design system showcases, and 3.76 IPK badge.

### D. Member Portfolio 3: Azwar Riansyah (Data Engineering)
- **Archetype:** *"Interactive Developer Terminal & Code Console"*.
- **Style:** Dark terminal window widget (`$ cat profile.json`), CLI prompt aesthetics, structured pipeline diagrams, data engineering stack (SQL, Python, ETL), and 3.79 IPK metric.

---

## 3. Global Color System & Design Tokens

### Unified Tokens
- **Background Root:** `#0B0F19` (Dark mode portal accents) / `#F8FAFC` (Light editorial base).
- **Surface Elevation:** `#FFFFFF` (Light cards) / `#1E293B` (Dark cards).
- **Text Headings:** `#0F172A` (Light mode) / `#F1F5F9` (Dark mode).
- **Text Muted:** `#64748B`.
- **Border Default:** `#E2E8F0` / `#334155`.
- **Radius:** `12px` to `16px` for cards and badges.

### Member Personal Accent Palette
- **Danuardi Saputro:** Amber (`#DE8C2B`) & Teal (`#106B6B`).
- **Anugrah Linson:** Warm Indigo (`#6366F1`) & Coral Rose (`#F43F5E`).
- **Azwar Riansyah:** Terminal Emerald (`#10B981`) & Cyber Cyan (`#06B6D4`).

---

## 4. Typography Hierarchy
- **Portal & Shared Headings:** `Plus Jakarta Sans` / `Inter` / `Newsreader` (Editorial weight 600–700).
- **Body Text:** `Inter` / `IBM Plex Sans` (400, 500, 600) with 1.6 line height.
- **Code & Numerical Metrics:** `IBM Plex Mono` / `JetBrains Mono` for terminal commands, figures, and IPK/GPA badges.

---

## 5. Information Architecture & Navigation Flow

```
[Central Landing Portal: index.html]
  ├── (01) Danuardi Saputro  ──> /Danuardi Saputro/index.html (ML & AI Portfolio)
  ├── (02) Anugrah Linson    ──> /Anugrah Linson Putra Aditama/index.html (UI/UX Portfolio)
  └── (03) Azwar Riansyah    ──> /Azwar-Riansyah/index.html (Data Engineering Portfolio)
       │
       └── Back Navigation Button on every portfolio page returning to Central Hub
```

### Core Features Across All Pages
1. **Responsive Header & Drawer Menu:** Mobile-first collapse with blur backdrop.
2. **Featured Hero Section:** Personal punchline, role tag, GPA/IPK metrics, and primary CTA.
3. **Structured Body Sections:** About, Case Studies / Projects, Technical Skills, and Certifications / Organizations.
4. **Interactive Contact & Social Links:** Real verified channels (Email, LinkedIn, GitHub).
5. **Fast Performance:** Optimized assets, Tailwind CSS integration, zero bloat, instant cloud delivery.
