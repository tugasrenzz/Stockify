# Stockify — Sistem Inventaris Ruangan Komputer

Aplikasi inventaris untuk Lab Komputer, dibuat dengan React Native + Expo.

## Fitur
- Icon Stockify terbaru diterapkan pada PWA dan asset aplikasi.
- Navbar menampilkan identitas `@david&rendi`.
- Splash screen HTML-like native dengan logo, nama aplikasi, pembuat, dan loading.
- Dashboard: total barang, kondisi baik, barang rusak.
- Tambah, edit, hapus inventaris.
- Konfirmasi sebelum hapus.
- Pencarian nama/kode.
- Filter ruangan dan kondisi.
- Dark mode.
- Data tersimpan lokal menggunakan AsyncStorage pada APK.
- Tampilan responsif Android.

## Data
Field:
- Nama Barang
- Kode Inventaris
- Nama Ruangan
- Jumlah Barang
- Kondisi: Baik / Rusak Ringan / Rusak Berat

## Build APK
Di Windows:
1. `npm install`
2. `npm install -g eas-cli`
3. `eas login`
4. `eas build:configure`
5. `eas build -p android --profile preview`

Profil `preview` sudah diset agar menghasilkan APK.

## Catatan PWA
Folder `pwa/` berisi versi HTML/CSS/JS yang memenuhi struktur PWA dan menggunakan LocalStorage, manifest.json, serta service-worker.js. Versi ini dapat dijalankan dengan Live Server.
