# CDR Quick Viewer36

Aplikasi Android ringkas untuk membuka fail .cdr dan cuba memaparkan imej pratonton yang tersimpan di dalamnya. Antara muka menggunakan Bahasa Melayu dan fail diproses secara setempat pada peranti.

## Muat turun APK Android

Setiap kali kod dihantar ke branch main, GitHub Actions akan cuba membina APK debug.

1. Buka tab **Actions** dalam repositori ini.
2. Pilih workflow **Build Android APK** dan buka run yang paling baharu.
3. Di bahagian **Artifacts**, muat turun **CDR-Quick-Viewer36-debug-apk**.
4. Ekstrak ZIP artifak dan pasang fail app-debug.apk pada telefon Android. Telefon mungkin meminta kebenaran memasang aplikasi daripada sumber ini.

APK debug disediakan untuk ujian dan pemasangan terus, bukan keluaran bertandatangan untuk Play Store.

## Cara menggunakan

1. Buka aplikasi dan tekan **Pilih fail CDR**.
2. Pilih fail .cdr daripada storan telefon.
3. Jika imej pratonton boleh dibaca, ia akan dipaparkan. Gunakan **Simpan pratonton** untuk menyimpan imej tersebut.

## Batasan penting

Aplikasi ini ialah **pembaca pratonton**, bukan CorelDRAW dan bukan penukar vektor penuh. Ia mencari imej pratonton yang mungkin tertanam dalam fail CDR. Sesetengah versi atau fail tidak mempunyai pratonton yang serasi, jadi reka bentuk mungkin tidak dipaparkan. Untuk melihat atau menyunting semua objek vektor, gunakan CorelDRAW atau perisian yang menyokong versi fail berkenaan.

## Privasi

Fail CDR dipilih dan diproses pada peranti; aplikasi tidak memuat naiknya secara automatik. Pautan kepada pembaca pihak ketiga dibuka di luar aplikasi dan tertakluk kepada dasar privasi laman tersebut.

## Projek

- app/ — pembungkus Android WebView.
- CDR_Quick_Viewer_App.zip — sumber antara muka web/PWA yang dibungkus bersama aplikasi.
- .github/workflows/android-apk.yml — binaan APK automatik menggunakan GitHub Actions.
