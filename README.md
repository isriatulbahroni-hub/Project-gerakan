# Project-gerakan

Partikel interaktif yang dikontrol gerakan tangan lewat kamera (web, bisa dipakai di HP).

## Gestur

| Gestur | Bentuk |
|---|---|
| Kepalan | Hati merah |
| 1 jari | Planet oranye bercincin |
| 2 jari | Tulisan "I LOVE YOU" |
| 3-4 jari | Galaksi spiral |
| Tangan terbuka | Partikel menyebar |

## Cara pakai

Kamera hanya bisa diakses lewat **HTTPS** (atau `localhost`), jadi file `index.html` tidak jalan kalau dibuka langsung dari penyimpanan HP.

- Lokal: `python -m http.server` lalu buka `http://localhost:8000`
- HP: deploy ke GitHub Pages atau Vercel, lalu buka linknya di HP

## Teknologi

- MediaPipe Hands (deteksi tangan, dimuat dari CDN)
- Canvas 2D (partikel)

## Referensi untuk pengembangan berikutnya

Proyek open source yang lebih canggih (lihat lisensi masing-masing sebelum menyalin kode):

- WonderSnap (WebGL2, hingga 250 ribu partikel GPU): https://github.com/AkbarSheikh-debug/wondersnap
- Dynamic-Particles (Three.js, ramah HP, pemilih warna): https://github.com/Haynanson/Dynamic-Particles
- AI-Hand-Interaction-System (Three.js, bloom, hati dan Saturnus): https://github.com/longmanngithub/AI-Hand-Interaction-System
- ChristmasTree (React Three Fiber, bloom): https://github.com/DearBobby9/ChristmasTree
