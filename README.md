# Landing Template

Template halaman statis (HTML + Tailwind via CDN) mirip gaya promo page Bilibili. Cocok untuk di-deploy ke **GitHub Pages**.

## Struktur Folder
```
landing-template/
├── index.html       # Halaman utama
├── style.css        # Custom CSS tambahan
└── assets/          # Folder untuk gambar (logo, hero, card, dll)
    └── .gitkeep     # Placeholder supaya folder ikut ke repo
```

## Cara Pakai
1. Clone repo ini atau download ZIP.
2. Letakkan semua aset gambar (logo, background, dsb) di folder `assets/`.
3. Edit `index.html` untuk menyesuaikan:
   - Judul, deskripsi, dan teks lain.
   - Path gambar (`assets/...`).
4. Push ke repository GitHub.
5. Aktifkan **GitHub Pages** di Settings → Pages.

## Preview Lokal
Cukup buka file `index.html` di browser atau gunakan server sederhana:
```bash
python3 -m http.server
```

## Kustomisasi
- **Warna / tema**: diubah langsung di class Tailwind di `index.html`.
- **Grid Asset**: duplikasi blok `<article>` di dalam section `#assets`.
- **FAQ**: duplikasi `<details>` di dalam section `#faq`.

## Lisensi
Bebas dipakai untuk proyek pribadi atau presentasi. Untuk produksi, sesuaikan lisensi aset gambar yang kamu gunakan.
