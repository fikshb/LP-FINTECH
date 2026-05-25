# Design System — AI Speak x Katalis

Panduan visual untuk seluruh dokumen dan materi kolaborasi.

---

## 1. Color Palette

### Primary Colors (AI Speak)

| Nama | Hex | Penggunaan |
|------|-----|------------|
| Speak Blue | `#6CB4E4` | Heading, aksen teknologi, elemen AI |
| Speak Green | `#A8D06E` | Aksen sekunder, highlight, CTA |
| Speak Gradient | Blue → Green | Background hero, divider, ikon |

### Primary Colors (Katalis)

| Nama | Hex | Penggunaan |
|------|-----|------------|
| Katalis Red | `#E82C0C` | Heading, aksen impact, CTA |
| Katalis Dark Red | `#C42409` | Hover state, teks tebal |

### Co-Branding Palette

| Nama | Hex | Penggunaan |
|------|-----|------------|
| Deep Navy | `#1A2332` | Body text, heading utama |
| Slate Gray | `#4A5568` | Body text sekunder, paragraf |
| Light Gray | `#F7F8FA` | Background section |
| White | `#FFFFFF` | Background utama |
| Accent Gold | `#F5A623` | Highlight penting, badge premium |

### Gradients

- **Tech Gradient**: `#6CB4E4` → `#A8D06E` (AI Speak identity)
- **Impact Gradient**: `#E82C0C` → `#F5A623` (Katalis energy)
- **Collaboration Gradient**: `#6CB4E4` → `#E82C0C` (co-branding hero sections)

---

## 2. Typography

### Font Stack

| Level | Font | Weight | Size | Penggunaan |
|-------|------|--------|------|------------|
| H1 | Poppins | Bold (700) | 32–40px | Judul utama dokumen |
| H2 | Poppins | SemiBold (600) | 24–28px | Section heading |
| H3 | Poppins | Medium (500) | 18–22px | Sub-section heading |
| Body | Inter | Regular (400) | 14–16px | Paragraf, deskripsi |
| Caption | Inter | Medium (500) | 12–13px | Label, catatan kaki |
| Data | JetBrains Mono | Regular (400) | 13–14px | Angka, statistik, kode |

### Hierarki Teks

- Heading selalu menggunakan warna **Deep Navy** (`#1A2332`)
- Subheading menggunakan **Slate Gray** (`#4A5568`)
- Link dan CTA menggunakan warna brand yang relevan (Blue/Red)
- Angka besar (statistik) menggunakan warna brand + font Data

---

## 3. Logo Usage

### Penempatan Co-Branding

```
┌──────────────────────────────────────────────┐
│                                              │
│   [AI Speak Logo]    ×    [Katalis Logo]     │
│                                              │
│   Jarak antar logo: minimal 24px             │
│   Separator "×" menggunakan Slate Gray       │
│   Kedua logo harus seimbang secara visual     │
│                                              │
└──────────────────────────────────────────────┘
```

### Rules

- Logo AI Speak dan Katalis harus selalu tampil bersama di dokumen kolaborasi
- Ukuran kedua logo harus proporsional dan seimbang
- Minimum clear space di sekitar logo: setengah tinggi logo
- Jangan memodifikasi warna, proporsi, atau orientasi logo
- Di background gelap, gunakan versi putih/light dari kedua logo
- Penempatan standar: header (kiri) atau footer (center)

---

## 4. Layout & Spacing

### Grid System

- **Dokumen cetak/PDF**: 12-column grid, margin 2.5cm
- **Website**: 12-column grid, max-width 1200px, gutter 24px
- **Presentasi**: 16:9, safe area 5% dari edge

### Spacing Scale

| Token | Nilai | Penggunaan |
|-------|-------|------------|
| xs | 4px | Inline spacing |
| sm | 8px | Compact elements |
| md | 16px | Default gap |
| lg | 24px | Section padding |
| xl | 32px | Between sections |
| 2xl | 48px | Major section breaks |
| 3xl | 64px | Page section dividers |

---

## 5. Component Patterns

### Card Style

```
┌─────────────────────────────┐
│  ▎ Speak Blue left border   │
│                             │
│  H3: Judul Modul            │
│  Body: Deskripsi singkat    │
│                             │
│  [Icon]  Detail →           │
└─────────────────────────────┘
Background: White
Border: 1px solid #E2E8F0
Border-left: 4px solid #6CB4E4 atau #E82C0C
Border-radius: 8px
Shadow: 0 2px 8px rgba(0,0,0,0.06)
```

### Stat Block

```
┌─────────────────┐
│    70%           │  ← Font: Data, size 48px, warna brand
│  perusahaan      │  ← Font: Body, Slate Gray
│  gagal dalam     │
│  transformasi    │
│  digital         │
└─────────────────┘
```

### Section Divider

```
────────── ◆ ──────────
```

Menggunakan garis tipis (`#E2E8F0`) dengan diamond accent di tengah menggunakan warna brand.

### CTA Button

```
┌───────────────────────────┐
│   Hubungi Kami Sekarang   │  Primary: Katalis Red bg, white text
└───────────────────────────┘

┌───────────────────────────┐
│   Lihat Program Training  │  Secondary: White bg, Speak Blue border & text
└───────────────────────────┘
```

---

## 6. Iconography

- Style: **Outlined**, stroke 1.5–2px
- Corner: Rounded (sesuai border-radius 8px)
- Set yang direkomendasikan: Lucide Icons atau Phosphor Icons
- Warna ikon mengikuti konteks section (Blue untuk tech, Red untuk impact)

### Ikon Kunci untuk Proposal

| Konsep | Ikon |
|--------|------|
| AI / Machine Learning | Brain, Cpu, Sparkles |
| Fintech | Wallet, CreditCard, TrendingUp |
| Training | GraduationCap, BookOpen, Users |
| Security | Shield, Lock, Fingerprint |
| Analytics | BarChart, PieChart, Activity |
| Collaboration | Handshake, Users, Link |
| Website | Globe, Layout, Monitor |

---

## 7. Photography & Imagery

### Gaya Visual

- Foto profesional dengan tone hangat dan modern
- Prioritas: foto tim bekerja, workshop, teknologi, fintech environment
- Hindari: stock photo generik, foto terlalu formal/kaku
- Overlay: gunakan gradient brand (opacity 60–80%) untuk hero images

### Ilustrasi

- Style: flat/semi-flat dengan warna brand
- Kompleksitas sedang — detail cukup untuk profesional, tidak terlalu ramai
- Konsisten menggunakan corner radius dan stroke weight yang sama

---

## 8. Tone of Voice (Dokumen)

| Aspek | Guideline |
|-------|-----------|
| Formalitas | Semi-formal — profesional tapi approachable |
| Perspektif | "Kami" (kolaboratif), bukan "Saya" |
| Data | Selalu sertakan angka dan fakta pendukung |
| CTA | Action-oriented, spesifik, tidak generik |
| Jargon | Gunakan istilah industri dengan penjelasan singkat |

### Contoh Tone

- **Terlalu kaku**: "Dengan hormat kami sampaikan proposal pelatihan..."
- **Terlalu santai**: "Hai! Mau belajar fintech bareng kita?"
- **Tepat**: "Program pelatihan ini dirancang untuk membekali tim Anda dengan keahlian fintech yang terukur dan langsung applicable."

---

## 9. File & Asset Reference

| Asset | Path | Format |
|-------|------|--------|
| Logo AI Speak | `Asset/LOGO SPEAK.png` | PNG, transparent bg |
| Logo Katalis | `Asset/Katalis-2048x510.webp` | WebP, transparent bg |

### Format Export

- **Proposal PDF**: A4 portrait, 300 DPI untuk cetak
- **Presentasi**: 16:9, 1920×1080px
- **Website assets**: SVG preferred, PNG fallback @2x
- **Social media**: sesuai platform (1080×1080 IG, 1200×628 LinkedIn)
