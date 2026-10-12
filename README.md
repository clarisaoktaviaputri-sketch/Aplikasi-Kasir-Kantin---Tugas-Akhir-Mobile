# 🍽️ KantinKu - Aplikasi Kasir Kantin

Aplikasi mobile kasir kantin sekolah berbasis **MIT App Inventor** dengan backend **Firebase Realtime Database**.


## 📱 Deskripsi

**KantinKu** adalah aplikasi mobile untuk membantu proses transaksi di kantin sekolah. Aplikasi ini memudahkan kasir untuk:
- Mencatat penjualan secara digital
- Menghitung total belanja otomatis
- Melacak stok dan pendapatan
- Menyimpan riwayat transaksi ke cloud

Dibuat untuk memenuhi **Tugas Akhir Mapel Mobile**.

---

## ✨ Fitur Utama

| Fitur | Deskripsi |
|-------|-----------|
| 🔐 **Login Kasir** | Autentikasi dengan username & password dari Firebase |
| 📋 **Dashboard Menu** | Menampilkan daftar menu kantin dari Firebase |
| 📷 **Scan Barcode** | Scan QR Code / barcode menu pakai kamera HP |
| 🛒 **Keranjang Belanja** | Hitung total belanja otomatis |
| 📍 **GPS Lokasi** | Catat lokasi transaksi (anti-fraud) |
| 💾 **Simpan Transaksi** | Kirim data transaksi ke Firebase |
| 🔄 **Refresh Menu** | Update daftar menu secara real-time |

---

## 🎯 Persyaratan Tugas Terpenuhi

| Syarat | Status | Implementasi |
|--------|--------|--------------|
| **Navigasi minimal 3 layar** | ✅ | Screen1 (Login), Screen2 (Dashboard), Screen3 (Kasir) |
| **Sensor/Hardware** | ✅ | Barcode Scanner (Kamera) + Location Sensor (GPS) |
| **Cloud/Backend** | ✅ | Firebase Realtime Database |

---

## 🛠️ Teknologi yang Digunakan

- **MIT App Inventor** — Platform development berbasis visual block programming
- **Firebase Realtime Database** — Backend cloud untuk menyimpan data
- **Barcode Scanner Component** — Komponen sensor kamera untuk scan barcode
- **Location Sensor Component** — Komponen sensor GPS untuk lokasi
- **FirebaseDB Component** — Komponen koneksi ke Firebase

---

## 🚀 Cara Menggunakan Aplikasi

### 1. Login
- Buka aplikasi **KantinKu**
- Masukkan:
  - **Username**: `kasir1`
  - **Password**: `12345`
- Klik tombol **LOGIN**

### 2. Dashboard
- Lihat **daftar menu** kantin
- Klik **REFRESH MENU** untuk update daftar
- Klik **TRANSAKSI BARU** untuk mulai transaksi

### 3. Transaksi (Kasir)
- Klik **📷 SCAN BARCODE**
- Arahkan kamera ke QR Code / barcode menu
- Menu otomatis masuk ke keranjang
- Total otomatis terhitung
- Isi **Jumlah Bayar**
- Klik **BAYAR** untuk menyimpan transaksi
- Klik **BATAL** untuk reset keranjang

### 4. Cek Transaksi
- Buka **Firebase Console** → **Realtime Database** → node `transaksi`
- Data transaksi tersimpan lengkap dengan waktu & lokasi

---

