# Pancasila dalam Ilmu: Teknologi

Edukasi Penggunaan Teknologi yang Bijak pada Siswa SMP Sapta Marga Cibinong.

Website dokumentasi kegiatan Pengabdian kepada Masyarakat Kelompok 14, Program Studi Ilmu Komunikasi, Universitas Bina Sarana Informatika (UBSI).

## Isi repository
- Halaman responsif dengan navigasi, profil kegiatan, naskah siaran pers, hasil pengamatan, galeri 5 foto, dan kontak.
- Galeri dengan dialog pembesaran foto; tutup dengan tombol Tutup atau Esc.
- PDF siaran pers asli tersedia pada tombol unduh.
- HTML, CSS, dan JavaScript biasa: tidak memerlukan instalasi, build, CDN, atau font eksternal.

## Publikasi ke GitHub Pages
1. Ekstrak paket ZIP ini.
2. Masuk ke GitHub dan buat repository bernama `pancasila-teknologi-sapta-marga` (disarankan Public).
3. Pilih **Add file → Upload files**, lalu unggah seluruh ISI folder hasil ekstraksi, termasuk folder `assets` dan `documents`. Pastikan `index.html` ada di root repository, bukan di subfolder tambahan.
4. Simpan dengan **Commit changes**. File `.nojekyll` kosong bersifat tambahan; apabila tersembunyi/tidak terunggah, website ini tetap dapat digunakan tanpa file tersebut.
5. Buka **Settings → Pages**. Di **Build and deployment**, pilih **Deploy from a branch**.
6. Pilih branch yang memuat file (umumnya `main`) dan folder `/(root)`, lalu **Save**.
7. Tunggu proses publikasi selesai. Gunakan tautan situs yang ditampilkan oleh GitHub Pages. URL bergantung pada username dan nama repository yang digunakan.

Alternatif dengan Git (buat repository kosong terlebih dahulu; ganti USERNAME):
```sh
git init
git add .
git commit -m "Tambahkan website PKM Kelompok 14 UBSI"
git branch -M main
git remote add origin https://github.com/USERNAME/pancasila-teknologi-sapta-marga.git
git push -u origin main
```
Jalankan dari folder yang berisi index.html. Aktifkan Pages melalui Settings setelah push.

## Pratinjau lokal
Buka `index.html` langsung di peramban, atau jalankan `python -m http.server 8000` dari folder repository lalu buka `http://localhost:8000`.

## Penyuntingan
- `index.html`: judul, naskah, statistik, kontak, keterangan foto.
- `assets/style.css`: warna, tipografi, tata letak dan tampilan seluler.
- `assets/script.js`: navigasi seluler dan pembesaran galeri.
- `assets/images/`: lima foto yang diberikan pengguna.
- `documents/press-release.pdf`: naskah PDF asli.

## Sumber dan batasan
Konten bersumber dari naskah siaran pers dan lima foto yang disediakan pengguna. Naskah berita dipertahankan; ringkasan dan judul bagian merupakan adaptasi editorial. Waktu mengikuti naskah: Oktober 2026, tanpa menambahkan tanggal pasti. Angka 8 mengacu pada mahasiswa pelaksana, bukan jumlah siswa. Skor 1–5 merupakan pengamatan awal tim, bukan bukti perubahan jangka panjang; naskah tidak merinci instrumen atau jumlah peserta yang dinilai.

Halaman contoh yang diberikan tidak berhasil dimuat saat pembuatan. Desain paket ini dibuat mandiri, bukan salinan identik halaman tersebut. Tidak ada logo resmi yang ditambahkan.

## Pemeriksaan sebelum publikasi
- Pastikan nama, kontak, naskah, dan keterangan foto benar serta diizinkan untuk dipublikasikan.
- Pastikan izin publikasi foto siswa, termasuk persetujuan sekolah dan orang tua/wali sesuai kebutuhan, telah diperoleh. Paket ini tidak menyatakan bahwa persetujuan tersebut sudah ada.
- PDF asli memuat kontak yang sama; bila menghapus kontak publik, perbarui juga PDF dan README.
- Jangan unggah informasi sensitif: repository publik dapat dilihat siapa saja.
- Uji tautan, unduhan PDF, menu seluler, dan galeri setelah situs terbit.

## Kontak dalam naskah
Nathan Izz Wardhana — Ketua Pelaksana Kelompok 14  
WhatsApp: +62 857-7101-2668  
Email: natanizzwardana@gmail.com

## Hak penggunaan
Foto dan dokumen mengikuti hak pemilik masing-masing. Tidak ada lisensi terbuka untuk media atau naskah yang diasumsikan oleh paket ini.
