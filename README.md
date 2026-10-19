# KandisKita — Direktori UMKM Kecamatan Kandis

Website direktori UMKM Kecamatan Kandis, Kab. Siak, Riau. Satu file `index.html` (statis, tanpa build), data 30 UMKM tertanam di dalamnya; `umkm-data.json` adalah salinan data yang sama untuk arsip/edit.

## Deploy: GitHub + Cloudflare Pages
- Repo GitHub ini terhubung ke Cloudflare Pages (production branch: `main`).
- Setiap push ke `main` = deploy otomatis. Tidak ada build command; output directory = root (`/`).
- `.assetsignore` WAJIB ada (mengecualikan `.git` dari aset, pelajaran dari deploy Oendang).

## Mengedit data usaha
Edit array `UMKM`, peta `TAG`, dan `PROMO` di `index.html`, lalu sesuaikan `umkm-data.json`. Status listing riset: "belum diklaim" — nomor dari sumber publik, diverifikasi saat pemilik klaim via WhatsApp admin (0822-8350-6764).

Dikelola oleh Lapak Kreatif, Kandis.
