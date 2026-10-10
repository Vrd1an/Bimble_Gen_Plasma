# RuangBelajar — Frontend Prototype

Prototype UI/UX aplikasi bimbingan belajar dengan 3 role simulasi: Admin, Tutor/Pengajar, dan User/Siswa.

## Teknologi
- HTML5
- CSS vanilla (responsive, mobile-first)
- JavaScript vanilla
- Dummy data di sisi frontend

## Menjalankan
1. Ekstrak ZIP.
2. Buka `index.html` langsung di browser, atau jalankan Live Server dari VS Code.
3. Gunakan dropdown **Mode tampilan** di kanan atas untuk berpindah role.
4. Klik ikon bulan/matahari untuk mengganti light/dark mode.
5. Navigasikan menu sidebar untuk membuka sembilan use case.

## Halaman / use case
1. Dashboard
2. Kelola Program
3. Kelola Jadwal
4. Kelola Ruangan
5. Kelola Durasi (Sesi)
6. Kelola Jenjang
7. Kelola Akun
8. Kelola Ulasan
9. Kelola Media

## Batasan prototype
- Tidak ada backend, database, API, atau autentikasi sungguhan.
- Tombol tambah/edit dan formulir hanya simulasi interaksi UI.
- Data contoh tidak disimpan dan akan kembali ke data awal setelah halaman dimuat ulang.
- Dropdown role hanya mengganti tampilan contoh, bukan memeriksa hak akses.
- Tanggal, nama, statistik, dan aktivitas merupakan dummy data.

## Struktur
```text
bimbel-frontend/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── style.css
    └── js/
        └── app.js
```
