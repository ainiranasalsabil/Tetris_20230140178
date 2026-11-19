# Tetris Adventure - Android APK

Project Android WebView untuk menjalankan game Tetris Adventure dalam APK.

## Cara build melalui GitHub
1. Ekstrak ZIP ini.
2. Upload seluruh isi folder hasil ekstrak ke repository GitHub (termasuk folder `.github` dan `AiniRanaAndroid`).
3. Buka tab **Actions**.
4. Pilih workflow **Build Android APK** lalu klik **Run workflow** (atau tunggu build otomatis setelah push ke `main`).
5. Setelah selesai, buka hasil workflow dan unduh artifact **TetrisAdventure-APK**.
6. Ekstrak ZIP artifact dan ambil file `app-debug.apk`.

Game menggunakan p5.js dari CDN, sehingga koneksi internet diperlukan saat bermain.
