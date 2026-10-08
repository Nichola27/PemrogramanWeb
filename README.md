# PRODUCT REQUIREMENTS DOCUMENT (PRD)

## Website Profil SMA Negeri 1 Nusantara
- Nama: Nichola Matthew Hutabarat
- NRP: 5025251231
- Kelas: Pemrograman Web B

- [**Hasil Web**](https://school-profile-omega.vercel.app)

### 1. Informasi Produk
| Item          | Detail  | 
|     :---      |  :---   |
| Nama Produk | Website Profil SMA Negeri 1 Nusantara | 
| Jenis Produk | Website Informasi dan Profil Institusi | 
| Target Pengguna | Calon siswa, siswa, orang tua, dan masyarakat umum | 
| Platform | Web Responsive | 
| Tujuan | Menyediakan informasi sekolah yang terkini, menarik, dan mudah diakses, termasuk informasi pendaftaran siswa baru (PPDB) | 

### 2. Latar Belakang
Website SMA Negeri 1 Nusantara digunakan sebagai media resmi untuk memperkenalkan sekolah dan menyampaikan informasi kepada masyarakat. Website menampilkan profil sekolah, program akademik, kegiatan kesiswaan, berita, galeri dokumentasi, informasi PPDB, serta kontak sekolah.

Website dibuat dengan tampilan yang sederhana, bersih, dan mudah digunakan, serta dikembangkan menggunakan teknologi web statis agar ringan dan mudah dipelihara. Desain dan struktur informasi mengacu pada website sekolah yang sudah ada (website referensi) sebagai inspirasi.

### 3. Tujuan Produk
Website ini bertujuan untuk:
- Menampilkan profil dan identitas sekolah.
- Menampilkan keunggulan sekolah (kurikulum, guru, dan ekstrakurikuler).
- Menampilkan informasi akademik, seperti jurusan, jadwal pelajaran, dan kalender akademik.
- Menampilkan informasi kesiswaan dan ekstrakurikuler.
- Menyampaikan berita, prestasi, kegiatan, dan pengumuman terbaru sekolah.
- Menampilkan agenda kegiatan sekolah yang akan datang.
- Menampilkan dokumentasi kegiatan melalui galeri.
- Menyediakan informasi PPDB (syarat, jadwal, dan alur pendaftaran).
- Menyediakan informasi kontak sekolah.
- Memiliki tampilan yang dapat digunakan melalui laptop maupun smartphone.

### 4. Target Pengguna
**Calon siswa dan orang tua**
Mencari informasi PPDB, program akademik, ekstrakurikuler, dan keunggulan sekolah.

**Siswa**
Melihat berita, agenda, jadwal pelajaran, prestasi, dan dokumentasi kegiatan sekolah.

**Pengunjung umum**
Mencari informasi mengenai profil sekolah, kegiatan, berita, dan kontak.

### 5. Struktur Website
```
Website Profil Sekolah
│
├── Beranda
│   ├── Hero (identitas sekolah + tombol aksi)
│   ├── Statistik Sekolah
│   ├── Keunggulan Sekolah
│   ├── Berita Terbaru
│   ├── Agenda Kegiatan
│   └── Akses Cepat
│
├── Profil
│
├── Akademik
│
├── Kesiswaan
│
├── Berita
│
├── Galeri
│
├── PPDB
│
└── Kontak
```

### 6. Functional Requirements
**FR 01 — Beranda**
Halaman utama menampilkan:
- Navbar/menu website dan tombol "Daftar Sekarang" yang mengarah ke halaman PPDB.
- Hero berisi nama sekolah, tagline, foto sekolah, dan tombol aksi (Profil Sekolah, Info PPDB, Video Profil).
- Statistik sekolah dengan animasi hitung: siswa aktif, guru & staf, tahun berdiri (sejak 1985), dan jumlah prestasi 5 tahun terakhir.
- Keunggulan sekolah: Kurikulum Terarah, Guru Berpengalaman, dan Ekosistem Ekstrakurikuler.
- Berita terbaru (3 berita) beserta tautan "Lihat Semua Berita".
- Agenda kegiatan dalam bentuk tabel (tanggal, kegiatan, lokasi).
- Akses cepat: PPDB, Jadwal Pelajaran, Ekstrakurikuler, dan Hubungi Sekolah.
- Footer berisi deskripsi singkat, navigasi, layanan, dan kontak sekolah.

**FR 02 — Profil Sekolah**
Halaman profil berisi:
- Identitas sekolah.
- Sejarah sekolah.
- Visi dan misi.
- Sambutan kepala sekolah.
- Fasilitas sekolah.

**FR 03 — Akademik**
Halaman akademik berisi:
- Kurikulum yang digunakan (Kurikulum Merdeka).
- Daftar jurusan/peminatan (MIPA, IPS, dan Bahasa).
- Jadwal pelajaran per kelas.
- Kalender akademik.

**FR 04 — Kesiswaan**
Halaman kesiswaan berisi:
- Daftar ekstrakurikuler beserta jadwal kegiatannya.
- Informasi OSIS/MPK.
- Informasi jumlah siswa.

**FR 05 — Berita**
Setiap berita memiliki:
- Judul.
- Foto.
- Tanggal.
- Kategori (Prestasi, Kegiatan, atau Pengumuman).
- Ringkasan.
- Isi berita.

Prestasi sekolah dan siswa ditampilkan sebagai berita berkategori **Prestasi**, serta tercermin pada statistik jumlah prestasi di beranda.

**FR 06 — Galeri**
Halaman galeri menampilkan:
- Foto dokumentasi kegiatan sekolah.
- Keterangan singkat untuk setiap foto.

**FR 07 — PPDB**
Halaman PPDB menampilkan:
- Syarat pendaftaran.
- Jadwal pendaftaran.
- Alur pendaftaran.

**FR 08 — Kontak**
Menampilkan informasi:
- Nama sekolah.
- Alamat: Jl. Pendidikan No. 12, Kota Nusantara.
- Nomor telepon: (031) 123-4567.
- Email: info@sman1nusantara.sch.id.
- Jam operasional.
- Media sosial.
- Google Maps.
- Formulir masukan/pesan.

### 7. Admin / Content Management (Pengembangan Berikutnya)
Versi saat ini berupa website statis, sehingga konten diubah langsung pada file HTML. Pada pengembangan berikutnya, dapat ditambahkan dashboard admin:
```
Admin Dashboard
│
├── Dashboard
├── Profil Sekolah
├── Berita
├── Agenda
├── Galeri
├── Program Akademik
├── Informasi PPDB
├── Pesan Kontak
└── User Management
```
Admin dapat melakukan operasi Create, Read, Update, dan Delete (CRUD) pada konten website.

### 8. Non-Functional Requirements
**Responsive**
Website dapat dibuka pada:
- Desktop/laptop.
- Tablet.
- Smartphone.

**Performance**
- Menggunakan gambar dengan ukuran yang tidak terlalu besar.
- Tidak menggunakan terlalu banyak animasi.
- Website tetap dapat dimuat dengan cepat.

**Accessibility**
- Warna teks mudah dibaca.
- Ukuran font cukup jelas.
- Setiap gambar memiliki alt.
- Navigasi mudah digunakan.

**SEO**
- Setiap halaman memiliki title dan meta description yang sesuai.

**Security**
- Tidak menampilkan data pribadi siswa.
- Form kontak melakukan validasi input dasar.

### 9. Teknologi yang Digunakan
```
HTML + CSS + JavaScript + Vercel
```

### 10. Struktur Database (Pengembangan Berikutnya)
- users
- schools
- teachers
- programs
- extracurriculars
- news
- categories
- agenda
- gallery
- ppdb
- contacts

Relasi utama: users → news; categories → news.

### 11. Prioritas Fitur
**MVP**
- Beranda
- Profil
- Akademik
- Kesiswaan
- Berita (termasuk prestasi)
- Galeri
- PPDB
- Kontak
- Responsive

**Pengembangan Berikutnya**
- Login
- Admin Dashboard
- Database
- CRUD
- Search
- Pagination
- Pendaftaran PPDB online
- Statistik pengunjung
- API

### 12. User Flow
**Pengunjung**
```
Beranda
│
├── Profil
├── Akademik
├── Kesiswaan
├── Berita
├── Galeri
├── PPDB
└── Kontak
```

**Calon siswa**
```
Beranda → Daftar Sekarang → PPDB → Kontak (jika ada pertanyaan)
```

### 13. Struktur Project
Struktur berikut disusun dari URL halaman dan gambar yang terlihat pada website. Sesuaikan dengan isi repository kamu.
```
Website Profil Sekolah
│
├── README.md
│
├── index.html
│
├── pages
│   ├── profil.html
│   ├── akademik.html
│   ├── kesiswaan.html
│   ├── berita.html
│   ├── galeri.html
│   ├── ppdb.html
│   └── kontak.html
│
└── assets
    └── images
        ├── Foto SMAN 1 Nusantara.jpg
        ├── Mendali emas olimpiade fisika.jpg
        ├── Foto Tarik Tambang.jpg
        └── foto ujian tengah semester.jpg
```