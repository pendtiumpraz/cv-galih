---
title: Modules
tags:
  - cv-galih
  - modules
created: 2026-06-07
---

# Modules

## Struktur Berkas

```
cv-galih/
├── index.html                     # Halaman utama CV interaktif
├── cv-clean.html                  # Versi CV bersih (tanpa animasi berat)
├── cv-print.html                  # Versi khusus cetak
├── Galih_Prasetyo_AI_Engineer_CV.pdf  # CV versi PDF statis
├── foto.jpeg                      # Foto profil
├── jobdesk yang dilamar.txt       # Acuan job description yang dilamar
├── linkedin saya.txt              # Konten LinkedIn
├── Portfolio vercel.txt           # Daftar proyek portfolio
├── portfolio github.txt           # Tautan GitHub portfolio
└── LICENSE                        # Lisensi MIT
```

## Bagian dalam index.html

| Bagian | Deskripsi |
|--------|-----------|
| `<head>` | Metadata, Google Fonts, Tailwind CDN, html2pdf.js, style inline |
| **Header** | Nama, gelar, tautan sosial dengan ikon |
| **Ringkasan** | Profil AI Engineer |
| **Proyek** | Grid kartu proyek (20+) |
| **Pengalaman** | Timeline karier |
| **Pendidikan** | Riwayat pendidikan formal |
| **Sertifikasi** | Sertifikat dan pelatihan |
| **Footer** | Hak cipta |
| `<script>` | Animasi scroll, inisialisasi PDF export |

## Alur Ekspor PDF

1. Klik tombol "Download CV"
2. `html2pdf.js` menangkap elemen utama halaman
3. Render ulang sebagai PDF
4. Unduh otomatis ke perangkat pengguna

## Lihat Juga

- [[architecture|Arsitektur]]
- [[features|Fitur]]
- [[tech-stack|Tech Stack]]
