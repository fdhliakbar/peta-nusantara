# Peta Nusantara <img src="./src/assets/images/Cat.gif" alt="KON Group Gif" height="45px">

Selamat datang di **Peta Nusantara**! Ini adalah proyek mandiri saya dalam bentuk Website yang dirancang untuk membantu Anda menemukan rute terpendek dan paling efisien di seluruh wilayah Nusantara.
Website ini memberikan solusi navigasi yang optimal untuk berbagai kebutuhan perjalanan Anda, mulai dari perjalanan pribadi hingga rencana logistik komersial.

## Daftar Isi

- [Peta Nusantara ](#peta-nusantara-)
  - [Daftar Isi](#daftar-isi)
  - [Fitur](#fitur)
  - [Cara Instalasi](#cara-instalasi)
  - [Teknologi yang Digunakan](#teknologi-yang-digunakan)
  - [Kontribusi](#kontribusi)
  - [Lisensi](#lisensi)
  - [FAQ](#faq)
    - [Apa tujuan dari Peta Nusantara?](#apa-tujuan-dari-peta-nusantara)
    - [Bagaimana cara kerja rute terpendek?](#bagaimana-cara-kerja-rute-terpendek)
  - [Alur Program](#alur-program)
  - [Pembagian Job](#pembagian-job)
  - [Kontak](#kontak)

## Fitur

- **Pencarian Rute Terpendek**: Temukan rute tercepat antara dua titik.
- **Pilihan Rute Alternatif**: Berikan beberapa pilihan rute dengan waktu tempuh yang berbeda.
- **Penyesuaian Preferensi**: Sesuaikan rute berdasarkan preferensi pengguna seperti jalan tol, tanpa jalan tol, dan sebagainya.
- **Peta Interaktif**: Peta dinamis dengan fitur zoom dan pan untuk melihat detail wilayah.
- **Informasi Lalu Lintas Real-time**: Dapatkan update lalu lintas secara real-time untuk perencanaan perjalanan yang lebih baik.
- **Asisten Perjalanan Virtual(Soryu)**: Menjawab pertanyaan seputar rute dan lokasi. Memberikan rekomendasi tempat wisata dan kuliner dan membantu menyediakan informasi seputar lalu lintas perjalanan.
- **Penerjemahan Bahasa Real-Time**: Terjemahkan teks dan suara secara real-time untuk membantu pengguna yang tidak berbahasa Indonesia.

## Cara Instalasi

1. **Kloning Repositori**:

   ```bash
   git clone https://github.com/username/peta-nusantara.git
   cd peta-nusantara
   ```

2. **Instalasi Dependensi**:
   Pastikan Anda memiliki [Node.js](https://nodejs.org/) dan [npm](https://www.npmjs.com/) yang sudah terinstal di sistem Anda. Lalu, jalankan:

   ```bash
   npm install
   ```

3. **Konfigurasi Lingkungan**:
   Buat file `.env` di root direktori dan tambahkan konfigurasi yang diperlukan seperti kunci API untuk peta dan informasi lalu lintas.

   Contoh `.env`:

   ```env
   MAP_API_KEY=your_map_api_key_here
   TRAFFIC_API_KEY=your_traffic_api_key_here
   ```

4. **Jalankan Aplikasi**:
   ```bash
   npm start
   ```

## Teknologi yang Digunakan

- **Front-end**: [React.js](https://reactjs.org/), [Leaflet](https://leafletjs.com/)
- **Back-end**: [Node.js](https://nodejs.org/), [Express.js](https://expressjs.com/)
- **Database**: [MongoDB](https://www.mongodb.com/)
- **API**: Peta dan lalu lintas dari Google Maps API

## Kontribusi

Kami menerima kontribusi dari siapa saja yang tertarik untuk mengembangkan proyek ini lebih lanjut.

## Lisensi

Proyek ini dilisensikan di bawah lisensi MIT - lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.

## FAQ

### Apa tujuan dari Peta Nusantara?

Peta Nusantara bertujuan untuk menyediakan layanan navigasi yang efektif dan efisien di wilayah Nusantara, membantu pengguna menemukan rute terpendek dan optimal untuk perjalanan mereka.

### Bagaimana cara kerja rute terpendek?

Kami menggunakan algoritma Dijkstra untuk menghitung rute terpendek berdasarkan data peta dan lalu lintas yang terkini.

## Alur Program

- Pengguna
- Aplikasi

## Pembagian Job

| Programmer                                                          | Laporan | UI/UX |
| ------------------------------------------------------------------- | ------- | ----- |
| [Muhamad Fadhli Akbar](https://github.com/fdhliakbar "fadhliakbar") | Evinda  |       |
|                                                                     | Nadya   |       |
|                                                                     | Qori    |       |

## Kontak

<p>Jika Anda memiliki pertanyaan atau membutuhkan
bantuan, silakan hubungi kami melalui email di
<a href="mailto:fadhliakbar125@gmail.com">fadhliakbar125@gmail.com</a>
</p>

---

<p>
Demikian Program yang telah kami buat, kami akan terus melakukan <b>improve</b> dan <b>inovasi</b> agar program kami dapat berguna bagi banyak orang:).
</p>

<img src="./src/assets/images/roxy-gif.gif" alt="Roxy Top Waifu" >
