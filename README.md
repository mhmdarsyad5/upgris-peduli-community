# UPGRISPeduli Community

UPGRISPeduli Community adalah platform web berbasis Laravel dan React (Inertia.js) untuk kolaborasi komunitas dalam mengelola proyek sosial, donasi, dan aktivitas relawan secara terstruktur dan transparan.

## Fitur Utama

- **Manajemen Proyek Sosial:** Buat, edit, hapus, dan dokumentasikan proyek dengan deskripsi, gambar, status, tanggal mulai, serta jumlah peserta yang dibutuhkan.
- **Dashboard Multi-Role:** Tampilan dashboard berbeda untuk admin, pengelola proyek, donatur, dan relawan.
- **Manajemen Relawan:** Pengguna dapat bergabung atau keluar dari proyek sebagai relawan.
- **Sistem Donasi:** Mendukung donasi dan permintaan bantuan secara langsung melalui platform.
- **Manajemen Peran & Izin:** Menggunakan Spatie Laravel Permission untuk kontrol akses berbasis role (admin, pengelola proyek, relawan, donatur).
- **Autentikasi & Registrasi:** Sistem login, registrasi, dan manajemen profil pengguna.
- **Upload Gambar Proyek:** Dokumentasi visual untuk setiap proyek.
- **Pengujian Otomatis:** Unit test untuk memastikan keamanan dan stabilitas fitur.

## Instalasi

1. **Install dependency backend**
   ```bash
   composer install
   ```

2. **Install dependency frontend**
   ```bash
   npm install
   ```

5. **Copy file environment**
   ```bash
   cp .env.example .env
   ```

4. **Generate key**
   ```bash
   php artisan key:generate
   ```

5. **Migrasi dan seed database**
   ```bash
   php artisan migrate --seed
   ```

6. **Jalankan server**
   ```bash
   php artisan serve
   npm run dev
   ```

## Struktur Folder Penting

- `resources/js/Pages/` — Halaman React (Inertia.js) untuk dashboard, proyek, donasi, profil, dll.
- `resources/js/Components/` — Komponen UI seperti tombol, modal, carousel, dsb.
- `app/Http/Controllers/` — Controller Laravel untuk logika backend.
- `database/seeders/` — Seeder untuk data awal (admin, role, dsb).


Admin:
admin@donasi.com
admin123

User:
user@donasi.com
user123
