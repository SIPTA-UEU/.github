![Poster SIPTA](img\sipta.png)

# SIPTA - Sistem Informasi Pengelolaan Tugas Akhir

SIPTA adalah sebuah sistem informasi berbasis web yang dirancang untuk membantu pengelolaan tugas akhir mahasiswa di FASILKOM UEU.

## Fitur Utama

- **Pendaftaran**: Memudahkan mahasiswa dalam mengajukan sidang tugas akhir 1 & 2.
- **Penjadwalan**: Memudahkan kaprodi plotting dosen penguji, dosen penguji menentukan waktu sidang, dan mahasiswa menerima informasi jadwal sidang tugas akhir.
- **Revisi**: Memudahkan dosen memberi revisi dan mahasiswa menerima revisi.
- **Penilaian**: Memudahkan dosen memberi nilai dan mahasiswa menerima nilai.
- **Lembar Revisi**: Memudahkan menerima dan mencetak revisi, serta menjadi bukti pencairan gaji.
- **Lembar Acara**: Memudahkan menerima dan mencetak nilai, serta menjadi bukti pencairan gaji.

## Teknologi yang Digunakan

- **Frontend**: [Next.js](https://nextjs.org/) + [React.js](https://react.dev/)
- **Backend & Database**: [Firebase](https://firebase.google.com/)

## Instalasi dan Menjalankan Proyek

1. Clone repositori ini:
   ```sh
   git clone https://github.com/SIPTA-UEU/sipta.git
   ```
2. Masuk ke direktori proyek:
   ```sh
   cd sipta
   ```
3. Install dependensi:
   ```sh
   npm install
   ```
4. Jalankan proyek:
   ```sh
   npm run dev
   ```
5. Akses aplikasi di `http://localhost:3000`

## Konfigurasi Firebase

1. Buat proyek di [Firebase Console](https://console.firebase.google.com/).
2. Tambahkan aplikasi web dan salin konfigurasi Firebase.
3. Buat file `.env.local` di root proyek dan tambahkan konfigurasi berikut:
   ```env
   NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
   NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
   ```

## Creator

SIPTA dikembangkan oleh **Jenyta Primaranti**.


### Kontak
- **LinkedIn**: [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://www.linkedin.com/in/jenytaprimaranti)
- **ORCID ID**: [![ORCID](https://img.shields.io/badge/ORCID-Profile-green?logo=orcid)](https://orcid.org/0000-0000-0000-0000)

## Lisensi

Proyek ini dilisensikan di bawah **MIT License**. Lihat file `LICENSE` untuk detail lebih lanjut.

---

Terima kasih telah mengunjungi proyek ini! Jika ada pertanyaan atau masukan, silakan hubungi saya.