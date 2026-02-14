# 🚀 Quick Start Guide

Panduan cepat untuk memulai menggunakan presentasi ini.

## 📦 Apa yang Anda Perlukan?

- Browser modern (Chrome, Firefox, Safari, Edge)
- Git (untuk cloning repository)
- Text editor (opsional, untuk modifikasi)

## ⚡ Mulai dalam 3 Langkah

### 1. Clone Repository

```bash
git clone https://github.com/username/klasifikasi-sampah-presentation.git
cd klasifikasi-sampah-presentation
```

### 2. Buka Presentasi

**Cara Termudah:**
- Double-click file `index.html`
- Presentasi akan terbuka di browser default Anda

**Dengan Live Server (VS Code):**
```bash
# Buka folder di VS Code
code .
# Klik kanan index.html → Open with Live Server
```

### 3. Navigasi Presentasi

- **Scroll** atau gunakan **mouse wheel** untuk pindah slide
- **Arrow keys** ↑↓ juga bisa digunakan
- Setiap slide akan snap ke posisi penuh layar

## 🎯 Struktur Slide

1. **Slide 1** - Judul & Tagline
2. **Slide 2** - Industri Pengelolaan Sampah
3. **Slide 3** - Identifikasi Masalah
4. **Slide 4** - Solusi Data Science
5. **Slide 5** - Pipeline ML
6. **Slide 6** - Hasil & Evaluasi
7. **Slide 7** - Terima Kasih

## 🎨 Kustomisasi

### Ubah Warna

Edit bagian `:root` di `index.html`:

```css
:root {
  --forest-dark: #1a4d2e;    /* Warna utama gelap */
  --forest-main: #2d6a4f;    /* Warna utama */
  --mint: #52b788;           /* Warna aksen */
  /* ... */
}
```

### Ubah Konten

1. Buka `index.html` dengan text editor
2. Cari bagian slide yang ingin diubah
3. Edit teks di dalam tag HTML
4. Save dan refresh browser

### Tambah Slide Baru

```html
<!-- Template Slide Baru -->
<section class="slide slide-8">
  <img src="img/clover.png" class="clover clover-1" alt="" />
  <div class="content">
    <h2 class="slide-title">Judul Slide Baru</h2>
    <!-- Konten Anda di sini -->
  </div>
</section>
```

## 📱 Deploy Online

### GitHub Pages (Gratis)

1. Push ke GitHub repository
2. Settings → Pages
3. Source: `main` branch, `/ (root)` folder
4. Save
5. Akses di: `https://username.github.io/nama-repo/`

### Netlify (Gratis)

1. Daftar di [netlify.com](https://netlify.com)
2. Drag & drop folder project
3. Otomatis deploy!

### Vercel (Gratis)

```bash
npm i -g vercel
cd klasifikasi-sampah-presentation
vercel
```

## 🔧 Tips Penggunaan

### Presentasi Mode

- Tekan **F11** (Windows/Linux) atau **Cmd+Ctrl+F** (Mac) untuk fullscreen
- Zoom browser: **Ctrl/Cmd + Plus/Minus**

### Print ke PDF

1. Buka presentasi di browser
2. Tekan **Ctrl/Cmd + P**
3. Destination: **Save as PDF**
4. Layout: **Landscape**
5. Print!

### Share dengan Tim

**Cara 1: Online Link**
- Deploy ke GitHub Pages/Netlify
- Share link

**Cara 2: File ZIP**
- Zip seluruh folder
- Kirim via email/cloud storage

**Cara 3: PDF**
- Buka `docs/data-science.pdf`
- Share file PDF

## ❓ FAQ

**Q: Kenapa animasi tidak smooth?**
A: Pastikan hardware acceleration browser aktif. Chrome: `chrome://settings` → Advanced → System → Use hardware acceleration

**Q: Bisa digunakan offline?**
A: Ya! Semua asset sudah included. Hanya perlu browser.

**Q: Kompatibel dengan browser apa?**
A: Chrome, Firefox, Safari, Edge (versi terbaru). IE tidak support.

**Q: Bisa diubah menjadi PPT/PPTX?**
A: Tidak langsung. Tapi Anda bisa export tiap slide sebagai gambar, lalu import ke PowerPoint.

## 📚 Dokumentasi Lengkap

- [README.md](README.md) - Dokumentasi project lengkap
- [UPLOAD_GUIDE.md](UPLOAD_GUIDE.md) - Panduan upload ke GitHub
- [CONTRIBUTING.md](CONTRIBUTING.md) - Panduan kontribusi

## 🆘 Butuh Bantuan?

- Buat [Issue](../../issues) di GitHub
- Cek [Discussions](../../discussions)

---

**Happy Presenting! 🌿✨**
