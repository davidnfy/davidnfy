<!-- README.md - Simple & Cool with Pixel Animation -->
<!-- Paste this file directly into your repository root -->

<div align="center">

<h1>✨ Nama Project Kamu</h1>

<!-- Animated pixel SVG — GitHub akan merender SVG inline -->
<!-- Jika ingin ubah warna, edit atribut fill pada <rect> atau <animateColor>. -->
<svg width="240" height="80" viewBox="0 0 120 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="pixel animation">
  <!-- background -->
  <rect width="120" height="40" fill="transparent"/>
  <!-- grid of "pixels" 8x4 (kotak kecil) -->
  <!-- setiap rect memiliki animate untuk membuat efek 'berkedip' bergantian -->
  <!-- baris 1 -->
  <g transform="translate(8,6)">
    <!-- kolom 1..10 -->
    <!-- gunakan delay (begin) berbeda untuk efek berjalan -->
    <rect x="0" y="0" width="6" height="6" rx="1" fill="#FF6B6B">
      <animate attributeName="fill" values="#FF6B6B;#FFC3A0;#FF6B6B" dur="1.2s" repeatCount="indefinite" begin="0s"/>
    </rect>
    <rect x="8" y="0" width="6" height="6" rx="1" fill="#FFD93D">
      <animate attributeName="fill" values="#FFD93D;#FFF3C4;#FFD93D" dur="1.2s" repeatCount="indefinite" begin="0.08s"/>
    </rect>
    <rect x="16" y="0" width="6" height="6" rx="1" fill="#6BCB77">
      <animate attributeName="fill" values="#6BCB77;#CFF7D6;#6BCB77" dur="1.2s" repeatCount="indefinite" begin="0.16s"/>
    </rect>
    <rect x="24" y="0" width="6" height="6" rx="1" fill="#4D96FF">
      <animate attributeName="fill" values="#4D96FF;#CFE4FF;#4D96FF" dur="1.2s" repeatCount="indefinite" begin="0.24s"/>
    </rect>
    <rect x="32" y="0" width="6" height="6" rx="1" fill="#A66DFF">
      <animate attributeName="fill" values="#A66DFF;#E6DCFF;#A66DFF" dur="1.2s" repeatCount="indefinite" begin="0.32s"/>
    </rect>
    <rect x="40" y="0" width="6" height="6" rx="1" fill="#FF6B6B">
      <animate attributeName="fill" values="#FF6B6B;#FFC3A0;#FF6B6B" dur="1.2s" repeatCount="indefinite" begin="0.40s"/>
    </rect>
    <rect x="48" y="0" width="6" height="6" rx="1" fill="#FFD93D">
      <animate attributeName="fill" values="#FFD93D;#FFF3C4;#FFD93D" dur="1.2s" repeatCount="indefinite" begin="0.48s"/>
    </rect>
    <rect x="56" y="0" width="6" height="6" rx="1" fill="#6BCB77">
      <animate attributeName="fill" values="#6BCB77;#CFF7D6;#6BCB77" dur="1.2s" repeatCount="indefinite" begin="0.56s"/>
    </rect>
    <rect x="64" y="0" width="6" height="6" rx="1" fill="#4D96FF">
      <animate attributeName="fill" values="#4D96FF;#CFE4FF;#4D96FF" dur="1.2s" repeatCount="indefinite" begin="0.64s"/>
    </rect>
    <rect x="72" y="0" width="6" height="6" rx="1" fill="#A66DFF">
      <animate attributeName="fill" values="#A66DFF;#E6DCFF;#A66DFF" dur="1.2s" repeatCount="indefinite" begin="0.72s"/>
    </rect>
  </g>

  <!-- baris 2 (offset sedikit ke bawah) -->
  <g transform="translate(8,16)">
    <!-- contoh dengan pola delay berbeda untuk kesan 'gelombang' -->
    <!-- ulangi pattern seperti di atas tapi mulai dengan begin lebih besar -->
    <rect x="0" y="0" width="6" height="6" rx="1" fill="#4D96FF">
      <animate attributeName="fill" values="#4D96FF;#CFE4FF;#4D96FF" dur="1.1s" repeatCount="indefinite" begin="0.18s"/>
    </rect>
    <rect x="8" y="0" width="6" height="6" rx="1" fill="#A66DFF">
      <animate attributeName="fill" values="#A66DFF;#E6DCFF;#A66DFF" dur="1.1s" repeatCount="indefinite" begin="0.26s"/>
    </rect>
    <rect x="16" y="0" width="6" height="6" rx="1" fill="#FF6B6B">
      <animate attributeName="fill" values="#FF6B6B;#FFC3A0;#FF6B6B" dur="1.1s" repeatCount="indefinite" begin="0.34s"/>
    </rect>
    <rect x="24" y="0" width="6" height="6" rx="1" fill="#FFD93D">
      <animate attributeName="fill" values="#FFD93D;#FFF3C4;#FFD93D" dur="1.1s" repeatCount="indefinite" begin="0.42s"/>
    </rect>
    <rect x="32" y="0" width="6" height="6" rx="1" fill="#6BCB77">
      <animate attributeName="fill" values="#6BCB77;#CFF7D6;#6BCB77" dur="1.1s" repeatCount="indefinite" begin="0.50s"/>
    </rect>
    <rect x="40" y="0" width="6" height="6" rx="1" fill="#4D96FF">
      <animate attributeName="fill" values="#4D96FF;#CFE4FF;#4D96FF" dur="1.1s" repeatCount="indefinite" begin="0.58s"/>
    </rect>
    <rect x="48" y="0" width="6" height="6" rx="1" fill="#A66DFF">
      <animate attributeName="fill" values="#A66DFF;#E6DCFF;#A66DFF" dur="1.1s" repeatCount="indefinite" begin="0.66s"/>
    </rect>
    <rect x="56" y="0" width="6" height="6" rx="1" fill="#FF6B6B">
      <animate attributeName="fill" values="#FF6B6B;#FFC3A0;#FF6B6B" dur="1.1s" repeatCount="indefinite" begin="0.74s"/>
    </rect>
    <rect x="64" y="0" width="6" height="6" rx="1" fill="#FFD93D">
      <animate attributeName="fill" values="#FFD93D;#FFF3C4;#FFD93D" dur="1.1s" repeatCount="indefinite" begin="0.82s"/>
    </rect>
    <rect x="72" y="0" width="6" height="6" rx="1" fill="#6BCB77">
      <animate attributeName="fill" values="#6BCB77;#CFF7D6;#6BCB77" dur="1.1s" repeatCount="indefinite" begin="0.90s"/>
    </rect>
  </g>

  <!-- baris 3 -->
  <g transform="translate(8,26)">
    <rect x="0" y="0" width="6" height="6" rx="1" fill="#A66DFF">
      <animate attributeName="fill" values="#A66DFF;#E6DCFF;#A66DFF" dur="1.3s" repeatCount="indefinite" begin="0.36s"/>
    </rect>
    <rect x="8" y="0" width="6" height="6" rx="1" fill="#FF6B6B">
      <animate attributeName="fill" values="#FF6B6B;#FFC3A0;#FF6B6B" dur="1.3s" repeatCount="indefinite" begin="0.44s"/>
    </rect>
    <rect x="16" y="0" width="6" height="6" rx="1" fill="#FFD93D">
      <animate attributeName="fill" values="#FFD93D;#FFF3C4;#FFD93D" dur="1.3s" repeatCount="indefinite" begin="0.52s"/>
    </rect>
    <rect x="24" y="0" width="6" height="6" rx="1" fill="#6BCB77">
      <animate attributeName="fill" values="#6BCB77;#CFF7D6;#6BCB77" dur="1.3s" repeatCount="indefinite" begin="0.60s"/>
    </rect>
    <rect x="32" y="0" width="6" height="6" rx="1" fill="#4D96FF">
      <animate attributeName="fill" values="#4D96FF;#CFE4FF;#4D96FF" dur="1.3s" repeatCount="indefinite" begin="0.68s"/>
    </rect>
    <rect x="40" y="0" width="6" height="6" rx="1" fill="#A66DFF">
      <animate attributeName="fill" values="#A66DFF;#E6DCFF;#A66DFF" dur="1.3s" repeatCount="indefinite" begin="0.76s"/>
    </rect>
    <rect x="48" y="0" width="6" height="6" rx="1" fill="#FF6B6B">
      <animate attributeName="fill" values="#FF6B6B;#FFC3A0;#FF6B6B" dur="1.3s" repeatCount="indefinite" begin="0.84s"/>
    </rect>
    <rect x="56" y="0" width="6" height="6" rx="1" fill="#FFD93D">
      <animate attributeName="fill" values="#FFD93D;#FFF3C4;#FFD93D" dur="1.3s" repeatCount="indefinite" begin="0.92s"/>
    </rect>
    <rect x="64" y="0" width="6" height="6" rx="1" fill="#6BCB77">
      <animate attributeName="fill" values="#6BCB77;#CFF7D6;#6BCB77" dur="1.3s" repeatCount="indefinite" begin="1.00s"/>
    </rect>
    <rect x="72" y="0" width="6" height="6" rx="1" fill="#4D96FF">
      <animate attributeName="fill" values="#4D96FF;#CFE4FF;#4D96FF" dur="1.3s" repeatCount="indefinite" begin="1.08s"/>
    </rect>
  </g>

</svg>

</div>

---

## 🔎 Tentang
Readme ini minimal dan estetis — cocok untuk project pribadi, portofolio, atau repo yang ingin tampil beda tanpa ribet.

## 🚀 Fitur
- Tampilan clean dan modern  
- **Animasi pixel** langsung di README (SVG)  
- Mudah dikustom: ubah warna, ukuran, atau pola pixel

## ⚙️ Cara pakai
1. Salin seluruh isi file README ini.
2. Paste ke `README.md` di repo GitHub-mu.
3. Jika mau ubah tampilan animasi:
   - Edit ukuran SVG (`width`/`height`/`viewBox`) atau warna `fill` setiap `<rect>`.
   - Ubah nilai `begin` pada `<animate>` untuk mengatur timing gelombang.

## ✨ Contoh kustom singkat
- Ganti `#FF6B6B` jadi warna favoritmu.
- Ubah `dur="1.2s"` jadi `0.8s` untuk animasi lebih cepat.

## 📫 Kontak
Butuh versi lain (mis. bentuk hati pixel, tulisan animasi, atau GIF)? Tinggal bilang — saya buatkan cepat.

---

**License:** MIT  
(atau sesuaikan dengan lisensi yang kamu mau)
