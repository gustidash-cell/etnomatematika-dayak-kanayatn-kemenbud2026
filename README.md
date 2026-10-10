# Etnomatematika Siklus Padi Dayak Kanayatn di Landak: Eksplorasi Pengetahuan Tradisional dan Ritus Pertanian

[![Kemenbud RI 2026](https://img.shields.io/badge/Program-Dana%20Abadi%20Kebudayaan%202026-orange.svg)](https://kebudayaan.kemdikbud.go.id/)
[![Kategori](https://img.shields.io/badge/Kategori-Karya%20Kreatif%20Inovatif%20(Layanan%20Media)-blue.svg)]()
[![Lokasi](https://img.shields.io/badge/Lokus-Rumah%20Radakng%20Saham%2C%20Landak-green.svg)]()
[![Design System](https://img.shields.io/badge/UI%2FUX-OpenDesign%20%C3%97%20Pro%20Max-gold.svg)](./DESIGN.md)

Repository resmi operasional lapangan, alur pengumpulan data etnografis, dan paket instrumen pendukung untuk proyek penelitian yang didanai oleh **Program Pemanfaatan Hasil Kelola Dana Abadi Kebudayaan (Dana Indonesiana / Kementerian Kebudayaan Republik Indonesia) Tahun 2026**.

* **Ketua Tim Peneliti:** Dr. Siti Suprihatiningsih, M.Pd.
* **Lokus Penelitian:** Rumah Radakng Saham, Desa Saham, Kecamatan Sengah Temila, Kabupaten Landak, Kalimantan Barat.
* **Proposal Resmi Terverifikasi:** [`Proposal.pdf`](./Proposal.pdf)

---

## 🌟 Fitur Utama Repository & Portal Interaktif

1. **Portal Web Interaktif (`index.html`):**
   * Panduan alur pengumpulan data 6 fase dengan visualisasi *stepper* interaktif.
   * Matriks 6 aktivitas universal matematis Alan J. Bishop (1988) (*Counting, Locating, Measuring, Designing, Playing, Explaining*).
   * Hub unduhan langsung 8 dokumen Microsoft Word (`.docx`) instrumen lapangan.
   * **Kalkulator Metrologi Pribumi Dayak:** Konversi instan satuan lokal (*Solok, Gantang, Kaleng, Depa, Jengkal, Langkah, Tumpak*) ke standar metrik internasional (SI).
   * **Glosarium Bahasa & Konsep Budaya Kanayatn:** Pencarian interaktif istilah agrikultur padi ladang (*nguma*).
   * **Checklist Kesiapan Lapangan:** Dilengkapi bilah progres dan penyimpanan otomatis di `localStorage`.
   * **Dukungan Cetak PDF Bersih (`@media print`):** Siap diekspor menjadi buku panduan saku lapangan hanya dengan menekan tombol Cetak PDF.

2. **Paket 8 Instrumen Lapangan Siap Cetak (`Instrumen Pendukung/`):**
   * `INST-01-ETNO`: Pedoman Wawancara Mendalam Semi-Terstruktur (Framework Bishop 1988).
   * `INST-02-ETNO`: Lembar Observasi Etnografis Partisipatif Siklus Padi (*Nguma* 9 Tahapan).
   * `INST-03-ETNO`: Lembar Inventarisasi Metrologi Tradisional, Morfometri, & Geometri Artefak.
   * `INST-04-ETNO`: Panduan FGD Terstratifikasi Usia & Protokol Validasi Komunitas (*Member Checking* Bulan 8).
   * `INST-05-ETNO`: Protokol Etika Adat & Surat Persetujuan Informan (FPIC) Dwibahasa (Indonesia - Dayak Kanayatn).
   * `INST-06-ETNO`: Lembar Log Perekaman Audiovisual 4K & Kurasi Metadata Arsip Digital OPK Kemenbud.
   * `INST-07-ETNO`: Jurnal Refleksi Harian Lapangan Peneliti (*Fieldwork Diary & Emic-Etic Memo*).
   * `KATALOG-PANDUAN`: Katalog Induk & Standar Operasional Prosedur (SOP) 10 Bulan Riset.

---

## 🧭 Alur 6 Fase Pengumpulan Data

```
┌────────────────────────────────────────────────────────┐
│ FASE 1: PERSIAPAN ADMINISTRASI & IZIN ADAT (BULAN 1)   │
│ Izin Kesbangpol/Dinasbud, Sowan DAD, Rekrut Asisten    │
└────────────────────────────────────────────────────────┘
                           │
                           ▼
┌────────────────────────────────────────────────────────┐
│ FASE 2: PRA-SURVEI & KALIBRASI KALENDER (BULAN 2)      │
│ Pemetaan 15 Informan, Cek Bintang Karang/Tiga, Uji Coba│
└────────────────────────────────────────────────────────┘
                           │
                           ▼
┌────────────────────────────────────────────────────────┐
│ FASE 3: GELOMBANG I - PERSIAPAN & MENUGAL (BULAN 3-4)  │
│ Observasi Ladang, Hitungan Benih Tugal, Video 4K Sakral│
└────────────────────────────────────────────────────────┘
                           │
                           ▼
┌────────────────────────────────────────────────────────┐
│ FASE 4: GELOMBANG II - PANEN & BABARI (BULAN 5-6)      │
│ Anai-anai, Lumbung Dango, 3 Sesi FGD Stratifikasi Usia │
└────────────────────────────────────────────────────────┘
                           │
                           ▼
┌────────────────────────────────────────────────────────┐
│ FASE 5: TRIANGULASI & VALIDASI ADAT (BULAN 7-8)        │
│ Koding Tematik & Sidang Member Checking di Radakng     │
└────────────────────────────────────────────────────────┘
                           │
                           ▼
┌────────────────────────────────────────────────────────┐
│ FASE 6: FINALISASI 7 LUARAN & SEMINAR (BULAN 9-10)     │
│ Buku OPK-CB, Jurnal SINTA, Video 15-20 Menit, HKI      │
└────────────────────────────────────────────────────────┘
```

---

## 📂 Struktur Berkas Repository

```
d:\Penelitian 2026\Kemenbud\
├── index.html                   # Portal panduan interaktif UI/UX Pro Max
├── DESIGN.md                    # Kontrak token desain sistem OpenDesign
├── Proposal.pdf                 # Dokumen resmi proposal yang didanai Kemenbud 2026
├── README.md                    # Dokumentasi utama proyek
├── .gitignore                   # Konfigurasi filter berkas Git
└── Instrumen Pendukung/         # Paket dokumen instrumen (.docx & .md)
    ├── Instrumen_01_Pedoman_Wawancara_Mendalam_Bishop.docx
    ├── Instrumen_02_Lembar_Observasi_Etnografis_Siklus_Padi.docx
    ├── Instrumen_03_Inventarisasi_Metrologi_dan_Geometri_Artefak.docx
    ├── Instrumen_04_Panduan_FGD_dan_Validasi_Komunitas.docx
    ├── Instrumen_05_Protokol_Etika_Adat_dan_FPIC_Dwibahasa.docx
    ├── Instrumen_06_Logsheet_Audiovisual_dan_Kurasi_Arsip_Digital.docx
    ├── Instrumen_07_Jurnal_Refleksi_Harian_Etnografi.docx
    ├── Katalog_dan_Panduan_Operasional_Instrumen.docx
    └── README_Panduan_Penggunaan_Instrumen.md
```

---

## 🚀 Cara Menjalankan & Menggunakan

1. **Membuka Portal Interaktif di Peramban:**
   * Cukup klik ganda berkas `index.html` atau buka melalui browser web (Chrome, Edge, Firefox).
   * Seluruh fungsionalitas (kalkulator, filter, glosarium, checklist) berjalan secara mandiri (*self-contained*) tanpa membutuhkan instalasi server Node.js atau Apache.

2. **Mencetak Panduan Menjadi PDF:**
   * Buka `index.html` di peramban, lalu klik tombol **"Cetak PDF"** di pojok kanan atas (atau tekan `Ctrl + P`).
   * Desain telah dioptimalkan khusus cetak (`@media print`) dengan menyembunyikan elemen navigasi dan mempertahankan keterbacaan teks berkontras tinggi.

3. **Mencetak Formulir Instrumen:**
   * Buka folder `Instrumen Pendukung/` dan cetak dokumen `.docx` sesuai kebutuhan kuota narasumber (misal: 20 rangkap untuk Form FPIC INST-05).

---

## 👥 Tim Peneliti & Kepanitiaan Inti
* **Ketua Peneliti:** Dr. Siti Suprihatiningsih, M.Pd.
* **Pelindung & Penasihat:** Siskariyanti, M.Pd. & Teodora Mika, S.Pd.
* **Penanggung Jawab & Ketua Panitia:** Thomas, S.Pd. & Kurniawan, ST.
* **Seksi Kajian Etnomatematika:** Petrus Yanson, ST.
* **Seksi Kemitraan Adat & Narasumber:** Adira, S.Pd.
* **Seksi Dokumentasi & Publikasi:** Yeriko, S.Pd.
