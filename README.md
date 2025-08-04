# Blajar - Platform Pembelajaran Online

![Blajar Logo](./images/blajar-icon.png)

## Deskripsi Proyek

Blajar adalah platform pembelajaran online yang dirancang untuk membantu pengguna mempelajari keterampilan baru dari para ahli industri. Platform ini menyediakan berbagai kursus dalam bidang teknologi, khususnya pengembangan web dan pemrograman.

## Fitur Utama

- **Navigasi Intuitif**: Menu navigasi yang mudah digunakan dengan akses ke Home, Courses, Classes, About Us, dan Register
- **Hero Section**: Tampilan utama yang menarik dengan call-to-action untuk bergabung
- **Katalog Kursus**: Menampilkan kursus-kursus populer dengan sistem rating dan jumlah views
- **Desain Responsif**: Menggunakan metodologi BEM CSS untuk struktur yang bersih dan mudah dipelihara

## Teknologi yang Digunakan

- **HTML5**: Struktur semantik untuk konten web
- **CSS3**: Styling dengan metodologi BEM (Block Element Modifier)
- **Font Awesome 4.7.0**: Ikon untuk rating bintang dan views
- **BEM CSS Methodology**: Penamaan class yang konsisten dan terstruktur

## Struktur File

```
blajar/
├── index.html              # File HTML utama
├── src/
│   └── index.css           # File CSS dengan metodologi BEM
├── images/
│   ├── favicon.ico         # Icon website
│   ├── blajar-icon.png     # Logo Blajar
│   ├── hero-image.png      # Gambar hero section
│   ├── html-basic.png      # Thumbnail kursus HTML
│   ├── javascript-basic.png # Thumbnail kursus JavaScript
│   └── react-basic.png     # Thumbnail kursus React
└── README.md               # Dokumentasi proyek
```

## Metodologi BEM CSS

Proyek ini menggunakan metodologi BEM (Block Element Modifier) untuk penamaan class CSS:

### Contoh Struktur BEM:
- **Block**: `.nav`, `.hero`, `.courses`
- **Element**: `.nav__list`, `.nav__item`, `.hero__title`, `.courses__card`
- **Modifier**: `.fa-star.checked`

### Keuntungan BEM:
- Kode CSS yang lebih terorganisir
- Mudah dipelihara dan dikembangkan
- Menghindari konflik penamaan class
- Struktur yang konsisten dan dapat diprediksi

## Cara Menjalankan Proyek

### Persyaratan
- Web browser modern (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code, Sublime Text, dll.)

### Langkah Instalasi
1. Clone atau download proyek ini
2. Pastikan semua file gambar tersedia dalam folder `images/`
3. Buat file `src/index.css` untuk styling
4. Buka `index.html` di web browser

### Pengembangan
1. Edit file HTML di `index.html`
2. Tambahkan styling menggunakan metodologi BEM di `src/index.css`
3. Simpan dan refresh browser untuk melihat perubahan

## Kursus yang Tersedia

| Kursus | Rating | Views | Deskripsi |
|--------|--------|-------|-----------|
| HTML Basic | 4.0/5 (397 Reviews) | 3,578 Views | Dasar-dasar HTML untuk pemula |
| Frontend Basic | 4.0/5 (397 Reviews) | 3,578 Views | Fundamental pengembangan frontend |
| Backend Basic | 4.0/5 (397 Reviews) | 3,578 Views | Pengenalan pengembangan backend |

## Kontribusi

Kami menyambut kontribusi dari developer lain! Untuk berkontribusi:

1. Fork repository ini
2. Buat branch baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan Anda (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

### Panduan Kontribusi
- Gunakan metodologi BEM untuk penamaan class CSS
- Pastikan kode HTML semantik dan accessible
- Test di berbagai browser sebelum submit
- Tulis commit message yang jelas dan deskriptif

## Lisensi

Proyek ini dilisensikan di bawah MIT License - lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.

---

**Dikembangkan dengan ❤️ untuk komunitas pembelajaran Indonesia**
