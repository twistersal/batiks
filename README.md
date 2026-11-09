# BatikFit — GitHub Pages PWA

Paket ini siap diunggah ke repository GitHub Pages.

## Upload

1. Buat repository baru di GitHub.
2. Upload seluruh isi folder ini ke root repository.
3. Pastikan file `index.html` berada langsung di root, bukan di dalam folder tambahan.
4. Buka **Settings → Pages**.
5. Pilih **Deploy from a branch**, branch `main`, folder `/root`.
6. Tunggu deployment selesai.

## Instal di Android

Buka URL GitHub Pages menggunakan Chrome Android, tunggu sampai selesai dimuat, lalu pilih menu tiga titik → **Install app** atau **Add to Home screen**.

## Instal di iPhone

Buka URL menggunakan Safari → Share → **Add to Home Screen**.

## Shift yang tersedia

Paket ini mencakup shift P (09:00–17:00), FULL (09:00–22:00), LK2 (09:00–19:00), 11 (11:00–19:00), 12 (12:00–20:00), 12L (12:00–22:00), S (14:00–22:00), dan OFF.

## Catatan sinkronisasi

Versi ini menyimpan data lokal di browser melalui localStorage. Artinya data desktop dan mobile belum otomatis sama. Untuk sinkronisasi antarperangkat, tambahkan login dan database online seperti Supabase atau Firebase.

## Update berikutnya

Jika mengubah file aplikasi, naikkan nilai `CACHE_NAME` di `service-worker.js`, misalnya dari `batikfit-github-v3` menjadi `batikfit-github-v3`, agar perangkat mengambil versi terbaru.
