# Roti Bakar Beverly Hills - Platform Pemasaran Digital

Hellaur, ini repositori untuk proyek website Roti Bakar Beverly Hills, dibangun sebagai tugas akhir mata kuliah **Pemasaran Digital**. Proyek ini berfungsi sebagai platform digital untuk meningkatkan kehadiran online bisnis F&B lokal melalui desain yang user-friendly, optimasi SEO, dan integrasi AI.

**➡️ Lihat Live Demo:** [**https://joyraphaela.github.io/beverlyhillsjogja/**](https://joyraphaela.github.io/beverlyhillsjogja/)

## ✨ Fitur Unggulan

Fitur utama platform ini meliputi:

* **Desain Responsif (Mobile-First):** Dirancang dengan pendekatan *mobile-first* menggunakan **Tailwind CSS** untuk memastikan pengalaman pengguna yang konsisten di semua ukuran layar.
* **UI/UX Interaktif:** Implementasi komponen interaktif seperti carousel dinamis, animasi transisi saat scroll, dan modal untuk meningkatkan *engagement* pengguna.
* **Asisten Chat Berbasis AI:** Integrasi **Google Gemini API** untuk menyediakan layanan pelanggan otomatis 24/7, mampu menjawab pertanyaan umum seputar produk dan operasional bisnis.
* **Mode Terang & Gelap:** Fungsionalitas *theme-switching* (Light/Dark) yang persisten menggunakan `localStorage` untuk kenyamanan visual pengguna.
* **Optimasi SEO & Media Sosial:** Struktur halaman dan meta-tags (termasuk Open Graph) telah dioptimalkan untuk visibilitas maksimum di mesin pencari dan saat dibagikan di media sosial.
* **Kinerja & Performa:** Fokus pada *load time* yang cepat melalui *lazy loading* untuk aset gambar dan iframe, serta *preloader* untuk transisi halaman yang mulus.
* **Sistem Ulasan Interaktif:** Sistem pengumpulan *feedback* pelanggan melalui formulir ulasan dengan rating bintang yang intuitif.

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun menggunakan teknologi front-end modern berikut:

* **HTML5 & CSS3:** Untuk struktur dan styling.
* **Tailwind CSS:** Framework CSS berbasis utilitas.
* **JavaScript (ES6+):** Untuk logika interaktif dan integrasi API.
* **Google Gemini API:** Untuk fungsionalitas asisten chat.
* **Font Awesome & Google Fonts:** Untuk ikonografi dan tipografi.

## 🚀 Konfigurasi & Instalasi

Untuk menjalankan proyek ini secara lokal:

1.  **Clone repositori:**
    ```bash
    git clone [https://github.com/joyraphaela/beverlyhillsjogja.git](https://github.com/joyraphaela/beverlyhillsjogja.git)
    ```

2.  **Konfigurasi Kunci API Gemini:**
    * Dapatkan kunci API gratis dari [**Google AI Studio**](https://aistudio.google.com/app/apikey).
    * Buka `index.html` dan ganti `"MASUKKAN_API_KEY_ANDA_DISINI"` dengan kunci API Anda pada baris berikut:
        ```javascript
        const apiKey = "MASUKKAN_API_KEY_ANDA_DISINI";
        ```

## 📂 Struktur Proyek

```
/
├── images/       # Aset gambar
├── index.html    # File utama HTML
└── README.md     # Dokumentasi proyek
```
