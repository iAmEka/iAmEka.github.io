---
title: "Apolib: Aplikasi Informasi Obat Lengkap"
date: 2025-06-26 10:00:00 +0800
categories: [Portofolio, Mobile Development]
tags: [Android, Java, API, Informasi Obat, OpenFDA]
image: /assets/img/logo.png
---

Ini adalah **Apolib**, sebuah aplikasi informasi obat lengkap yang saya kembangkan menggunakan **Android Studio** dan bahasa pemrograman **Java**. Apolib dirancang untuk memberikan akses mudah kepada pengguna terhadap informasi detail berbagai jenis obat, dengan memanfaatkan data dari **OpenFDA**. Pengguna dapat mencari, menyimpan obat favorit, serta memfilter daftar obat berdasarkan kriteria tertentu.

## Fitur Utama:
* **Pencarian Obat Komprehensif:** Akses informasi detail dari berbagai obat menggunakan data akurat dari OpenFDA.
* **Obat Favorit:** Simpan obat-obatan yang sering dicari atau disukai untuk akses cepat.
* **Daftar Obat Interaktif:** Tampilkan daftar lengkap obat yang dapat dijelajahi.
* **Filter Cerdas Berdasarkan Jenis Resep:** Saring daftar obat berdasarkan kategori:
    * Obat Bebas (Tidak Butuh Resep Dokter)
    * Obat Resep (Membutuhkan Resep Dokter)
    * Obat Terapi (Untuk Kebutuhan Terapi Khusus)
* **Manajemen Profil Pengguna:** Pengguna dapat mengelola informasi profil pribadi mereka dalam aplikasi.
* **Antarmuka Pengguna Intuitif:** Desain yang bersih dan ramah pengguna untuk pengalaman navigasi yang lancar.

## Teknologi yang Digunakan:
* **Bahasa Pemrograman:** Java
* **IDE:** Android Studio
* **API Eksternal:** OpenFDA (sebagai sumber data obat)
* **Database:** SQLite untuk penyimpanan data lokal seperti obat favorit
* **Libraries Penting:** 
    * Retrofit (untuk permintaan API ke OpenFDA)
    * Glide/Picasso (untuk memuat gambar, jika ada)
    * Gson/Jackson (untuk parsing JSON dari API)
    * (dan lain lain )

## Tampilan Aplikasi:

<style>
.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); /* 3 kolom responsif */
    gap: 20px; /* Jarak antar gambar */
    margin-bottom: 30px;
}
.gallery-item {
    text-align: center;
    background: #fff;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    display: flex;
    flex-direction: column;
    height: 100%; /* Memastikan item memiliki tinggi yang sama */
}
.gallery-item img {
    max-width: 100%; /* Lebar maksimum 100% dari kontainer kolom */
    height: auto; /* Tinggi disesuaikan secara proporsional */
    object-fit: contain; /* PENTING: Gambar akan menyesuaikan tanpa terpotong */
    border-bottom: 1px solid #eee;
    padding: 10px; /* Opsional: ruang di sekitar gambar di dalam bingkai */
}
.gallery-item figcaption {
    padding: 15px;
    font-size: 0.9em;
    color: #555;
    flex-grow: 1; /* Memastikan caption memenuhi sisa ruang */
    display: flex;
    align-items: center;
    justify-content: center;
}
@media (max-width: 768px) {
    .gallery-grid {
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); /* 2 kolom di layar kecil */
    }
}
@media (max-width: 480px) {
    .gallery-grid {
        grid-template-columns: 1fr; /* 1 kolom di layar sangat kecil */
    }
}
</style>

<div class="gallery-grid">
    <figure class="gallery-item">
        <img src="/assets/img/home.jpg" alt="Halaman Utama Aplikasi Apolib">
        <figcaption>Halaman utama Aplikasi Apolib menampilkan daftar obat.</figcaption>
    </figure>
    <figure class="gallery-item">
        <img src="/assets/img/homefilter.jpg" alt="Tampilan Filter Obat">
        <figcaption>Tampilan filter obat berdasarkan jenis resep dan terapi.</figcaption>
    </figure>
    <figure class="gallery-item">
        <img src="/assets/img/infoObat.jpg" alt="Halaman Detail Obat">
        <figcaption>Halaman detail yang menampilkan informasi lengkap tentang obat.</figcaption>
    </figure>
    <figure class="gallery-item">
        <img src="/assets/img/profileapolip.jpg" alt="Halaman Profil Pengguna">
        <figcaption>Halaman profil tempat pengguna dapat mengelola informasi mereka.</figcaption>
    </figure>
    </div>

## Link Proyek:
* [Repositori GitHub](https://github.com/iAmEka/Apolib-App)


---