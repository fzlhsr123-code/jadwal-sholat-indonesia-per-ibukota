# Dashboard Monitoring Jadwal Sholat Seluruh Indonesia

Dashboard monitoring jadwal sholat **38 Ibukota Provinsi Resmi Republik Indonesia** dari Sabang sampai Merauke, berdasarkan standar hisab Kementerian Agama RI (MABIMS).

**Demo Live:** [Lihat di Vercel](https://your-project.vercel.app)

---

## Fitur

- Jadwal Sholat 38 Ibukota Provinsi (Subuh, Dzuhur, Ashar, Maghrib, Isya)
- Konversi Kalender Hijriah otomatis (algoritma Julian Day)
- Jam real-time 3 zona waktu: WIB / WITA / WIT
- Pencarian instan tanpa reload (Ctrl+K atau tekan /)
- Filter zona waktu (WIB, WITA, WIT)
- Modal detail per kota + salin ke clipboard
- Ekspor data ke CSV
- Dukungan cetak (print-friendly)
- Tema Hijau & Putih (Islamic theme)

---

## Stack Teknologi

| Teknologi | Keterangan |
|---|---|
| HTML5 + JavaScript | Frontend murni, tanpa framework |
| Tailwind CSS CDN | Styling responsif |
| Lucide Icons | Ikon vektor |
| Vercel | Hosting static gratis |

---

## Cara Deploy ke Vercel via GitHub

### Langkah 1: Push ke GitHub

```bash
# Di folder project ini
git init
git add .
git commit -m "feat: dashboard jadwal sholat 38 provinsi indonesia"
git branch -M main
git remote add origin https://github.com/USERNAME/NAMA-REPO.git
git push -u origin main
```

### Langkah 2: Import ke Vercel

1. Buka **[vercel.com](https://vercel.com)** dan login (bisa pakai akun GitHub)
2. Klik **"Add New Project"**
3. Pilih repository GitHub yang sudah di-push tadi
4. **Framework Preset:** pilih **Other** (karena ini static HTML)
5. Klik **"Deploy"** — selesai!

Vercel akan otomatis memberi URL seperti: `https://jadwal-sholat-indonesia.vercel.app`

---

## Struktur File

```
jadwal-sholat-indonesia/
├── index.html      # File utama (static, semua logika di JS)
├── vercel.json     # Konfigurasi routing Vercel
├── .gitignore      # File yang tidak ikut di-push
├── README.md       # Dokumentasi ini
└── index.php       # Versi lokal XAMPP (tidak di-deploy)
```

---

## Standar Hisab

Berdasarkan kriteria **MABIMS** (Menteri Agama Brunei Darussalam, Indonesia, Malaysia, dan Singapura):
- Tinggi hilal: **3 derajat**
- Elongasi: **6,4 derajat**
- Sudut depresi Subuh: **-20 derajat**
- Ikhtiyat: **2 menit**

---

*Dibuat dengan semangat memudahkan umat dalam ibadah. Semoga bermanfaat.*
