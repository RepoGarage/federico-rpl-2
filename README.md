# Webinar UKDC - RPL2

---

## Link Repositori

[Menuju Repositori](https://github.com/One-Of-Those-Organization/webinar-rpl)

## Anggota Kelompok

- Federico Matthew Pratama
- Fernando Perry
- Vincentius Johanes Lwie Jaya

---

## Prasyarat

Sebelum menjalankan proyek ini, pastikan Anda telah menginstal:

### Node.js dan npm

1. **Unduh dan Instal Node.js:**

   - Kunjungi [https://nodejs.org/](https://nodejs.org/)
   - Pilih versi LTS (Long Term Support)
   - Jalankan installer dan ikuti petunjuk instalasi
   - npm akan terinstal otomatis bersama Node.js

2. **Cek Instalasi:**
   ```bash
   node --version
   npm --version
   ```
   Jika sudah terinstal dengan benar, kedua perintah di atas akan menampilkan versi yang terpasang.

### Go (Untuk Backend)

- Unduh dan instal Go dari [https://golang.org/dl/](https://golang.org/dl/)
- Ikuti panduan instalasi sesuai sistem operasi Anda

---

## Cara Menjalankan Proyek (React + Vite + Backend Go)

1. **Frontend (React + Vite):**

   - Jalankan perintah berikut untuk memasang dependensi:
     ```bash
     npm install
     ```
   - Setelah selesai, build project dengan:
     ```bash
     npm run build
     ```
   - Untuk menjalankan server pengembangan:
     ```bash
     npm run dev
     ```
   - Aplikasi dapat diakses di `http://localhost:5173`

2. **Backend (Go):**
   - Masuk ke direktori `backend`:
     ```bash
     cd backend
     ```
   - Build aplikasi:
     ```bash
     go build .
     ```
   - Jalankan backend:
     ```bash
     go run .
     ```
   - Backend berjalan di `https://localhost:3000`

---

## Catatan

- Pastikan Node.js dan Go sudah terinstal dengan benar sebelum memulai.
- Jika ada kendala saat instalasi atau menjalankan project, silakan cek dokumentasi resmi atau hubungi anggota kelompok.

---

Selamat mencoba dan semoga bermanfaat!
