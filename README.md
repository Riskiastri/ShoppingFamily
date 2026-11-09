# Jesus Saves Today - Firebase Real-Time Cloud Bio Link & Multi-Affiliate Hub

Sistem website bio-link & multi-affiliate e-commerce mewah yang terintegrasi dengan **Firebase Real-Time Cloud Firestore Database**.

## Keunggulan Firebase Real-Time Sync:
Begitu Anda menambah atau mengedit produk di Admin (baik dari Laptop maupun HP), **detik itu juga** tampilan di HP pengunjung seluruh dunia langsung ter-update otomatis secara real-time tanpa perlu refresh atau export/import JSON!

---

## Cara Mengaktifkan Firebase Real-Time Database (100% Gratis):

### Langkah 1: Buat Project Firebase Gratis
1. Buka [console.firebase.google.com](https://console.firebase.google.com) dan login dengan akun Google Anda.
2. Klik **Add project** (Tambah Proyek), beri nama proyek Anda (misal: `jesus-saves-today`), lalu klik **Continue** sampai selesai.

### Langkah 2: Buat Database Firestore
1. Di menu sebelah kiri, klik **Build** -> **Firestore Database**.
2. Klik tombol **Create database**.
3. Pilih lokasi database (default ok) lalu klik **Next**.
4. Pilih **Start in test mode** (Mode Pengujian) agar izin baca/tulis terbuka, lalu klik **Create**.

### Langkah 3: Ambil Kode Firebase Config & Tempel di Website Admin
1. Di halaman utama Firebase console, klik ikon **Web `</>`** untuk menambahkan aplikasi web.
2. Beri nama aplikasi (misal: `Bio Link`), lalu klik **Register app**.
3. Salin/copy objek `const firebaseConfig = { ... };` yang diberikan.
4. Buka website Vercel Anda, masuk ke **Admin Rahasia** (klik logo header 15 kali cepat).
5. Pada kotak **"Firebase Real-Time Database Setup"**, paste/tempel objek JSON `firebaseConfig` tersebut, lalu klik **Connect Firebase Cloud**.
6. **SELESAI!** Indikator di navbar akan berubah hijau (**Firebase Real-Time Active**). Sekarang setiap perubahan produk atau marketplace di laptop akan langsung sinkron otomatis ke HP Anda & seluruh dunia!
