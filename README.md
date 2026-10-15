# Kalkulator Potong Material - Android Studio

1. Ekstrak zip, lalu di Android Studio pilih File > Open dan pilih folder KalkulatorPotong.
2. Tunggu Gradle Sync selesai (butuh internet pertama kali). Kalau diminta, setujui update Gradle / Android Gradle Plugin.
3. Colok HP (USB debugging aktif) atau pakai emulator, lalu klik Run.
4. Untuk APK: Build > Build Bundle(s) / APK(s) > Build APK(s). Hasil: app/build/outputs/apk/debug/app-debug.apk

Export Excel disimpan ke folder Download di HP.
Export .xlsx memakai library SheetJS. Supaya jalan tanpa internet, taruh file xlsx.full.min.js
(dari https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js) di app/src/main/assets/.
Tanpa file itu, aplikasi memuatnya dari internet; kalau offline, export berupa .csv.
Halaman aplikasi ada di app/src/main/assets/index.html.
