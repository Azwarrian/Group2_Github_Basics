# DESIGN.md — Personal Portfolio Design System: Danuardi Saputro

## 1. Product Overview & Identity
- **Product Name:** Danuardi Saputro — Machine Learning & Applied AI Portfolio
- **Target Audience:** Recruiters, engineering hiring managers, academic evaluators, and research collaborators.
- **Core Value Proposition:** Highlighting end-to-end Machine Learning and AI engineering capability—from data cleansing and exploratory analysis to model training, evaluation metrics, and shipping live interactive interfaces (Streamlit / Web).
- **Brand Personality:** Analytical, academic yet modern, methodical, credible, clean, and data-centric.

---

## 2. Visual Theme & Aesthetic Direction
- **Concept Archetype:** *"Research Notebook & Interactive Model Card"*
- **Look & Feel:** High-contrast editorial layout that combines academic precision (editorial serif headers, monospace metrics) with modern software product design (smooth micro-interactions, clean cards, subtle backdrop blur, and accessible contrast).
- **Theme Mode:** Refined light paper theme with deep navy ink and purposeful data accents. Supports dark mode transition with deep slate (`#0B0F19`) surfaces.

---

## 3. Color Palette & Design Tokens

### Primary & Neutral System
- **Background Main (`--bg`):** `#EEF1F6` (Cool technical paper grey-white)
- **Background Alternate (`--bg-alt`):** `#E4E8F0` (Slightly deeper contrast section background)
- **Surface / Card (`--surface`):** `#FFFFFF` (Pure white card surfaces)
- **Ink Primary (`--ink`):** `#12172A` (Deep charcoal navy for primary headings and body)
- **Ink Secondary (`--ink-soft`):** `#545C74` (Muted body text and secondary descriptions)
- **Ink Faint (`--ink-faint`):** `#8890A6` (Captions, timestamps, metadata)
- **Border Default (`--border`):** `#D6DBE6` (Crisp subtle hairline borders)

### Semantic & Accent Colors
- **Navy Accent (`--navy`):** `#17213D` (Sophisticated deep slate navy for brand typography)
- **Teal / AI Accent (`--teal`):** `#106B6B` (Engineering precision, badges, active states)
- **Teal Tint (`--teal-tint`):** `#DDEEEC` (Soft background pills for models & metrics)
- **Amber Accent (`--amber`):** `#DE8C2B` (Highlights, status indicators, badges)
- **Amber Tint (`--amber-tint`):** `#FBEBD4` (Notice highlights, feature callouts)

---

## 4. Typography Hierarchy

### Font Families
- **Display / Editorial Headings:** `Newsreader`, Georgia, or modern serif (Weights: 500, 600) — communicates editorial credibility and academic rigor.
- **Interface & Body Text:** `IBM Plex Sans`, `Inter`, or `Plus Jakarta Sans` (Weights: 400, 500, 600, 700) — clean, highly legible technical sans-serif.
- **Data & Numerical Metrics:** `IBM Plex Mono` or `JetBrains Mono` (Weights: 400, 500) — used for figure numbers (`Fig. 01`), statistical metrics (`ROC-AUC 0.81`, `GPA 3.96`), and timestamps.

### Scale & Spacing
- **Hero Title:** `clamp(2.4rem, 5vw, 3.6rem)` with `-0.02em` tracking.
- **Section Headings (H2):** `clamp(1.7rem, 3vw, 2.3rem)`.
- **Card Titles (H3):** `1.25rem` to `1.4rem`.
- **Body Text:** `16px` base (`1.0rem`), `line-height: 1.6`.
- **Metadata / Kickers:** `0.8rem` uppercase monospace with letter spacing.

---

## 5. Layout Architecture & Key Sections

1. **Global Sticky Navigation Bar:**
   - Monogram logo (`DS` in minimalist rounded mark).
   - Clean anchor links (`About`, `Projects`, `Certifications`).
   - Prominent call-to-action button (`Contact`).
   - Frosted glass effect (`backdrop-filter: blur(10px)`).

2. **Hero Header:**
   - Role badge: *"Informatics Engineering student — Machine Learning & AI"*.
   - Value lede highlighting end-to-end model development and UIN Syarif Hidayatullah Jakarta affiliation.
   - Dual CTA: Primary button (*View projects*) + Ghost button (*Get in touch*).
   - **Key Metric Indicators:**
     - `3.96` (Cumulative GPA out of 4.00)
     - `3` (ML models shipped to production/Streamlit)
     - `0.81` (Best ROC-AUC score)
   - Profile Portrait Frame with status tag (*Open to internships*).

3. **About & Academic Profile:**
   - Narrative story focusing on data-driven engineering and UI delivery.
   - Formal education card (Bachelor of Informatics Engineering, UIN Syarif Hidayatullah Jakarta).

4. **Technical Skills Taxonomy:**
   - Grouped categorized cards:
     - *Modeling & ML:* Python, TensorFlow, PyTorch, Scikit-Learn, XGBoost.
     - *Data & Deployment:* Pandas, NumPy, Streamlit, Git, SQL.
     - *Design & Visual:* Figma, Adobe Photoshop.

5. **Case Studies / Featured Projects:**
   - Card format numbered like research notebook figures (`Fig. 01`, `Fig. 02`, `Fig. 03`).
   - Project 1: **Diagnostic Liver Disease Prediction** (LFT data, XGBoost, Streamlit app, ROC-AUC 0.76).
   - Project 2: **Customer Churn Prediction** (Behavioral subscription data, Random Forest, ROC-AUC 0.81).
   - Project 3: **House Price Prediction** (Property & geographic regression, XGBoost, R² 0.87).
   - Pill tags for tools and technical metrics.

6. **Certifications & Professional Learning:**
   - Multi-column grid showcasing credentials from Dicoding (ASAH AI 2026, AI Minicamp), DBS Foundation Coding Camp, and IBM SkillsBuild.

7. **Contact & Professional Presence:**
   - Actionable direct channels: Email, WhatsApp/Phone.
   - Verified profile links: LinkedIn (`danuardi-saputro`), GitHub Primary (`Danuardi-Saputro`), GitHub Developer (`dnnuuyzzo`).

---

## 6. Components & Design Tokens
- **Corner Radius:** `8px` to `12px` (`--radius: 10px`) for soft modern cards.
- **Shadows:** Subtle layered shadows (`0 10px 30px -18px rgba(18, 23, 42, 0.25)`).
- **Interactions:** Hover states with smooth translate (`translateY(-2px)`), high contrast keyboard focus rings, and responsive mobile-first drawer navigation.
