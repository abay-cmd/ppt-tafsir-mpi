# Slide Web: Guru dalam Proses Pendidikan (Tafsir Manajemen Pendidikan Islam)

Slide web statis (HTML, CSS, JS, tanpa build). Bola dunia 3D memakai three.js dari CDN, ekspor PPT memakai PptxGenJS dari CDN.

## Kontrol
- Panah kiri dan kanan, Spasi, tombol di bawah, atau geser layar di HP
- Slide pembuka: seret bola dunia untuk memutarnya
- Slide ayat: ketuk frasa Arab bergaris putus untuk membuka kaidah linguistik dan pendapat mufasir
- Tombol N: menampilkan atau menyembunyikan naskah presenter (metode SOCIAL)
- Tombol Unduh di kanan atas: Unduh PDF (dialog cetak, pilih Simpan sebagai PDF) dan Unduh PPT

## Mengubah isi
- Naskah presenter: variabel `NT` di bagian script
- Kaidah linguistik dan pendapat mufasir per frasa: variabel `LW`
- Naskah berada di dalam file JavaScript, sehingga bisa terbaca lewat View Source. Untuk naskah yang benar-benar rahasia, hapus `NT` dari versi yang dipublikasikan.

## Deploy
1. Buat repo GitHub baru, lalu unggah isi folder ini (`index.html`, `assets/`, `README.md`).
2. Di vercel.com pilih Add New, Project, lalu impor repo tersebut.
3. Framework Preset: Other, tanpa build command, klik Deploy.
