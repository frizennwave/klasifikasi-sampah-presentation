# Panduan Kontribusi

Terima kasih telah tertarik untuk berkontribusi pada project ini! 🎉

## Cara Berkontribusi

### Melaporkan Bug

Jika Anda menemukan bug:

1. Pastikan bug belum dilaporkan dengan mengecek [Issues](../../issues)
2. Buat issue baru dengan label "bug"
3. Sertakan:
   - Deskripsi jelas tentang masalah
   - Langkah-langkah untuk mereproduksi bug
   - Screenshot jika memungkinkan
   - Browser dan versi yang digunakan

### Mengusulkan Fitur Baru

Jika Anda memiliki ide untuk fitur baru:

1. Cek dulu apakah fitur tersebut sudah diusulkan
2. Buat issue baru dengan label "enhancement"
3. Jelaskan:
   - Fitur yang diusulkan
   - Mengapa fitur ini berguna
   - Contoh implementasi jika ada

### Pull Request

1. Fork repository
2. Buat branch baru dari `main`:
   ```bash
   git checkout -b feature/nama-fitur
   ```
3. Lakukan perubahan Anda
4. Test perubahan di berbagai browser
5. Commit dengan pesan yang jelas:
   ```bash
   git commit -m "Add: deskripsi singkat perubahan"
   ```
6. Push ke branch Anda:
   ```bash
   git push origin feature/nama-fitur
   ```
7. Buat Pull Request ke branch `main`

## Standar Kode

### HTML
- Gunakan indentasi 2 spasi
- Pastikan semantic HTML
- Tambahkan komentar untuk bagian kompleks

### CSS
- Ikuti struktur CSS yang sudah ada
- Gunakan CSS variables untuk warna
- Kelompokkan properties secara logis
- Tambahkan komentar untuk section baru

### Penamaan
- Class names: gunakan kebab-case (contoh: `stat-card`)
- IDs: gunakan camelCase jika diperlukan
- Variabel CSS: gunakan kebab-case dengan prefix (contoh: `--forest-dark`)

## Testing

Sebelum submit Pull Request, pastikan:

- [ ] Presentasi berjalan lancar di Chrome, Firefox, dan Safari
- [ ] Responsive di berbagai ukuran layar (mobile, tablet, desktop)
- [ ] Tidak ada console errors
- [ ] Animasi berjalan dengan smooth
- [ ] Scroll snap berfungsi dengan baik

## Kode Etik

- Bersikap hormat dan profesional
- Terima kritik konstruktif dengan lapang dada
- Fokus pada apa yang terbaik untuk project

## Pertanyaan?

Jika ada pertanyaan, silakan:
- Buat issue dengan label "question"
- Atau hubungi maintainer melalui discussion tab

Terima kasih atas kontribusi Anda! 🌿
