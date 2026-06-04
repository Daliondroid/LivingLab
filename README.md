# MuDu - Kolaborasi Sampah Organik Jakarta

Landing page dan platform untuk mengelola sampah organik rumah tangga di Jakarta.

## 📁 Struktur Folder

```
LivingLab/
├── index.html                 # Landing page MuDu (BARU)
├── artikelLiterasi/          # Folder untuk artikel literasi
├── assets/                    # Asset internal (jika ada)
├── images/                    # Semua gambar (.png, .jpg) - REORGANISASI
│   ├── MuDu logo.png
│   ├── DLH logo.png
│   ├── dokum1.jpg
│   ├── Gallery*.jpg/png
│   ├── Step*.jpg
│   └── ... (dll)
├── ori/                       # File HTML Original - BACKUP
│   ├── index_original.html
│   ├── artikel.html
│   ├── challenge.html
│   ├── education.html
│   ├── pilot-project.html
│   ├── wastemap.html
│   ├── Pengumpulan_Pilot_Project.html
│   └── index copy.html
├── pages/                     # Folder untuk HTML pages (untuk pengembangan selanjutnya)
├── data/                      # Folder untuk data files
│   └── tps_data.json
├── vercel.json               # Konfigurasi Vercel
└── README.md                 # File dokumentasi ini
```

## 🎨 Landing Page MuDu (Baru)

Landing page yang baru menampilkan:

### Fitur Utama:
1. **Pengenalan MuDu** - Deskripsi lengkap tentang platform
2. **3 Pilar Utama:**
   - 🎓 Fitur Edukasi & Konten Kreatif
   - 🌐 Hub Digital & Manajemen Sampah
   - 🎮 Sistem Gamifikasi & Reward

3. **Target User:**
   - 👷 Petugas RW / LPS
   - 🛡️ DLH (Pengawas)
   - 🏭 Mitra Pengelola
   - 💼 CSR
   - 👨‍👩‍👧‍👦 Warga

4. **Demo Modal** - Modal untuk memilih versi demo dari 5 role berbeda

### Desain:
- ✅ Menggunakan tema dan color palette yang sama (Primary Green: #62a64a, Primary Orange: #ec7c0c)
- ✅ Responsive design (mobile-first)
- ✅ Animasi dan efek visual yang menarik
- ✅ Menggunakan Tailwind CSS
- ✅ Asset yang konsisten

## 🔧 Teknologi

- HTML5
- Tailwind CSS
- Font Awesome Icons
- Google Fonts (Inter)
- Vanilla JavaScript (tanpa framework)

## 📝 Catatan Pengembangan

### File yang dipindahkan:
- Semua gambar (.png, .jpg) → `/images`
- Semua HTML original → `/ori` (sebagai backup)
- JSON data → `/data`

### File-file original tersedia di folder `ori/` jika diperlukan untuk referensi atau rollback

### Next Steps (untuk pengembangan):
1. [ ] Membuat halaman demo untuk Petugas RW
2. [ ] Membuat halaman demo untuk DLH
3. [ ] Membuat halaman demo untuk Mitra Pengelola
4. [ ] Membuat halaman demo untuk CSR
5. [ ] Membuat halaman demo untuk Warga
6. [ ] Update link di HTML pages ke gambar di folder `/images`

## 📧 Informasi

- **Platform:** MuDu (Kolaborasi Sampah Organik Jakarta)
- **Fokus:** Edukasi, Mediasi, Gamifikasi sampah organik rumah tangga
- **Target:** Jakarta Timur (Pilot Project di Gem House)
