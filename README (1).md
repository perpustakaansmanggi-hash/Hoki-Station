# Hoki Station — Prototipe

Prototipe tampilan platform literasi digital **Hoki Station**, milik Perpustakaan Smanggi Hoki, SMAN 1 Gondanglegi. Platform ini dirancang sebagai wadah menulis, membaca, dan berbagi karya bagi siswa, guru, alumni, dan masyarakat umum.

> **Status: prototipe tampilan.** Berkas ini hanya satu halaman `index.html` tanpa backend. Tidak ada database, akun sungguhan, atau penyimpanan permanen. Semua data hilang saat halaman dimuat ulang. Jangan memasukkan data pribadi warga sekolah ke prototipe ini.

## Cara membuka

**Di komputer:** unduh `index.html`, lalu buka dengan browser.

**Lewat GitHub Pages:**
1. Unggah `index.html` ke repositori ini.
2. Buka **Settings → Pages**.
3. Pada **Source**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
4. Tunggu satu sampai dua menit. Alamat situs akan tampil di halaman yang sama.

## Akun demo

Halaman pertama yang terbuka adalah halaman login. Prototipe ini memakai satu akun admin demo untuk mencoba Panel Admin:

- Username: `hokiadmin`
- Password: `hoki444station`

Akun ini hanya untuk demo dan tertulis di kode, sehingga **terlihat oleh siapa saja yang membuka repositori**. Jangan memakai password ini di aplikasi sungguhan. Pengguna lain bisa masuk dengan isian apa saja dan akan menjadi akun siswa demo.

## Yang bisa dicoba

- **Beranda:** banner sambutan, target menulis dan membaca harian, ranking, dan berita.
- **Menulis:** editor dengan penghitung kata (10–1.000 kata), format teks, lampiran gambar (maksimal 4 foto, 5 MB per foto) dan audio (maksimal 5 MB).
- **Karya:** pencarian, filter kategori, pengurutan, halaman baca (tema Terang, Gelap, Hangat), suka, simpan, dan komentar (tulis, balas, lapor, hapus).
- **Ranking:** harian dan mingguan.
- **Panduan:** panduan pengguna, dengan bagian khusus untuk admin.
- **Menu akun:** Profil, Perpustakaan Saya, dan Panel Admin.
- **Panel Admin:** Laporan dan Statistik (unduh CSV, Excel, PDF), Verifikasi akun dan penetapan peran, Berita, moderasi Karya dan komentar yang dilaporkan, serta Backup manual dan pemulihan.

## Batasan prototipe

- Belum ada: notifikasi, pencarian khusus, kelola kategori dan banner, audit log, sistem bab untuk novelet dan cerbung, ekspor Word, dan fungsi cetak.
- Koneksi Google Drive hanya menampilkan status **Belum terhubung**. Koneksi sungguhan membutuhkan backend.
- Pembatasan akses admin hanya ada di tampilan. Pada aplikasi sungguhan, semua izin diperiksa di server.
- Unduhan XLSX dan PDF memuat pustaka dari cdnjs, jadi butuh koneksi internet.

## Rencana pengembangan

Aplikasi sungguhan dibangun bertahap:

1. **Fondasi:** database, akun, verifikasi, hak akses, avatar, profil.
2. **Fitur literasi:** menulis, karya, pencarian, Perpustakaan Saya, sistem membaca.
3. **Interaksi dan motivasi:** like, komentar, target harian, ranking, badge, notifikasi.
4. **Administrasi:** dashboard, manajemen akun dan karya, berita, kategori, laporan.
5. **Pengamanan dan dokumentasi:** ekspor, backup database, Google Drive, audit log, optimasi.

## Identitas visual

Putih `#FFFFFF`, abu-abu muda `#F1F5F9`, biru `#2589F5`, navy `#142B50`, dengan hijau untuk keberhasilan dan emas untuk penghargaan.
