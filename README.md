# DICAKUN — Static dynamic site (Netlify-ready)

Cara pakai:
1. Unzip dan push folder `DICAKUN` ke repository GitHub.
2. Di Netlify, connect repository tersebut dan deploy (build not necessary for static site).
3. Untuk menambah film: edit `data/movies.json` dan tambahkan objek film baru.
   - `id`: unique slug (jika kosong, akan dibuat otomatis dari judul).
   - `poster`: path ke file di `assets/poster/`.
   - `genres`: array genre.
4. Struktur:
```
index.html
film.html
script.js
style.css
data/movies.json
assets/poster/*.svg
```

Catatan:
- Poster saat ini berupa file SVG contoh. Ganti dengan gambar berkualitas saat upload ke repo.
- Jika ingin memakai CDN/hosting gambar eksternal, set `poster` di JSON ke URL lengkap.
