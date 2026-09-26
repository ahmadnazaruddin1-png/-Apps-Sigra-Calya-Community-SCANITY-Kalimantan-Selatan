# Cara mendapatkan APK SCANITY Kalsel tanpa Android Studio

Project ini sudah dilengkapi GitHub Actions untuk membangun APK secara otomatis di server GitHub.

## Langkah
1. Buat akun/login di GitHub.
2. Buat repository baru, misalnya `SCANITY-Kalsel-Android`.
3. Upload seluruh isi folder project ini ke repository (termasuk folder `.github`).
4. Buka tab **Actions**.
5. Pilih workflow **Build SCANITY Kalsel APK**.
6. Tekan **Run workflow**.
7. Tunggu sampai proses selesai.
8. Buka hasil workflow yang berhasil dan bagian **Artifacts**.
9. Download `SCANITY-Kalsel-v2.0-APK.zip`.
10. Di HP Android, ekstrak ZIP tersebut dan instal `app-debug.apk`.

APK debug ini dapat dipasang langsung untuk pengujian. Android mungkin meminta izin **Install unknown apps** untuk browser/file manager yang digunakan.

Login Admin awal aplikasi:
- Username: `admin`
- Password: `scanity2026`

Setelah instalasi, segera ganti password Admin.
