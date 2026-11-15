# Proyek Kelompok TBP
Dokumentasi pengujian otomatis CI menggunakan GitHub Actions.

## Cara Menjalankan Pengujian Otomatis (CI)
1. Pastikan berkas `README.md` tersedia pada direktori utama proyek.
2. Setiap perintah `push` atau `pull_request` ke cabang `main` akan memicu alur kerja `.github/workflows/ci.yml`.
3. Sistem akan otomatis menjalankan pemeriksaan berkas dan pengujian unit dengan status keluaran sukses (`exit 0`).
