# 🏋️‍♂️ Tracker Latihan Harian

Projek ini adalah laman web statik untuk membantu anda merancak dan mengesan kemajuan latihan harian selama **8 minggu**, tanpa keperluan gym atau alatan khas. Ia dirangka dengan:

- Kalender interaktif
- Dialog modal untuk pilih latihan harian
- Panduan ringkas setiap jenis latihan
- Penyimpanan data secara automatik menggunakan `localStorage`
- Eksport data sebagai fail CSV
- Paparan statistik mingguan
- Responsif & boleh digunakan di telefon pintar

---

## 🎯 Matlamat Projek

Membantu pengguna:
- Menyusun jadual latihan rumah selama 2 bulan
- Mengelakkan melompat (berdasarkan kekangan fizikal)
- Hanya gunakan berat badan dan objek biasa di rumah
- Mencapai bentuk badan yang lebih sihat dan ideal seperti CR7

---

## ✅ Ciri-ciri Utama

| Ciri | Penerangan |
|------|------------|
| 📅 Kalender Bulanan | Paparan tarikh bulan semasa untuk pilih hari latihan |
| 💬 Modal Dialog | Untuk pilih latihan dan lihat info/panduan harian |
| 🌈 Warna Minggu Berbeza | Setiap minggu mempunyai warna unik untuk visualisasi |
| 💾 Simpan ke localStorage | Data tidak hilang apabila refresh atau tutup browser |
| 📄 Eksport CSV | Simpan data latihan sebagai fail CSV |
| 🔁 Butang Reset | Padam semua rekod dengan sekali klik |
| 📊 Statistik Mingguan | Tunjukkan jumlah hari latihan setiap 2 minggu |

---

## 🧩 Struktur Fail

```
tracker/
├── index.html        # Laman utama dengan Tailwind CSS dan JavaScript
└── README.md         # Dokumentasi penggunaan
```

> Anda hanya perlukan satu fail HTML sahaja — tiada backend, database atau library tambahan diperlukan.

---

## 🛠️ Cara Gunakan

1. **Muat turun atau salin kod HTML**
   - Simpan sebagai `index.html` atau nama fail lain yang sesuai
2. **Buka dengan browser**
   - Anda boleh buka fail tersebut secara langsung tanpa perlu internet
3. **Klik pada tarikh**
   - Pilih latihan harian dari dropdown
   - Baca panduan ringkas untuk latihan tersebut
   - Klik "Simpan"
4. **Lihat kemajuan mingguan**
   - Bahagian atas kalender akan paparkan jumlah hari latihan setiap 2 minggu
5. **Eksport atau reset data**
   - Guna butang “Eksport CSV” untuk simpan data
   - Atau guna “Reset Data” untuk mula semula

---

## 📦 Teknologi Digunakan

- **HTML5** – struktur laman
- **Tailwind CSS** – reka bentuk minimal dan responsif
- **JavaScript (Vanilla)** – logik interaksi dan penyimpanan
- **LocalStorage** – simpan data secara sementara
- **CSV Export** – eksport data ke fail teks

---

## 📝 Nota Penting

- Projek ini **tidak memerlukan internet** selepas muat pertama kali
- Data disimpan dalam **localStorage browser**, jadi pastikan anda tidak membersihkan cache jika tidak mahu data hilang
- Jika ingin versi lebih canggih (simpan ke Google Sheets, notifikasi harian, dll), sila maklumkan

---

## 🆘 Sokongan & Soalan

Jika ada sebarang soalan, cadangan penambahbaikan atau masalah teknikal, sila hantar isu di repositori ini atau hubungi saya secara terus.

---

## 🙌 Terima Kasih!

Semoga aplikasi ini dapat membantu anda mencapai matlamat kesihatan dan kecergasan dengan cara yang mudah dan berterusan. 💪

---
