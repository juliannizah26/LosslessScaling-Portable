# Lossless Scaling Portable

<img width="1474" height="389" alt="9d1c1ae9fd5d5aa35a0d104650e62ff9" src="https://github.com/user-attachments/assets/1941834f-d3d2-465e-882b-6ddc5481890e" />

![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Python](https://img.shields.io/badge/Python-3.7+-green)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Portable-brightgreen)
![Version](https://img.shields.io/badge/Version-v1.0.0-brightgreen)

## 📦 Yang Disertakan
- `LSPortable.exe` - Launcher utama yang dapat dijalankan
- `Data/Settings.xml` - Konfigurasi portabel Anda
- `LsApp/` - File-file aplikasi Lossless Scaling

## 🎮 Cocok untuk Warnet!
- ✅ **Portable 100%** - Tidak perlu install di sistem
- ✅ **Tidak Ganggu Sistem** - Semua file tetap di folder

## 🚀 Memulai dengan Cepat

### Pengaturan Pertama Kali:
1. **Ekstrak** semua file ke folder pilihan Anda
2. **Klik kanan** pada `LSPortable.exe` → **"Run as administrator"**
3. Launcher akan secara otomatis:
   - Mengatur registry Steam untuk Lossless Scaling
   - Mengelola pengaturan portabel Anda (tidak perlu salin manual)
   - Menjalankan Lossless Scaling (v3.2.1)

### Penggunaan Sehari-hari:
- **Klik dua kali** `LSPortable.exe` untuk menjalankan
- **Atau** Klik kanan → "Run as administrator" untuk fitur lengkap

## 📁 Struktur Folder
```
LosslessScaling-Portable/
├── LSPortable.exe           ← Launcher utama
├── Data/
│   └── Settings.xml        ← Pengaturan portabel Anda (dikelola otomatis)
└── LsApp/
    └── LosslessScaling.exe ← Aplikasi utama (v3.2.1)
```

## ⚙️ Fitur
- ✅ **Pengaturan Portabel Sebenarnya** - Settings.xml disinkronkan secara otomatis antara Data dan AppData
- ✅ **Output Profesional** - Log yang bersih dan informatif
- ✅ **Manajemen Proses** - Menangani konflik secara otomatis

## 🔧 Cara Kerja

### Peluncuran Normal:
1. Memastikan `Settings.xml` ada dan terhubung antara Data dan AppData (symlink/salin otomatis)
2. Mengatur registry Steam untuk kompatibilitas
3. Menghentikan instance Lossless Scaling yang sedang berjalan
4. Menjalankan aplikasi

## 🛡️ Hak Administrator
**Mengapa diperlukan?**
- Operasi registry untuk kompatibilitas Steam
- Manajemen proses (menghentikan aplikasi yang berjalan)
- Operasi file di direktori sistem

**Aman?** Ya! Launcher hanya:
- Menambahkan Lossless Scaling ke registry Steam
- Mengelola proses Lossless Scaling
- Menautkan file pengaturan Anda secara otomatis

## 📋 Pemecahan Masalah

### "Settings.xml not found"
- Launcher sekarang secara otomatis menyalin atau menautkan pengaturan Anda. Cukup jalankan peluncur; salin manual tidak diperlukan.

### "Failed to launch"
- Periksa apakah `LsApp/LosslessScaling.exe` ada
- Jalankan sebagai administrator

### "Registry import failed"
- Harus dijalankan sebagai administrator untuk integrasi Steam

## 🎮 Tips Penggunaan
1. **Kustomisasi Dulu**: Jalankan sekali, atur Lossless Scaling sesuai keinginan
2. **Pindah Ke Mana Saja**: Seluruh folder portabel - pindahkan ke mana saja!

### 🏪 Tips Khusus Warnet:
- **Master Setup**: Atur setting optimal, atau game yang paling sering dimainkan.
- **Customer Friendly**: User tinggal double-click, langsung jalan
- **No Installation**: Tidak perlu install/uninstall, langsung pakai

## 📞 Dukungan
- **GitHub**: https://github.com/JulianNizah/LosslessScaling-Portable
- **Issues**: Laporkan bug melalui GitHub Issues

---

**Copyright (c) JulianNizah 2025. Hak cipta dilindungi.**
