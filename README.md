# EXPLORE: Petualangan 24 Lantai Perpusnas

Game edukatif HTML5/CSS3/JavaScript tentang prosedur layanan, koleksi, dan literasi di 24 lantai Perpustakaan Nasional RI.

## Fitur
- 4 karakter dengan jalur kebutuhan utama berbeda.
- 24 lantai tercatat utuh, termasuk 12A sebagai representasi lantai 13 pada data permainan.
- Gerbang loker Lantai 1, kartu anggota SAKTI Lantai 2, dan katalog OPAC/OneSearch.
- Animasi karakter berjalan, lift, indikator lantai, dan blueprint menara 24 lantai.
- Kuis edukatif dan mini-game DDC di Lantai 21–22.
- Penyimpanan progres dengan localStorage.

## Menjalankan
Buka `index.html` atau jalankan server statis:

```bash
python3 -m http.server 8000
```

Aset identitas game ada di `assets/logo-perpusnas.svg`. Inspeksi aset lokal menemukan satu foto komponen elektronik yang bukan gedung/logo Perpusnas, sehingga blueprint gedung dibuat menggunakan CSS tanpa mengklaim foto tersebut sebagai gedung.

## Deployment
Proyek dipublikasikan melalui GitHub Pages dari branch `main` root repository.
