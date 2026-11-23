# QR Inspection System — Admin Dashboard UI Scaffold

Kerangka frontend desktop untuk QR Inspection System dengan gaya Industrial Professional.

## Isi
- `index.html` — UI dashboard dan navigasi awal.
- Dashboard Overview memakai angka dan aktivitas **dummy/demo**.
- Menu Asset, QR Code, Checklist, Monitoring, Findings, Reports, Users, Settings masih berupa placeholder UI.

## Jalankan lokal
Buka `index.html` menggunakan browser.

## Deploy GitHub Pages
1. Buat repository baru, misalnya `qr-inspection-admin`.
2. Upload `index.html` ke root repository.
3. Buka Settings → Pages.
4. Pilih Deploy from a branch → `main` → `/ (root)`.
5. Simpan dan tunggu proses deployment.

## Status integrasi
Belum terhubung ke Supabase. Jangan masukkan service-role key ke frontend.
Integrasi berikutnya memakai Supabase URL dan publishable/anon key, dengan RLS tetap aktif.
