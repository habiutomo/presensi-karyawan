# AttendEase - Sistem Absensi Karyawan

Sistem absensi karyawan ini adalah aplikasi web yang membantu perusahaan untuk melacak kehadiran karyawan, mengelola permohonan cuti, dan menghasilkan laporan absensi.

## Fitur Utama

- **Absensi Check-In/Check-Out**: Karyawan dapat check-in dan check-out untuk mencatat kehadiran harian mereka.
- **Manajemen Karyawan**: Admin dapat menambah, mengedit, dan menghapus data karyawan.
- **Permohonan Cuti**: Karyawan dapat mengajukan permohonan cuti yang dapat disetujui oleh manajer atau admin.
- **Laporan & Analitik**: Menghasilkan laporan kehadiran dan statistik untuk membantu pengambilan keputusan.
- **Peran Pengguna**: Mendukung beberapa peran (admin, manajer, karyawan) dengan hak akses yang berbeda.

## Teknologi

- **Frontend**: React, TailwindCSS, Shadcn UI
- **Backend**: Node.js, Express
- **Database**: In-memory database (untuk pengembangan)
- **Autentikasi**: Passport.js dengan strategi lokal

## Penggunaan

1. Clone repositori ini
2. Install dependensi dengan `npm install`
3. Jalankan aplikasi dengan `npm run dev`
4. Akses aplikasi di browser melalui `http://localhost:5000`

## Pengembangan

Proyek ini menggunakan Vite sebagai bundler dan alat pengembangan. Struktur proyek terdiri dari:

- `client/`: Kode frontend React
- `server/`: Kode backend Express
- `shared/`: Skema dan tipe data yang digunakan oleh frontend dan backend

## Akun Default

Saat pertama kali menjalankan aplikasi, Anda dapat membuat akun baru melalui halaman registrasi.

## Alur Kerja

1. Login ke sistem menggunakan kredensial Anda
2. Karyawan dapat melakukan check-in di pagi hari dan check-out di sore hari
3. Admin dan manajer dapat melihat data kehadiran semua karyawan
4. Karyawan dapat mengajukan permohonan cuti yang akan ditinjau oleh manajer
5. Admin dapat mengelola seluruh data karyawan dan menghasilkan laporan

## Kontribusi

Kontribusi terhadap proyek ini sangat dihargai. Silakan buat fork dari repositori ini dan kirimkan pull request dengan perubahan Anda.

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).