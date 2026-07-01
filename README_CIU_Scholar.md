# CIU Scholar — Academic Staff Portal

> Portal profil akademik dosen UIN Siber Syekh Nurjati Cirebon

Aplikasi web untuk mengelola dan menampilkan profil akademik dosen secara terpusat — mulai dari data diri, riwayat pendidikan, hingga rekam jejak tridharma (pengajaran, penelitian, dan pengabdian kepada masyarakat). Dibangun dengan Laravel dan tema *liquid glass* beridentitas visual UIN SSC.

---

## Preview

![Landing Page](screenshots/landing.png)
![Direktori Dosen](screenshots/direktori.png)
![Profil Dosen](screenshots/profil.png)
![Dashboard Dosen](screenshots/dashboard.png)
![Panel Admin](screenshots/admin.png)

---

## Fitur Utama

### Untuk Dosen
- Registrasi mandiri dengan pemilihan fakultas dan jurusan
- Dashboard personal dengan indikator kelengkapan profil
- Kelola data tridharma lengkap: mata kuliah, publikasi ilmiah, riset & hibah, dan pengabdian kepada masyarakat (PKM)
- Export profil dan rekam jejak akademik ke PDF siap cetak

### Untuk Publik
- Landing page dengan statistik agregat dosen dan sebaran per fakultas
- Direktori dosen yang dapat dicari berdasarkan nama, jurusan, atau bidang keahlian
- Halaman profil publik per dosen dengan data lengkap dan tautan ke ID akademik (SINTA, Scopus, Google Scholar, ORCID)

### Untuk Admin
- Verifikasi akun dosen baru (approve/reject dengan catatan)
- Sistem antrian perubahan data — perubahan pada field sensitif seperti jabatan fungsional dan riwayat pendidikan masuk antrian dan perlu disetujui sebelum tampil publik
- Panel `admin_fakultas` dengan akses terbatas ke dosen di fakultasnya masing-masing
- Panel `super_admin` dengan akses penuh termasuk kelola akun admin

---

## Status Proyek

**MVP / Prototipe** — dikembangkan sebagai proyek portofolio pribadi, siap diserahkan untuk dikembangkan lebih lanjut oleh tim institusi.

Beberapa hal yang belum digarap di versi ini: tampilan mobile, verifikasi email, dan deployment ke server produksi.

---

## Tertarik untuk Berkolaborasi atau Mengembangkan Lebih Lanjut?

Hubungi saya melalui email: **fawwazmf24@gmail.com**
