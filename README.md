# SatSet ⚡ — versi web

**Semua urusan file, sat-set.** Semua alat berjalan langsung di HP/laptop pengguna, tanpa server. Cukup dipasang gratis di GitHub Pages.

## Isi
| File | Fungsi |
|---|---|
| `index.html` | Seluruh aplikasi |
| `manifest.webmanifest`, `icon-*.png` | Ikon & data untuk "Tambah ke Layar Utama" di iPhone |
| `u2netp.onnx` | Model AI kecil untuk Hapus Background (±4,6 MB) |

## Fitur
- **Unduh:** panduan download video/MP3 lewat Shortcut a-Shell + SW-DLT (berjalan di iPhone), ubah MP4 → MP3
- **Gambar:** kompres, ubah format (JPG/JPEG/PNG/WEBP/BMP/ICO/PDF), perbesar resolusi, ubah ukuran, hapus background (latar transparan/putih/merah/biru), foto grid & kolase, foto ke PDF
- **Dokumen:** edit PDF, edit TXT, TXT → PDF/Word, PDF → TXT
- **PDF:** edit, gabung, pisah/ambil halaman, kompres, putar, hapus halaman, nomor halaman, watermark, PDF ↔ gambar
- **Alat:** penghitung kata, ubah huruf, QR code, tanda tangan digital, kalkulator IPK, pembuat password

## Pasang di GitHub Pages
1. Buat repo baru (Public), upload semua file ini ke halaman utama repo.
2. Settings → Pages → Source: **Deploy from a branch** → Branch: **main**, folder **/ (root)** → Save.
3. Tunggu 1–2 menit, buka `https://USERNAME.github.io/NAMA-REPO/`.
4. Domain sendiri (opsional): Settings → Pages → Custom domain, lalu tambahkan CNAME di DNS domain ke `USERNAME.github.io`.

Komponen pembantu (pdf-lib, pdf.js, JSZip, lamejs, onnxruntime-web, qrcode.js) dimuat dari CDN saat alatnya dipakai.
