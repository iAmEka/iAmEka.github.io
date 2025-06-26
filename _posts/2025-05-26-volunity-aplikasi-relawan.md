---
title: "Volunity: Aplikasi Manajemen Relawan dan Event"
date: 2025-05-26 10:00:00 +0800
categories: [Portofolio, Mobile Development]
tags: [Android, Java, SQLite, Relawan, Event, API]
image: /assets/img/image.png # Opsional: gambar thumbnail untuk postingan
---

Ini adalah **Volunity**, sebuah aplikasi Android yang saya kembangkan menggunakan **Android Studio** dan bahasa pemrograman **Java**. Volunity dirancang untuk memfasilitasi interaksi antara penyelenggara kegiatan (Organizer) dan para relawan (Volunteer), dengan data yang disimpan secara lokal menggunakan **SQLite database**.

Aplikasi ini memiliki dua jenis pengguna utama:
* **Organizer:** Bertanggung jawab untuk membuat, mengelola, dan mempublikasikan event atau kegiatan yang membutuhkan relawan.
* **Volunteer:** Dapat mencari, melihat detail event, serta mendaftar atau melamar untuk kegiatan yang diminati.

## Fitur Utama:
* **Dua Peran Pengguna:** Memisahkan fungsionalitas untuk Organizer dan Volunteer.
* **Manajemen Event (Organizer):** Organizer dapat membuat event baru, menambahkan detail, tanggal, lokasi, dan kebutuhan relawan.
* **Pendaftaran Relawan (Volunteer):** Volunteer dapat menelusuri daftar event yang tersedia dan mendaftar untuk berpartisipasi.
* **Profil Pengguna:** Setiap pengguna (Organizer dan Volunteer) memiliki profil sendiri untuk mengelola informasi pribadi.
* **Database Lokal:** Penyimpanan data yang efisien menggunakan SQLite.
* **Integrasi Wilayah:** Penggunaan API eksternal untuk informasi wilayah.
* **Antarmuka Pengguna Intuitif:** Desain yang bersih dan mudah digunakan untuk kedua jenis pengguna.

## Teknologi yang Digunakan:
* **Bahasa Pemrograman:** Java
* **IDE:** Android Studio
* **Database:** SQLite
* **API Eksternal:** * API dari GitHub (untuk data wilayah/lokasi)
    
* **Libraries Penting:**
    * Retrofit (untuk permintaan API)
    * Glide/Picasso (untuk memuat gambar, jika ada)
    * Gson/Jackson (untuk parsing JSON dari API)
    

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
    object-fit: contain; /* Gambar akan menyesuaikan tanpa terpotong */
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
        <img src="/assets/img/homevolunity.png" alt="Splash Screen Volunity">
        <figcaption>Splash screen aplikasi Volunity.</figcaption>
    </figure>
    <figure class="gallery-item">
        <img src="/assets/img/dashboardorg.png" alt="Dashboard Organizer">
        <figcaption>Tampilan dashboard untuk Organizer.</figcaption>
    </figure>
    <figure class="gallery-item">
        <img src="/assets/img/volunterdash.png" alt="Daftar Event Relawan">
        <figcaption>Daftar event yang tersedia untuk relawan.</figcaption>
    </figure>
    <figure class="gallery-item">
        <img src="/assets/img/detail.png" alt="Detail Event">
        <figcaption>Halaman detail informasi event.</figcaption>
    </figure>
    <figure class="gallery-item">
        <img src="/assets/img/profilevol.png" alt="Halaman Profil Pengguna">
        <figcaption>Halaman profil untuk mengelola informasi pengguna.</figcaption>
    </figure>
</div>

---

## Link Proyek:
* [Repositori GitHub](https://github.com/iAmEka/Volunity)


---

## Kontributor:
Berikut adalah anggota tim yang berkontribusi dalam pengembangan aplikasi Volunity:
* [muhammad raihan](https://github.com/ivy799)
* [harmelia](https://github.com/harmeliayra17)


---