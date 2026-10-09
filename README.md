[readme_pertemuan_4.md](https://github.com/user-attachments/files/33244517/readme_pertemuan_4.md)
# Eksplorasi SCSS - Tugas Pemrograman Web (Pertemuan 4)

Repository ini berisi *source code* untuk tugas mata kuliah Pemrograman Web pada pertemuan keempat. Pada proyek ini, fokus pembelajaran beralih dari CSS murni (Vanilla CSS) ke penggunaan **SCSS (Sassy CSS)**, yaitu sebuah *CSS preprocessor* yang memungkinkan penulisan kode *styling* menjadi lebih rapi, efisien, dan mudah dipelihara.

## 📝 Deskripsi Proyek

Proyek ini mendemonstrasikan bagaimana fitur-fitur lanjutan dari SCSS digunakan untuk membangun antarmuka website. Dengan SCSS, penulisan gaya (style) tidak lagi menumpuk dan repetitif. Proyek ini mengimplementasikan konsep-konsep inti SCSS untuk menghasilkan *file* CSS akhir yang akan dibaca oleh *browser*.

## ✨ Fitur & Konsep SCSS yang Digunakan

* **Variables (`$var`):** Penggunaan variabel untuk menyimpan nilai warna (*color palette*), ukuran *font*, atau *margin*, sehingga perubahan desain dapat dilakukan dengan cepat hanya dari satu tempat.
* **Nesting:** Penulisan *selector* bersarang (hierarki) yang mengikuti struktur HTML, membuat kode lebih mudah dibaca dan mengurangi pengulangan nama *class*.
* **Mixins & Includes:** Pembuatan blok kode CSS yang dapat digunakan kembali (*reusable*), sangat berguna untuk *styling* tombol, efek transisi, atau pengaturan *flexbox*.
* **Modularisasi (Partials):** (Jika diterapkan) Pemisahan kode SCSS ke dalam beberapa file kecil agar lebih terorganisir sebelum dikompilasi menjadi satu file CSS utama.

## 🛠️ Teknologi yang Digunakan

* **HTML5:** Struktur semantik halaman web.
* **SCSS / Sass:** *CSS Preprocessor* untuk *styling*.
* **CSS3:** Hasil kompilasi akhir dari SCSS.

## 🚀 Cara Menjalankan Proyek

Berbeda dengan CSS biasa, SCSS perlu **dikompilasi** (diubah) menjadi CSS standar agar dapat dibaca oleh *browser*. Berikut cara menjalankan proyek ini:

1. *Clone* repositori ini ke komputer Anda:
   ```bash
   git clone https://github.com/ValdoMilo/TugasPemrogramanWeb-Pertemuan4-SCSS.git
   ```
2. Buka folder proyek menggunakan Code Editor (seperti **Visual Studio Code**).
3. **Untuk melihat hasilnya langsung:** Anda bisa langsung membuka file `index.html` di *browser* jika file hasil kompilasi (misalnya `style.css`) sudah tersedia di dalam folder.
4. **Untuk mengedit SCSS:** 
   * Pastikan Anda menginstal ekstensi **Live Sass Compiler** di VS Code.
   * Buka file `.scss`.
   * Klik tombol **"Watch Sass"** di bagian bawah VS Code (Status Bar).
   * Ekstensi akan otomatis menerjemahkan kode SCSS Anda menjadi file CSS setiap kali Anda menyimpan (*save*) perubahan.

## 👨‍💻 Pembuat

* **GitHub:** [@ValdoMilo](https://github.com/ValdoMilo)

*Dibuat untuk memenuhi penugasan mata kuliah Pemrograman Web - Pertemuan 4.*
