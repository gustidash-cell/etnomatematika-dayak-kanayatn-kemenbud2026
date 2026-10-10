# DESIGN SYSTEM: ETNOMATEMATIKA DAYAK KANAYATN (KEMENBUD 2026)
*Unified OpenDesign × UI/UX Pro Max Architecture*

---

## 1. Identitas & Karakter Desain
- **Domain:** Dokumentasi Kebudayaan Nasional, Etnomatematika, & Riset Etnografis Lapangan (Dana Abadi Kebudayaan Kemenbud RI 2026).
- **Lokus:** Rumah Radakng Saham, Desa Saham, Sengah Temila, Kabupaten Landak, Kalimantan Barat.
- **Konsep Visual:** *Borneo Cultural Heritage meets Modern Scientific Fieldwork Dashboard*. Memadukan kehormatan tradisi lisan Dayak Kanayatn dengan ketelitian metodologis sains matematika.
- **Surface Mode:** Web Interactive Portal / Single-File App (Responsive across Mobile, Tablet, Laptop, & Desktop) with `@media print` support.

---

## 2. Token Semantik CSS (`:root`)

```css
:root {
  /* Surfaces & Canvas */
  --bg: #0c0f14;
  --surface: #141922;
  --surface-raised: #1c2230;
  --surface-hover: #232c3d;
  --surface-glass: rgba(20, 25, 34, 0.85);

  /* Typography Scale */
  --text-primary: #f3f4f6;
  --text-secondary: #9ca3af;
  --text-muted: #6b7280;
  --text-inverse: #0c0f14;

  /* Brand Accents (Borneo Heritage: Ochre Gold & Harvest Amber + Forest Emerald) */
  --accent: #e5a93c;              /* Padi Menguning / Emas Budaya */
  --accent-hover: #f3be58;
  --accent-subtle: rgba(229, 169, 60, 0.12);
  --accent-secondary: #22c55e;    /* Hutan Borneo & Kesuburan */
  --accent-secondary-subtle: rgba(34, 197, 94, 0.12);
  --accent-tertiary: #38bdf8;     /* Kosmologi Langit & Navigasi Bintang */

  /* Borders & Dividers */
  --border: rgba(255, 255, 255, 0.08);
  --border-strong: rgba(255, 255, 255, 0.16);
  --border-accent: rgba(229, 169, 60, 0.35);

  /* Typography Pairing */
  --font-display: 'Outfit', 'Plus Jakarta Sans', sans-serif;
  --font-body: 'Plus Jakarta Sans', -apple-system, BlinkMacSystemFont, sans-serif;
  --font-mono: 'JetBrains Mono', monospace;

  /* Shadows & Elevations */
  --shadow-sm: 0 2px 8px rgba(0, 0, 0, 0.25);
  --shadow-md: 0 8px 24px rgba(0, 0, 0, 0.35);
  --shadow-lg: 0 16px 48px rgba(0, 0, 0, 0.5);
  --shadow-glow: 0 0 30px rgba(229, 169, 60, 0.18);

  /* Radius & Transitions */
  --radius-sm: 6px;
  --radius-md: 12px;
  --radius-lg: 18px;
  --radius-full: 9999px;
  --ease-spring: cubic-bezier(0.16, 1, 0.3, 1);
  --duration-fast: 180ms;
  --duration-normal: 280ms;
}
```

---

## 3. Struktur Layout & Komponen
1. **Header & Status Banner:**
   - Badge program: *Kementerian Kebudayaan RI | Dana Abadi Kebudayaan 2026*.
   - Countdown / Status Kesiapan Operasional, Nama Lokus, dan Peneliti Utama (*Dr. Siti Suprihatiningsih, M.Pd.*).
2. **Interactive Stepper: 6 Fase Alur Pengumpulan Data:**
   - Fase 1: Perizinan Adat & Administrasi.
   - Fase 2: Pra-Survei & Kalibrasi Kalender Tani.
   - Fase 3: Gelombang I (Persiapan & Penanaman / Nugal).
   - Fase 4: Gelombang II (Perawatan & Panen / Ngetam).
   - Fase 5: Triangulasi & Validasi Adat (*Member Checking* di Rumah Radakng).
   - Fase 6: Finalisasi 7 Luaran (Buku OPK, Jurnal, Video 4K, HKI, Pameran).
3. **Pusat Unduhan & Panduan 8 Instrumen (Filterable Bento Grid):**
   - Kartu dokumen berstandar monoline icon SVG dengan tombol pratinjau detail, petunjuk penggunaan lapangan, dan rincian teknis.
4. **Kalkulator Metrologi Tradisional Interaktif:**
   - Konversi langsung: *Solok, Gantang, Kaleng, Depa, Jengkal, Langkah, Tumpak* ke satuan SI (gram, liter, cm, meter persegi).
5. **Glosarium Etnomatematika Kanayatn (Searchable):**
   - Istilah bahasa Kanayatn terkait 6 aktivitas Bishop (Counting, Locating, Measuring, Designing, Playing, Explaining).
6. **Checklist Kesiapan Lapangan (Interactive LocalStorage):**
   - Berkas administrasi, alat metrologi, perangkat audiovisual, dan tata krama adat yang dapat dicentang langsung oleh tim di lapangan.
7. **Peta & Kontak Tim Pelaksana:**
   - Alamat Rumah Radakng Saham dan kontak divisi kepanitiaan.

---

## 4. Guardrails Anti-AI-Slop (The Seven Cardinal Sins)
- ❌ **Dilarang menggunakan Tailwind Indigo klise** (`#6366f1`). Menggunakan Amber Ochre `#e5a93c` dan Forest Emerald `#22c55e`.
- ❌ **Dilarang menggunakan Two-Stop Violet Gradient** di hero banner.
- ❌ **Dilarang memakai emoji** untuk UI icon. Wajib memakai inline Monoline SVG (`stroke="currentColor"`, `stroke-width="1.6"`).
- ❌ **Dilarang filler text / lorem ipsum.** Seluruh teks memuat data faktual proposal Kemenbud 2026.
- ❌ **Dilarang card rounded dengan border kiri tebal klise.** Gunakan perimeter border halus `rgba(255,255,255,0.08)` atau glassmorphism.
