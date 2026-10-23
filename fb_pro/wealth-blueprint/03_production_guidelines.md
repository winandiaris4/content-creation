# 03. Production Guidelines — Wealth Blueprint

Dokumen ini memuat panduan produksi visual, audio, serta standar desain aset grafis dan thumbnail untuk video animasi Wealth Blueprint.

---

## 1. Identitas Visual & Desain (*Visual Identity*)

### Skema Palet Warna (*Color Palette*)

Konsistensi visual merupakan tanda pengenal utama merek animasi tanpa wajah (*faceless channel*). Lima warna utama wajib hadir di setiap konten:

| Elemen | Kode Hex | Peran Penggunaan |
|---|---|---|
| **Primary Navy** | `#080E1F` | Background utama, elemen dasar, nuansa stabilitas & otoritas |
| **Wealth Gold** | `#C99E43` | Aksen angka, kata kunci penekanan (*highlight*), grafik naik |
| **Surface Dark** | `#12192F` | Card UI, box framework, kontras sekunder |
| **Pure White** | `#FFFFFF` | Teks narasi utama, subjudul, ikonografi |
| **Danger Red** | `#E53935` | Peringatan hutang, biaya tersembunyi, serpihan krisis (*faceted shards*) |

---

### Aturan *"First Frame = Thumbnail"*
Pada Facebook Reels dan feed video Facebook:
* Algoritma sering kali mengambil **0.5 detik pertama video** sebagai cuplikan pratinjau (*preview thumbnail*) di feed penonton.
* **SOP Produksi:** Pastikan frame pertama (detik 00:00–00:00.5) adalah still frame statis yang tajam, memuat judul/hook visual yang jelas, dan **bukan** animasi blur, layar hitam, atau transisi pudar (*fade-in*).

---

## 2. Standar Gaya Visual & Hook Scene (*Visual Archetypes*)

Wealth Blueprint mengadopsi pendekatan visual berbasis vektor isometrik geometris (*Faceted Isometric Vector Style*) yang memadukan ketegangan dramatis dengan kesederhanaan grafis berbobot tinggi.

### Aset Referensi Visual Resmi di Folder Proyek:
* 📁 `assets/vertical_hook_layout_9x16.jpg` — **Desain Hook Vertikal 9:16 (Reels/Shorts/TikTok)**
* 📁 `assets/vector_hook_reference.jpg` — **Hook Awal Vector Horizontal 16:9 ("THE DEBT TRAP")**
* 📁 `assets/vector_style_reference.jpg` — **Infografis Breakdown Diagram Geometris**
* 📁 `assets/visual_style_reference.jpg` — **Sinematik Dark Mode Alternatif**

---

### Spesifikasi Layout Vertikal 9:16 (Facebook Reels & Shorts)

Berdasarkan aset `assets/vertical_hook_layout_9x16.jpg` (Ukuran Standar: 1080 x 1920 piksel):

```text
┌─────────────────────────────────────────────────────────────┐  Y: 0px
│ [Top Safe Margin - Hindari Notch & UI Bar] (0 - 180px)      │
├─────────────────────────────────────────────────────────────┤
│ • Badge Seri: "WEALTH BLUEPRINT • FRAMEWORK #01"           │  Y: 200px
│ • Hook Title: "THE DEBT" (Gold #C99E43)                   │  Y: 310px
│ • Action Word: "TRAP" (White #FFFFFF, Font 114pt)          │  Y: 405px
│ • Subtitle: "How Banks Trap Americans In Minimum Payments"  │  Y: 545px
├─────────────────────────────────────────────────────────────┤
│                                                             │
│             HERO VISUAL CENTER (Eye Level)                  │  Y: 620 - 1450px
│      Kartu Kredit Retak + Serpihan Poligon Merah            │
│               + Balok Isometrik Emas Naik                   │
│                                                             │
├─────────────────────────────────────────────────────────────┤
│ FLOATING METRIC CARDS:                                      │  Y: 1500px
│ [Card 1: 24.99% APR (Red)]   [Card 2: 27.4 YEARS (Gold)]    │
├─────────────────────────────────────────────────────────────┤
│ [Bottom Safe Zone - Caption & Sound Title Area] (1750-1920) │
└─────────────────────────────────────────────────────────────┘  Y: 1920px
```

---

## 3. Standar Thumbnail Video (In-Stream 3+ Menit)

Thumbnail adalah iklan pertama video. Pengguna media sosial mengambil keputusan klik dalam waktu **0.3 detik**.

### Formula Thumbnail Finansial Efektif:
1. **Angka Spesifik:** Gunakan nominal atau persentase konkret daripada kata-kata abstrak.
   * ❌ *"Tips Investasi Saham"*
   * ✅ *"Why 93% of Investors Fail in Year One"*
   * ❌ *"Cara Keluar dari Hutang"*
   * ✅ *"0K Debt → bash in 18 Months"*
2. **Kontras Ekstrem:** Tulisan wajib terbaca jelas di layar smartphone kecil (background gelap pekat dengan teks emas/putih tebal).
3. **Satu Pesan Utama:** Jangan memuat lebih dari 5–7 kata pada visual thumbnail.
4. **Visual Dramatis Pengganti Wajah:** Karena tidak menggunakan foto wajah manusia, gunakan visual pengikat perhatian: grafik yang menukik ekstrem, metafora visual (kartu kredit terbelah, rantai bunga bank), atau perbandingan visual 2 kubu.

---

## 4. Panduan Audio & Sound Design

### Prinsip Inti Audio:
* **Wajib Tanpa Vokal (No Lyrics):** Lirik lagu akan bersaing dengan pemrosesan otak penonton dalam menyerap narasi.
* **Pacing Dinamis:** Musik harus mengalir selaras dengan tensi narasi (tegang di awal, memberikan solusi di tengah, optimis di akhir).

### 5 Gaya Musik Latar (BGM) & Relevansi Konten:

| Gaya Musik | Karakteristik Audio | Relevansi Topik | Kata Kunci Pencarian Library |
|---|---|---|---|
| **1. Corporate Uplifting** | Piano ringan, strings halus, ketukan modern | Investing, Wealth Building, S&P 500 | *corporate motivational, uplifting background, success music* |
| **2. Cinematic Tension** | Low strings, perkusi halus, atmosfer tegang | Opening Hook, Debt Traps, Banking Secrets | *cinematic suspense light, documentary background* |
| **3. Lo-fi / Chill Beats** | Ketukan hangat, santai, reflektif | Wealth Psychology, Mindset, Buku Finansial | *lo-fi study beats, chill background music* |
| **4. Tech / Minimalist** | Synth bersih, modern, presisi data | Fintech, Compound Interest, Grafik Pasar | *minimal electronic background, tech corporate* |
| **5. Storytelling Piano** | Piano solo emosional, lembut, menyentuh | Kisah pelunasan hutang, perjuangan hidup | *emotional piano background, inspirational soft piano* |

---

### SOP Mixing & Level Volume Audio

Untuk menjamin kualitas profesional dan keterbacaan suara narasi (*voiceover*):

```text
┌─────────────────────────────────────────────────────────────┐
│ 100% ──── [Voiceover Level Standar: -6dB s/d -3dB]          │
│                                                             │
│  40% ──── [Transisi / Jeda Narasi: 30%–40% BGM Level]       │
│                                                             │
│  15% ──── [BGM Saat Ada Narasi (Audio Ducking): 8%–15%]     │
│   0% ───────────────────────────────────────────────────────┘
```

1. **Audio Ducking:** Volume BGM wajib otomatis turun ke level **8%–15%** saat voiceover berbicara.
2. **Level Transisi:** Volume BGM naik ke **30%–40%** hanya saat terjadi pergantian segmen atau jeda dramatis 1–2 detik tanpa suara narasi.
3. **Transisi Halus:** Gunakan *smooth fade-in* dan *fade-out* (minimal 500ms). Hindari pemotongan track musik secara mendadak.
4. **Signature Brand Tracks:** Pilih **2–3 track tetap** yang dijadikan identitas suara khas (*sonic branding*) Wealth Blueprint dan dipakai secara konsisten.

---

## 5. Sumber Lisensi Musik Bebas Masalah Copyright

* **Epidemic Sound (Rekomendasi Utama):** Memiliki integrasi whitelist langsung ke akun Meta/Facebook, mencegah klaim otomatis atau mute audio.
* **Artlist:** Lisensi komersial seumur hidup per track yang diunduh.
* **YouTube Audio Library / Pixabay:** Pilihan gratis untuk fase persiapan, namun tetap utamakan platform berlisensi resmi saat monetisasi aktif.
