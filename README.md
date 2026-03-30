# Smart Door Lock dengan Pengenalan Wajah Berbasis Raspberry Pi

Aplikasi pengenalan wajah (*face recognition*) untuk membuka servo penahan pintu otomatis yang dioperasikan menggunakan Raspberry Pi. Proyek ini dibangun dengan bahasa pemrograman **Python** dan memanfaatkan *library* **OpenCV** untuk pemrosesan visi komputer. Algoritma pengenalan wajah utama yang digunakan dalam sistem ini adalah **Local Binary Pattern Histogram (LBPH)**.

---

## 📹 Video Demo Aplikasi

Saksikan bagaimana aplikasi ini bekerja secara langsung:
[![Video Demo](https://img.youtube.com/vi/lZdOjA3wDoU/0.jpg)](https://www.youtube.com/watch?v=lZdOjA3wDoU&t=8s)
*(Klik gambar atau link di atas untuk menonton video di YouTube)*

---

## 🛠️ Persiapan Perangkat Keras (Hardware)

Sistem ini menggunakan **Kamera Modul V2** dari Raspberry Pi. Berikut adalah langkah-langkah untuk menghubungkan dan mengaktifkan kamera pada Raspberry Pi Anda:

1. Cari *port* kamera pada board Raspberry Pi, lalu hubungkan kabel *ribbon* kamera dengan benar.
2. Nyalakan (*start up*) Raspberry Pi tersebut.
3. Buka **Configuration Tool** Raspberry Pi dari menu utama (atau jalankan perintah `sudo raspi-config` di terminal).
4. Masuk ke menu antarmuka (*Interface Options*) dan pastikan fitur **Camera** telah diaktifkan (*Enabled*).
5. Setelah itu, *reboot* (hidupkan ulang) Raspberry Pi Anda untuk menerapkan pengaturan.

---

## 💻 Persiapan Perangkat Lunak (Software)

### Instalasi OpenCV
OpenCV adalah *library open source* yang sangat populer untuk kebutuhan *computer vision*. Pada proyek ini, OpenCV digunakan secara ekstensif untuk menjalankan algoritma pengenalan wajah LBPH.

* **Dokumentasi Resmi OpenCV:** [https://opencv.org/about/](https://opencv.org/about/)
* **Panduan Instalasi OpenCV:** Untuk langkah-langkah detail mengenai cara menginstal OpenCV di Raspberry Pi, silakan unduh dan lihat panduan presentasi pada [tautan OneDrive berikut](https://onedrive.live.com/view.aspx?resid=2AAE05B692B45603!149547&ithint=file%2cpptx&authkey=!AMJoTWk2pvH73f8).

---

## 🚀 Teknologi yang Digunakan

* **Bahasa Pemrograman:** Python
* **Hardware:** Raspberry Pi, Kamera Modul V2, Motor Servo
* **Computer Vision Library:** OpenCV
* **Algoritma Pengenalan Wajah:** Local Binary Pattern Histogram (LBPH)
