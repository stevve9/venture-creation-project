# Slimu 

Website katalog & pre-order untuk bisnis slime kampus **Slimu**. Pengunjung bisa menjelajahi katalog produk, mengisi kuis tekstur untuk mendapat rekomendasi slime yang sesuai preferensi mereka, lalu menyelesaikan pemesanan langsung lewat WhatsApp.

## Fitur

- **Katalog produk** — menampilkan varian slime (butter, clear, cloud, dll) lengkap dengan harga dan deskripsi
- **Kuis tekstur** — beberapa pertanyaan singkat untuk merekomendasikan produk yang paling cocok dengan preferensi pengunjung
- **Keranjang & checkout via WhatsApp** — produk yang dipilih otomatis disusun menjadi pesan pre-order yang dikirim ke WhatsApp admin
- **Halaman perawatan slime** — tips menyimpan dan merawat slime agar tahan lama
- **FAQ & tentang kami** — informasi seputar proses produksi, pengambilan pesanan di kampus, dan kebijakan garansi

## Struktur Project
├── index.html # Halaman utama (katalog, kuis tekstur, keranjang, FAQ, dll)
└── support.js # Script pendukung interaktivitas website


## Menjalankan secara lokal

Karena ini website statis, cukup buka `index.html` langsung di browser, atau jalankan local server sederhana:

```bash
npx serve .
```

## Deployment

Website ini di-deploy sebagai static site menggunakan [Vercel](https://vercel.com), terhubung langsung ke repository GitHub ini. Setiap `git push` ke branch `main` akan otomatis memicu deployment baru.

## Tentang Bisnis

Slimu adalah bisnis slime yang dimulai untuk dijual di bazar kampus, dengan model pre-order: pembeli memilih produk lewat website, lalu mengambil pesanan langsung di titik pengambilan di area kampus.