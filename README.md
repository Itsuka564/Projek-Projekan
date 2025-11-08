# 🗓️ Kalender Interaktif & To-Do List

Sebuah aplikasi *web-app* mini yang menggabungkan kalender bulanan interaktif dengan manajemen tugas (to-do list). Dibuat murni menggunakan HTML, CSS (dengan Variabel CSS), dan JavaScript (ES6+), dan memanfaatkan `localStorage` untuk menyimpan data tugas dan preferensi tema.

Proyek ini adalah evolusi dari *to-do list* sederhana menjadi *planner* harian yang fungsional.

---

## 📸 Pratinjau (Preview)

[Ganti bagian ini dengan screenshot aplikasi Anda. Rekomendasi: Tampilkan mode terang dan gelap berdampingan!]

*(Contoh gambar placeholder - hapus baris ini)*
![Contoh Tampilan Aplikasi](https://via.placeholder.com/800x400.png?text=Pratinjau+Aplikasi+Kalender+Anda)

---

## ✨ Fitur Utama

* **Kalender Dinamis:** Menampilkan kalender bulanan yang dapat dinavigasi (bulan-sebelumnya/berikutnya) dengan penanda hari ini.
* **Manajemen Tugas:** Tambah, hapus, dan tandai tugas selesai untuk *setiap tanggal* yang dipilih.
* **Tenggat Waktu (Deadline):** Atur tanggal *dan jam* tenggat untuk setiap tugas.
* **Status Tugas:** Visual otomatis untuk tugas yang **Terlewat** (Overdue) atau tenggat **Hari Ini** (Due Today) dengan perbandingan waktu yang presisi.
* **Ganti Tema:** Tombol *toggle* untuk beralih antara **Mode Terang** (Light) dan **Mode Gelap** (Dark).
* **Penyimpanan Lokal:** Semua tugas dan pilihan tema disimpan di `localStorage` browser, sehingga data tidak hilang saat halaman di-*refresh*.
* **Desain Responsif:** Tata letak yang rapi menggunakan CSS Flexbox & Grid.
* **Single File:** Seluruh aplikasi (HTML, CSS, JS) dimuat dalam satu file `index.html`.

---

## 💻 Teknologi yang Digunakan

* **HTML5:** Untuk struktur konten.
* **CSS3:** Untuk *styling* dan tema.
    * CSS Variables (untuk *theming*).
    * Flexbox & Grid (untuk *layout*).
    * Animasi & Transisi sederhana.
* **JavaScript (ES6+):** Untuk semua logika.
    * Manipulasi DOM (Dynamic HTML).
    * Manajemen *Event* (click, keyup).
    * Manajemen `Date()` & `new Date()`.
    * `localStorage` (Web Storage API) untuk persistensi data.

---

## 🚀 Cara Menjalankan

Ada dua cara untuk menjalankan aplikasi ini:

### 1. (Rekomendasi) Menggunakan GitHub Pages

Cara termudah untuk melihatnya secara *live* adalah dengan mengaktifkan GitHub Pages di *repository* ini:

1.  Pergi ke *repository* Anda di GitHub.
2.  Klik **Settings** > **Pages** (di sidebar kiri).
3.  Di bawah "Build and deployment", pilih *Source* ke **Deploy from a branch**.
4.  Pilih *branch* `main` (atau `master`) dan folder `/ (root)`.
5.  Klik **Save**.
6.  Tunggu beberapa menit dan kunjungi `https://[NAMA_USER_ANDA].github.io/[NAMA_REPO_ANDA]/`

### 2. Secara Lokal

1.  *Clone repository* ini:
    ```bash
    git clone [https://github.com/](https://github.com/)[NAMA_USER_ANDA]/[NAMA_REPO_ANDA].git
    ```
2.  Masuk ke direktori proyek.
3.  Cukup klik ganda file `(nama-file-Anda).html` (misal: `kalender_final.html`) untuk membukanya di browser favorit Anda.

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah [Lisensi MIT](LICENSE).
