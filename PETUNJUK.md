# Nota Digital – Proyek Android

Aplikasi ini membungkus `app/src/main/assets/index.html` (Aplikasi Nota Digital + Pelunasan)
menjadi aplikasi Android. Bekerja offline, data tersimpan otomatis di HP.

## Cara 1 – Android Studio
1. Buka Android Studio → File → Open → pilih folder `NotaDigital`.
2. Tunggu Gradle sync selesai.
3. Build → Build Bundle(s) / APK(s) → Build APK(s).
4. File APK ada di `app/build/outputs/apk/debug/app-debug.apk`. Kirim ke HP dan pasang.

## Cara 2 – Tanpa Android Studio (GitHub Actions)
1. Buat repositori baru di github.com, unggah seluruh isi folder ini (termasuk folder `.github`).
2. Buka tab Actions → tunggu "Build APK" selesai (hijau).
3. Klik hasil run → bagian Artifacts → unduh `NotaDigital-APK` → ekstrak → `app-debug.apk`.

## Memasang di HP
Buka file APK → izinkan "Pasang dari sumber tidak dikenal" jika diminta → Pasang.

## Mengubah isi aplikasi
Edit `app/src/main/assets/index.html`, lalu build ulang.
