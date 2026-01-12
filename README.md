# 🔐 Password Generator Web

Password Generator Web adalah aplikasi berbasis web yang berfungsi untuk menghasilkan password acak yang kuat dan aman secara **real-time**, langsung di sisi klien (browser), tanpa menyimpan atau mengirim data ke server mana pun.

Project ini dikembangkan oleh **Bhycero Group** dengan tampilan **modern, responsif, premium, dan profesional** menggunakan **Bootstrap 5**.

---

## 🚀 Fitur Utama

- Generate password secara **instan & real-time**
- Pengaturan panjang password (6–50 karakter)
- Opsi karakter:
  - Huruf Besar (A–Z)
  - Huruf Kecil (a–z)
  - Angka (0–9)
  - Simbol khusus
- Tombol **Copy ke Clipboard**
- Notifikasi modern (Toast Bootstrap)
- 100% berjalan di browser (Client-Side)
- Tanpa database & tanpa API eksternal

---

## 🛠️ Teknologi yang Digunakan

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Bootstrap 5
- Bootstrap Icons

---

## 📂 Struktur File Project
password-generator/ 
├── index.html 
├── README.md 
└── LICENSE

---

## ⚙️ Cara Menjalankan Project

### ▶️ Jalankan Secara Lokal
1. Download / clone repository
2. Buka file `index.html` menggunakan browser:
   - Google Chrome
   - Firefox
   - Edge
   - Brave

> Tidak membutuhkan server, database, atau build tools

### 🌐 Hosting (Opsional)
Project ini bisa langsung di-host di:
- GitHub Pages
- Vercel
- Netlify
- Shared Hosting

---

## 🧠 Cara Kerja Aplikasi

### 1️⃣ Input Pengguna
Pengguna menentukan:
- Panjang password
- Jenis karakter (checkbox)

---

### 2️⃣ Penggabungan Karakter
Karakter akan digabung berdasarkan pilihan pengguna:

```javascript
let chars = "";
if (upper) chars += "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
if (lower) chars += "abcdefghijklmnopqrstuvwxyz";
if (numbers) chars += "0123456789";
if (symbols) chars += "!@#$%^&*()_+{}[]<>?";
```

---

© Copyright 2026 By Bhycero Group
