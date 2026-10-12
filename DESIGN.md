# DESIGN.md — Glassmorphism Multi-Portfolio Platform: Kelompok 2 (Tugas Github Basics)

## 1. Product Overview & Identity
- **Product Name:** Kelompok 2 Glassmorphism Multi-Portfolio Platform — Tugas UTS Sistem Basis Data
- **Institution:** Program Studi Teknik Informatika, UIN Syarif Hidayatullah Jakarta
- **Platform Architecture:** Centralized Glassmorphism Landing Hub (`index.html`) connecting to three distinct, specialized student portfolios:
  1. **Danuardi Saputro** — *Machine Learning & Applied AI*
  2. **Anugrah Linson Putra Aditama** — *UI/UX Design & Visual Design*
  3. **Azwar Riansyah** — *Data Engineering & Machine Learning*
- **Target Audience:** Course lecturer (Pak Rizal Broer Bahaweres), tech recruiters, UI designers, and evaluators.

---

## 2. Visual Theme & Aesthetic Direction: Glassmorphism
- **Design Paradigm:** **Modern Premium Glassmorphism (Frosted Glass UI System)**.
- **Atmosphere:** Deep dark ambient canvas with vibrant, multi-colored blurred glow orbs (mesh gradient) that shine through translucent frosted-glass containers.
- **Glass Panel Characteristics:**
  - Background: Semi-transparent backdrop (`rgba(255, 255, 255, 0.05)` to `rgba(255, 255, 255, 0.10)`).
  - Blur Effect: High-fidelity frosted glass blur (`backdrop-filter: blur(16px)`).
  - Border: Subtle crisp translucent hairline (`1px solid rgba(255, 255, 255, 0.15)`).
  - Depth & Shadows: Multi-layered ambient glass elevation (`0 8px 32px 0 rgba(0, 0, 0, 0.37)`).
  - Highlighting: Specular top-edge inner highlight for a tactile polished glass look.

---

## 3. Global Color Palette & Glass Tokens

### Canvas & Ambient Mesh Gradients
- **Root Background Canvas:** Deep space navy / void (`#080B14`).
- **Floating Ambient Glow 1 (Danuardi):** Cyan Glow (`#06B6D4`) & Warm Amber (`#F59E0B`).
- **Floating Ambient Glow 2 (Anugrah):** Electric Violet (`#8B5CF6`) & Sunset Rose (`#F43F5E`).
- **Floating Ambient Glow 3 (Azwar):** Neon Emerald (`#10B981`) & Cyber Blue (`#3B82F6`).

### Glass Surface Tokens
- **Glass Card Default:** `rgba(255, 255, 255, 0.06)` with `backdrop-filter: blur(16px)`.
- **Glass Card Hover:** `rgba(255, 255, 255, 0.12)` with luminous border pulse.
- **Glass Navigation Bar:** `rgba(8, 11, 20, 0.70)` with `backdrop-filter: blur(20px)`.
- **Glass Pill Badges:** `rgba(255, 255, 255, 0.10)` with rounded full capsules.
- **Typography - Headers:** `#FFFFFF` (Crisp white with high readability).
- **Typography - Body:** `#CBD5E1` (Soft slate for comfortable contrast).
- **Typography - Muted:** `#94A3B8` (Subtle captions and meta).

---

## 4. Typography Hierarchy
- **Primary Font:** `Plus Jakarta Sans` or `Inter` (Weights: 400, 500, 600, 700, 800).
- **Code & Numeric Metrics:** `JetBrains Mono` or `IBM Plex Mono` (for GPA badges, ROC-AUC, and CLI commands).
- **Hero Title:** `clamp(2.5rem, 6vw, 4rem)` with gradient text clip (`bg-clip-text text-transparent bg-gradient-to-r from-white via-slate-200 to-slate-400`).

---

## 5. Information Architecture & Navigation Flow

```
[Central Glass Portal: index.html]
  ├── (01) Danuardi Saputro  ──> Frosted Glass ML/AI Card (GPA 3.96, Models, Streamlit)
  ├── (02) Anugrah Linson    ──> Frosted Glass UI/UX Card (IPK 3.76, Figma, Visual Design)
  └── (03) Azwar Riansyah    ──> Frosted Glass Terminal Card (IPK 3.79, SQL, Data Pipelines)
```

### Component Details
1. **Central Portal Hub:**
   - Hero header with subtle glass pill tag: *"Kelompok 2 — Tugas Project Github"*.
   - 3 Frosted Glass Interactive Cards with individual member avatar, glowing role badges, and chevron arrow transitions.
2. **Sub-Portfolios (Per Member):**
   - Translucent floating navigation bar with quick "Back to Portal Hub" icon.
   - Glassmorphic Hero section with glowing metric counter badges.
   - Interactive Project Cards displaying live metrics and technology pills with backdrop blur.
   - Translucent glass form / contact dock featuring links to LinkedIn and GitHub.
