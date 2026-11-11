# Koleksi Kartu

Halaman awal satu file (`index.html`). Tanpa build dan tanpa framework. Satu-satunya sumber luar adalah Google Fonts.

## Pasang di GitHub Pages

1. Buat repository baru di GitHub, misalnya `koleksi-kartu`.
2. Upload `index.html` dan `README.md` ke root repository (Add file, lalu Upload files).
3. Buka Settings, lalu Pages. Pilih Source: Deploy from a branch, Branch: `main`, folder `/ (root)`, lalu Save.
4. Tunggu 1–2 menit, lalu buka `https://USERNAME.github.io/NAMA-REPO/`.

## Cara pakai

- Scroll mouse atau geser kartu di dalam kotak untuk memilih kartu.
- Klik kartu tengah (atau tombol **Buka**) untuk membuka link di tab baru.
- Tombol **+** membuka kotak tambah kartu (gambar, nama, link). Warna kartu mengikuti warna dominan gambar.
- Tombol **Auto**: klik untuk membuka semua link yang sudah diatur sebagai tab baru. Klik kanan (atau tekan lama di HP) untuk mengatur daftar link.
- Tombol **Hapus**: tekan dua kali untuk menghapus kartu yang sedang aktif.

## Catatan

- Kartu yang ditambahkan dan daftar link Auto disimpan di `localStorage` browser masing-masing. Data itu tidak ikut ke GitHub dan tidak muncul di perangkat lain.
- Untuk kartu bawaan yang tampil di semua perangkat, edit array `seed` di dalam `index.html`.
- Jika browser memblokir pop-up saat Auto dipakai, izinkan pop-up untuk situs ini.
