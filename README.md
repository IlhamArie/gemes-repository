# 🦟 Tepuk Nyamuk! Misi: KKA (Koding dan Kecerdasan Artifisial)
Game edukasi interaktif berbasis kamera webcam & computer vision MediaPipe Hands untuk asesmen KKA siswa SMK.

---

## 🚀 Panduan Publikasi Online 100% GRATIS

Aplikasi ini dibuat secara **ringan dan mandiri (standalone)**, sehingga Anda dapat mempublikasikannya secara online di berbagai layanan hosting gratis tanpa biaya sepeser pun.

> ⚠️ **Catatan Penting Kamera:**  
> Browser web (Google Chrome, Microsoft Edge, Safari, Firefox) **wajib menggunakan koneksi HTTPS** agar kamera webcam dan deteksi MediaPipe diizinkan aktif. Seluruh layanan di bawah ini sudah **otomatis menyertakan SSL/HTTPS gratis**.

---

### Pilihan 1: Netlify Drop (Paling Mudah & Instan — 1 Menit, Tanpa Koding)
Metode ini adalah cara tercepat tanpa perlu menginstal aplikasi apa pun di laptop Anda:
1. Unduh file `index.html` dari aplikasi ini (klik tombol **"🚀 Publikasi Gratis"** > **"Unduh File index.html"**).
2. Masukkan file `index.html` ke dalam sebuah folder baru di laptop Anda (misal beri nama folder: `tepuk-nyamuk-kka`).
3. Buka peramban dan kunjungi: **[https://app.netlify.com/drop](https://app.netlify.com/drop)**.
4. Tarik (*drag & drop*) folder tersebut ke area drop Netlify.
5. Selesai! Netlify akan langsung memberikan tautan link aktif dengan HTTPS (contoh: `https://tepuk-nyamuk-kka.netlify.app`). Anda bisa langsung membagikan tautan ini ke siswa!

---

### Pilihan 2: GitHub Pages (100% Gratis Selamanya)
Cocok jika Anda ingin mengelola versi dan membagikan proyek ke guru lain:
1. Masuk ke akun [GitHub](https://github.com).
2. Buat repositori baru (misalnya bernama `tepuk-nyamuk-kka`), pilih opsi **Public**.
3. Unggah file `index.html` ke dalam repositori tersebut.
4. Buka menu **Settings** di repositori Anda.
5. Klik menu **Pages** di sebelah kiri (di bawah bagian *Code and automation*).
6. Pada bagian **Build and deployment > Branch**, pilih branch `main` (atau `master`) dan folder `/ (root)`, lalu klik **Save**.
7. Tunggu sekitar 1–2 menit, game Anda akan live di alamat:  
   `https://[username-github-anda].github.io/tepuk-nyamuk-kka/`

---

### Pilihan 3: Vercel (Performa Cepat & Domain Gratis)
1. Kunjungi [https://vercel.com](https://vercel.com) dan login menggunakan akun GitHub / Email Anda.
2. Klik **Add New...** > **Project**.
3. Impor repositori GitHub Anda.
4. File `vercel.json` sudah disediakan dalam proyek ini. Vercel akan otomatis mengenali dan melakukan build.
5. Klik tombol **Deploy**. Dalam beberapa detik game Anda aktif di subdomain `.vercel.app`.

---

### Pilihan 4: Cloudflare Pages (Bandwidth Tanpa Batas Gratis)
1. Masuk ke [Cloudflare Dashboard](https://dash.cloudflare.com/) > menu **Workers & Pages**.
2. Pilih **Create Application** > tab **Pages**.
3. Pilih **Upload Assets** (Anda tinggal upload folder yang berisi `index.html`).
4. Beri nama proyek dan klik **Deploy Site**.

---

## 🎮 Fitur Aplikasi
- **Deteksi Tangan Real-Time (MediaPipe Hands)**: Mendeteksi hingga 4 tangan sekaligus dengan gestur *fist grab* (mengepal/tepuk).
- **3 Mode Bermain**:
  - Mode Individu (Solo): 1 Pemain di 1 layar penuh.
  - Mode Battle: Layar terbagi 2, 3, atau 4 zona arena mandiri untuk kompetisi.
  - Mode Kelompok (Tim): Kolaborasi bersama mengumpulkan skor tim.
- **Dashboard Asesmen Guru**:
  - Kelola paket soal pilihan ganda (1 benar + 4 pengecoh).
  - Unduh template format tabel Word (.doc).
  - Unggah soal dari dokumen Word (.doc & .docx) secara instan.
  - Rekapitulasi nilai siswa dan ekspor ke file CSV/Excel.
- **Dukungan Touch & Mouse**: Tetap dapat dimainkan di perangkat tanpa webcam.
