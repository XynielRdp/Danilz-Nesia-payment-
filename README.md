# IRANVESTMENT GOLD - Digital Gold Platform

Platform investasi emas digital berbasis web yang terintegrasi dengan **Firebase Realtime Database**. Website ini memungkinkan pengguna untuk melakukan pendaftaran, login, melihat paket investasi, dan memantau saldo secara real-time.

## 🚀 Fitur Utama
* **Authentication**: Sistem login dan registrasi menggunakan Firebase.
* **Real-time Dashboard**: Saldo user terupdate otomatis tanpa refresh halaman.
* **Investment Packages**: Berbagai pilihan paket investasi (Bronze, Silver, dsb).
* **WhatsApp Live Chat**: Tombol melayang untuk bantuan langsung ke Admin.
* **Mobile Responsive**: Tampilan nyaman dibuka di HP maupun Laptop.

## 🛠️ Teknologi yang Digunakan
* **Frontend**: HTML5, CSS3 (Bootstrap 5), JavaScript.
* **Backend/Database**: Firebase Realtime Database.
* **Hosting**: GitHub Pages.

## ⚙️ Cara Instalasi
1.  Buat repository baru di GitHub.
2.  Upload file `index.html` ke repository tersebut.
3.  Aktifkan **GitHub Pages** melalui menu *Settings* > *Pages*.
4.  Pastikan konfigurasi Firebase di dalam `index.html` sudah sesuai dengan proyek Firebase kamu.

## 📝 Catatan Admin
Untuk mengelola saldo pengguna:
1.  Buka **Firebase Console**.
2.  Pilih menu **Realtime Database**.
3.  Cari data user di bawah folder `users/`.
4.  Ubah nilai pada key `saldo` untuk menambah atau mengurangi saldo user secara instan.

---
Dikembangkan oleh **Daniel (Jaliladm)**.

