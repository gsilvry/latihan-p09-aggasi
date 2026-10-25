# DEPENDENCIES

## 1. Pustaka yang Digunakan

- **Nama:** Bootstrap
- **Versi:** 5.3.3
- **Sumber:** CDN jsDelivr
- **CSS:** https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css
- **JavaScript:** https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js

## 2. Komponen yang Digunakan

1. **Navbar**  
   Navbar digunakan sebagai navigasi halaman untuk memudahkan pengguna berpindah bagian. Komponen ini juga mendukung tampilan responsif pada berbagai ukuran layar.

2. **Button**  
   Button digunakan sebagai tombol aksi, termasuk tombol Detail. Komponen ini memudahkan pengguna menjalankan fungsi aplikasi melalui interaksi yang jelas.

3. **Dialog**  
   Dialog digunakan untuk menampilkan informasi detail tanpa mengharuskan pengguna berpindah halaman. Pada implementasi Level 2, dialog menggunakan elemen HTML bawaan `<dialog>` untuk menggantikan Bootstrap Modal.

## 3. Ukuran Transfer

Pengukuran ukuran transfer dilakukan menggunakan Chrome DevTools pada tab Network dengan memuat ulang halaman dan mencatat nilai Transferred.

- **Sebelum optimasi:** [Isi ukuran transfer awal]
- **Sesudah optimasi:** [Isi ukuran transfer setelah optimasi]
- **Persentase pengurangan:** [Isi hasil perhitungan]

Persentase pengurangan ukuran transfer dihitung menggunakan rumus:

Pengurangan (%) = ((Total transfer awal − Total transfer sesudah optimasi) / Total transfer awal) × 100%

Target optimasi adalah mengurangi total transfer halaman sekurang-kurangnya 50% tanpa mengubah tampilan dan fungsi aplikasi.

## 4. Alasan Pemilihan Pustaka

Bootstrap digunakan karena menyediakan sistem grid, komponen antarmuka, dan utilitas responsif yang membantu proses pengembangan tampilan aplikasi. Versi Bootstrap dikunci pada 5.3.3 agar versi pustaka yang digunakan tetap konsisten.

## 5. Pembungkus JavaScript

File `ui-pustaka.js` berfungsi sebagai pembungkus untuk operasi antarmuka, termasuk fungsi `bukaDetail()`. Pembungkus ini memisahkan implementasi antarmuka dari logika utama aplikasi sehingga implementasi dapat diganti tanpa harus mengubah pemanggilan fungsi di `main.js`.


## 6. Referensi

- Bootstrap Documentation: https://getbootstrap.com/docs/5.3/
- jsDelivr: https://www.jsdelivr.com/
- HTML Dialog Element: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog
