# 🏫 Dashboard PPDB — SMK Budi Bakti Ciwidey



Landing page **Dashboard PPDB (Penerimaan Peserta Didik Baru) SMK Budi Bakti Ciwidey Tahun Ajaran 2026/2027** yang modern, responsif, dan interaktif. Dibangun dengan tampilan antarmuka berbasis aplikasi mobile-first yang menampilkan seluruh fitur penting mulai dari profil sekolah, program keahlian, hingga formulir pendaftaran online.



Proyek ini dibangun menggunakan arsitektur frontend murni berbasis **Vanilla JS** dan **CSS Custom** tanpa dependensi framework berat, menjamin performa muat halaman yang instan, efisiensi tinggi, dan kemudahan deployment di berbagai platform hosting statis.



---



## 🚀 Fitur Unggulan Proyek



### 1. Navigasi & Layout Utama

*   **Navbar Atas:** Header navigasi bersih dengan logo sekolah, nama halaman, dan elemen profil pengguna berbentuk pill yang elegan.
*   **Search Bar:** Kolom pencarian terpusat di bawah navbar untuk memudahkan navigasi konten.
*   **Bottom Fixed Navigation Bar:** Navigasi bawah tetap (*sticky*) bergaya aplikasi mobile dengan 5 tab: Beranda, Profil, PPDB, Berita, dan Kontak — masing-masing dapat membuka modal konten yang relevan.



### 2. Hero Banner Dinamis

*   **Gradient Banner Premium:** Tampilan hero banner dengan gradasi biru tua yang elegan, lengkap dengan teks sambutan, judul sekolah, dan deskripsi singkat.
*   **Dekorasi Emoji Besar:** Elemen dekorasi emoji 🏫 berukuran besar dengan opasitas rendah sebagai latar belakang artistik banner.



### 3. Program Keahlian Terakreditasi

Sekolah membuka tiga program keahlian unggulan yang dapat dipilih oleh calon peserta didik baru:

*   🎨 **Desain Komunikasi Visual (DKV)**
    Berfokus pada pembuatan ilustrasi, sketsa, desain grafis, dan komunikasi visual untuk media digital maupun cetak.

*   📈 **Pemasaran (Bisnis Daring dan Pemasaran / BDP)**
    Berfokus pada strategi bisnis digital, manajemen penjualan, dan digital marketing di era e-commerce.

*   💻 **Pengembangan Perangkat Lunak dan Gim (PPLG / Rekayasa Perangkat Lunak)**
    Berfokus pada pemrograman, pembuatan aplikasi, dan pengembangan game berbasis teknologi terkini.

> Informasi lebih lanjut tentang masing-masing jurusan dapat dilihat melalui:
> - 📸 Instagram Resmi Sekolah: [@info.smkbudibakticiwidey](https://www.instagram.com/info.smkbudibakticiwidey/)
> - 🔗 Linktree: [linktr.ee/zev134n](https://linktr.ee/zev134n)
> - 🌐 Portal SPMB Jawa Barat: [informasi-spmb.site](https://informasi-spmb.site/spmb/jawa-barat/sekolah/20227934)



### 4. Grid 8 Fitur Aplikasi

Grid 4 kolom (responsif menjadi 2 kolom di tablet dan 1 kolom di HP) yang menampilkan seluruh fitur utama dashboard:

1.  **Beranda** — Informasi utama sekolah yang selalu terupdate.
2.  **Profil Sekolah** — Sejarah, visi misi, statistik pencapaian, dan keunggulan sekolah.
3.  **Kompetensi Keahlian** — Detail tiga jurusan unggulan yang tersedia.
4.  **Pendaftaran** — Formulir PPDB online lengkap dengan integrasi Google Maps.
5.  **Berita & Kegiatan** — Update terbaru seputar prestasi dan kegiatan sekolah.
6.  **Galeri** — Dokumentasi visual kegiatan dan fasilitas kampus.
7.  **Informasi PPDB** — Jadwal, alur, syarat, dan catatan penting pendaftaran.
8.  **Kontak & Lokasi** — Akses cepat ke WhatsApp admin dan navigasi Google Maps.



### 5. Bottom CTA Banner

*   **Spanduk Ajakan Daftar:** Banner gradasi biru-hijau di bagian bawah konten dengan ikon toga 🎓, teks motivasi, dan tombol **"Mulai Daftar"** yang langsung membuka formulir pendaftaran.



### 6. Sistem Modal Portal

*   **8 Konten Modal Lengkap:** Setiap fitur membuka jendela modal terpusat yang menarik dengan konten berbeda dan spesifik.
*   **Animasi Fade Halus:** Modal muncul dan menghilang dengan transisi opacity yang lembut disertai efek *backdrop blur*.
*   **Auto-Close on Overlay Click:** Pengguna dapat menutup modal dengan mengklik area luar jendela.
*   **Konten Modal Dinamis:**
    -   **Profil:** Grid statistik sekolah (tahun berdiri, jumlah alumni, jurusan, akreditasi) dan daftar keunggulan.
    -   **Kompetensi:** Kartu detail untuk jurusan DKV, BDP, dan PPLG.
    -   **Pendaftaran:** Formulir multi-field lengkap (nama, NISN, WhatsApp, pilihan jurusan, alamat) dengan tombol integrasi peta Google Maps.
    -   **Berita:** Daftar berita terbaru sekolah yang berurutan berdasarkan waktu.
    -   **Galeri:** Grid placeholder dokumentasi foto fasilitas dan kegiatan sekolah.
    -   **Informasi PPDB:** Alur pendaftaran bertahap dalam format list terstruktur dengan notifikasi info.
    -   **Kontak:** Dua opsi kontak interaktif — WhatsApp langsung dan navigasi Google Maps.



---



## 🛠️ Spesifikasi Teknologi



*   **HTML5:** Struktur semantik penuh untuk performa SEO dan aksesibilitas (*accessibility*) yang optimal.
*   **CSS3 Custom:** Styling manual dengan variabel warna, grid layout, flexbox, dan efek glassmorphism modern tanpa ketergantungan framework CSS eksternal.
*   **Vanilla JavaScript:** Logika fungsionalitas murni (modal toggle, navigasi, form submit, integrasi Maps) tanpa framework eksternal demi kecepatan optimal.
*   **Google Fonts:** Tipografi modern menggunakan font *Poppins* untuk tampilan yang bersih dan profesional.
*   **Responsive Design:** Layout adaptif penuh untuk semua ukuran layar — dari smartphone (≤576px), tablet (≤992px), hingga desktop.



---



## 📁 Struktur Folder Proyek



```bash
ppdb-dashboard/
├── index.html          # File Tunggal Dashboard PPDB (All-in-One)
├── prd.md              # Product Requirement Document    
└── README.md           # Dokumentasi Utama Proyek (File Ini)
```



> Seluruh aset, style CSS, dan logika JavaScript diintegrasikan langsung dalam satu berkas `index.html` untuk kemudahan deployment dan distribusi.



---



## 💻 Cara Menjalankan Proyek Secara Lokal



Karena proyek ini adalah frontend statis murni tanpa memerlukan server build atau proses kompilasi, Anda dapat menjalankannya dengan sangat mudah:



### Opsi A: Buka Langsung (Tanpa Server)

1.  Klik dua kali berkas `index.html` pada komputer Anda.
2.  Berkas akan langsung terbuka dengan sempurna di peramban web (Google Chrome, Microsoft Edge, Safari, Firefox, dll.).



### Opsi B: Menggunakan Local Development Server (Direkomendasikan)

Untuk mendapatkan pengalaman yang lebih optimal dan konsisten lintas browser, disarankan menjalankan server lokal sederhana:

*   **Jika menggunakan VS Code:** Instal ekstensi **Live Server**, buka folder proyek ini, kemudian klik tombol **"Go Live"** di bar status bawah VS Code.
*   **Menggunakan Python (Terminal):**
    ```bash
    python -m http.server 8000
    ```
    Buka `http://localhost:8000` di peramban Anda.
*   **Menggunakan Node.js / NPM (npx):**
    ```bash
    npx serve .
    ```
    Buka alamat yang tertera di terminal Anda.



---



## 📝 Catatan Kustomisasi



1.  **Nomor Kontak WhatsApp Admin:**
    Untuk mengubah tujuan nomor admin pada tombol kontak WhatsApp di modal "Kontak & Lokasi", cari elemen `<a>` dengan atribut `href` yang dimulai dengan `https://wa.me/` di dalam `index.html` dan perbarui nomor `6281234567890` serta parameter teks pesan pembukaannya.

2.  **Lokasi Sekolah di Google Maps:**
    Tautan Google Maps pada fungsi `openGoogleMaps()` saat ini mengarah ke pencarian `SMK+Budi+Bakti+Ciwidey`. Anda dapat menggantinya dengan koordinat GPS yang presisi untuk akurasi navigasi yang lebih baik.

3.  **Data Berita & Konten:**
    Seluruh konten (berita, statistik profil, info PPDB) dapat diperbarui langsung dengan mengedit objek `listKonten` di dalam blok `<script>` pada `index.html`.



---



*Dikembangkan secara profesional dan didedikasikan untuk peningkatan mutu sistem informasi penerimaan peserta didik baru di **SMK Budi Bakti Ciwidey**.*
