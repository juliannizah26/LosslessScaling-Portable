# Lossless Scaling Portable

![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Python](https://img.shields.io/badge/Python-3.7+-green)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Portable-brightgreen)
![Version](https://img.shields.io/badge/Version-v1.0.0-brightgreen)

## 📦 Yang Disertakan
- `LSPortable.exe` - Launcher utama yang dapat dijalankan
- `Backup-Settings.bat` - Utilitas backup pengaturan
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
   - Mengatur registry Steam
   - Menyalin pengaturan Anda
   - Menjalankan Lossless Scaling
   - Meminimalkan jendela

### Penggunaan Sehari-hari:
- **Klik dua kali** `LSPortable.exe` untuk menjalankan
- **Atau** Klik kanan → "Run as administrator" untuk fitur lengkap

## 💾 Menyimpan Pengaturan Anda

Setelah melakukan perubahan di Lossless Scaling:
1. **Tutup** Lossless Scaling
2. **Klik dua kali** `Backup-Settings.bat`
3. Pengaturan Anda sekarang tersimpan di folder portabel!

## 📁 Struktur Folder
```
LosslessScaling-Portable/
├── LSPortable.exe           ← Launcher utama
├── Backup-Settings.bat      ← Simpan pengaturan kembali
├── Data/
│   └── Settings.xml        ← File pengaturan Anda
└── LsApp/
    └── LosslessScaling.exe ← Aplikasi utama
```

## ⚙️ Fitur
- ✅ **Pengaturan Portabel** - Simpan konfigurasi di mana saja
- ✅ **Interface Bersih** - Output profesional dengan timestamp
- ✅ **Kontrol Jendela Otomatis** - Meminimalkan secara otomatis
- ✅ **Backup Pengaturan** - Simpan perubahan kembali ke folder portabel
- ✅ **Manajemen Proses** - Menangani konflik secara otomatis

## 🔧 Cara Kerja

### Peluncuran Normal:
1. Menyalin pengaturan Anda ke Windows AppData
2. Mengatur entri registry Steam
3. Menghentikan Lossless Scaling yang sedang berjalan
4. Menjalankan aplikasi
5. Meminimalkan jendela

### Backup Pengaturan:
1. Menyalin pengaturan dari Windows AppData
2. Menyimpannya kembali ke folder portabel Anda
3. Siap untuk peluncuran berikutnya!

## 🛡️ Hak Administrator
**Mengapa diperlukan?**
- Operasi registry untuk kompatibilitas Steam
- Manajemen proses (menghentikan aplikasi yang berjalan)
- Operasi file di direktori sistem

**Aman?** Ya! Launcher hanya:
- Menambahkan Lossless Scaling ke registry Steam
- Mengelola proses Lossless Scaling
- Menyalin file pengaturan

## 📋 Pemecahan Masalah

### "Settings.xml not found"
- Pastikan file `Data/Settings.xml` ada
- Coba jalankan `Backup-Settings.bat` terlebih dahulu

### "Failed to launch"
- Periksa apakah `LsApp/LosslessScaling.exe` ada
- Jalankan sebagai administrator

### "Registry import failed"
- Harus dijalankan sebagai administrator untuk integrasi Steam

## 🎮 Tips Penggunaan
1. **Kustomisasi Dulu**: Jalankan sekali, atur Lossless Scaling sesuai keinginan
2. **Backup Pengaturan**: Gunakan `Backup-Settings.bat` untuk menyimpan konfigurasi
3. **Pindah Ke Mana Saja**: Seluruh folder portabel - pindahkan ke mana saja!

### 🏪 Tips Khusus Warnet:
- **Master Setup**: Atur setting optimal, atau game yang paling sering dimainkan. jika sudah lalu jalankan Backup-Settings.bat
- **Customer Friendly**: User tinggal double-click, langsung jalan
- **No Installation**: Tidak perlu install/uninstall, langsung pakai

## 👨‍💻 Pengembang & Dukungan
- **Aplikasi portable ini gratis jangan di perjual belikan**
- **Jangan serta merta menghilangkan credits**
- **Apresiasi Pengembang**: Dukung melalui [Saweria](https://saweria.co/jndev26)
- **GitHub**: https://github.com/juliannizah26/LosslessScaling-Portable
- **Issues**: Laporkan bug melalui GitHub Issues

---

**Copyright (c) JulianNizah 2025.**

> 💡 **Tips Pro**: Setelah mengonfigurasi Lossless Scaling dengan sempurna, jalankan `Backup-Settings.bat` untuk menyimpan pengaturan. Agar PC Client mana pun memiliki konfigurasi yang sama persis!
