# Lab6Web

# 🌐 Praktikum 6 - Twitter Bootstrap

## 🎯 Tujuan Praktikum
1. Mahasiswa mampu memahami konsep **CSS Framework**.  
2. Mahasiswa mampu mengenal **Twitter Bootstrap** dan kegunaannya.  
3. Mahasiswa mampu menggunakan **Grid System** untuk membuat layout yang responsif.  
4. Mahasiswa mampu menggunakan komponen dasar Bootstrap seperti **Navbar, Card, Button, dan Form**.  
5. Mahasiswa mampu membuat halaman web sederhana dengan cepat menggunakan Bootstrap.

---

## 🧩 Struktur Project

lab6_bootstrap/
├── index.html
├── layoutmod.html
├── portfolio.html
├── form_bootstrap.html
├── assets/
│ └── images/
│ ├── profile.jpg
│ ├── project1.jpg
│ ├── project2.jpg
│ ├── project3.jpg
└── README.md


---

## 📸 Hasil Screenshot

### 💻 1–4 — Tampilan Coding di VSCode
Berisi keempat file utama yang dibuat pada praktikum ini:
1. `index.html`
<img width="1366" height="768" alt="Screenshot 2025-10-29 123301" src="https://github.com/user-attachments/assets/9239ad68-0272-4897-992c-d798fdbfdf46" />

2. `portfolio.html`
<img width="1366" height="768" alt="Screenshot 2025-10-29 123322" src="https://github.com/user-attachments/assets/f23112ad-2f4f-4046-916c-81f78cb58f1a" />

3. `layoutmod.html`
<img width="1366" height="768" alt="Screenshot 2025-10-29 123343" src="https://github.com/user-attachments/assets/b49cca9a-2816-4c72-aac7-400e094f6b28" />

4. `form_bootstrap.html`
<img width="1366" height="768" alt="Screenshot 2025-10-29 123419" src="https://github.com/user-attachments/assets/8dc8b69d-bcc1-44a2-83b9-217694e92dfa" />

Keempat file ini memanfaatkan Bootstrap untuk menampilkan **layout responsif**, **navbar**, **form**, dan **komponen card** yang modern.

---

### 🌍 5–6 — Tampilan Halaman Utama (index.html)

#### 🖼️ Screenshot 5  
Menampilkan halaman **Bootstrap Index** dengan dua card utama:
- **Judul Widget 1** berisi foto pribadi.  
- **Judul Widget 2** menampilkan logo **Universitas Pelita Bangsa (UPB)**.  
Semua card diatur dengan sistem grid Bootstrap agar tampil responsif di semua ukuran layar.

<img width="1366" height="768" alt="Screenshot 2025-10-29 123539" src="https://github.com/user-attachments/assets/fbe65bd4-13ff-4ed1-904f-aa2145676a9a" />


#### 🖼️ Screenshot 6  
Menampilkan bagian lanjutan dari halaman Index:
- **Tiga Kolom Heading** berisi teks bawaan *"Isi singkat untuk kolom 1–3"*.  
- Di bawahnya terdapat **Form Kontak (Refactor dari Praktikum 5)** yang berisi kolom:
  - Nama  
  - Email  
  - Pesan  
  - Tombol Kirim  

<img width="1366" height="768" alt="Screenshot 2025-10-29 123955" src="https://github.com/user-attachments/assets/acadcda0-b5bb-4430-9b6b-e5d871a588c6" />


**Catatan:**  
Form ini hanya bersifat **tampilan (frontend)** untuk latihan penggunaan komponen form Bootstrap.  
Ketika tombol **Kirim** ditekan, tidak terjadi aksi apapun karena belum terhubung ke server/backend.  
Hal ini **sesuai dengan instruksi praktikum** yang hanya menekankan pada desain tampilan, bukan fungsi pengiriman data.

---

### 💼 7 — Tampilan Halaman Portfolio
Halaman ini berisi:
- Sebuah foto pribadi di sisi kiri.  
- Di sisi kanan, terdapat nama lengkap **Muhammad Raffi Pasya Perdana** dan deskripsi singkat:
  > “Perkenalkan, saya Muhammad Raffi Pasya Perdana – seorang pengembang web yang suka membuat antarmuka yang bersih dan responsif menggunakan Bootstrap.”

Di bawahnya terdapat 3 card proyek pada bagian **Portfolio Saya**, masing-masing berisi gambar dummy dan deskripsi singkat proyek.
<img width="1366" height="631" alt="Screenshot 2025-10-29 124618" src="https://github.com/user-attachments/assets/b92b7ebe-2f20-4e09-b86c-100d80ba2bb3" />


---

### 🧱 8 — Tampilan Halaman Layoutmod (Refactor Praktikum 4)
Halaman ini merupakan hasil refactor dari layout praktikum 4 menggunakan Bootstrap:
- Menampilkan teks **"Hello World!"** pada Hero Section.  
- Menggunakan **Grid System** untuk membagi area konten utama dan sidebar.  
- Menggunakan komponen **Card** untuk artikel dan link terkait.  
- Warna, padding, dan jarak otomatis diatur oleh Bootstrap tanpa CSS manual.
<img width="1293" height="636" alt="Screenshot 2025-10-29 124754" src="https://github.com/user-attachments/assets/2ec89ab2-e60b-4dd9-9c55-005f10335101" />


---

### 🧮 9 — Tampilan Halaman Form Bootstrap (Refactor Praktikum 5)
Menampilkan form validasi nilai yang berisi:
- Field **Nama**
- Field **Nilai**
- Tombol **Cek Hasil**

Ketika tombol ditekan, muncul teks hasil validasi:
> “Selamat [username], kamu LULUS! 🎉”

Form ini menggunakan JavaScript sederhana untuk validasi input dan menampilkan pesan menggunakan komponen **alert Bootstrap**.
<img width="1366" height="723" alt="Screenshot 2025-10-29 124808" src="https://github.com/user-attachments/assets/63c0e9c7-544d-41d7-8312-44fdd256f3c4" />


---

## ⚙️ Teknologi yang Digunakan
- **HTML5**
- **Bootstrap 5.3.3 (CDN)**
- **JavaScript Dasar**
- **Visual Studio Code**

---

## 🧠 Kesimpulan
Dengan menggunakan Bootstrap:
- Pembuatan layout web menjadi lebih **cepat, konsisten, dan responsif**.  
- Developer tidak perlu lagi menulis CSS manual seperti `float`, `clear`, atau `margin`.  
- Komponen seperti **navbar**, **form**, dan **card** sudah memiliki tampilan modern secara otomatis.  
- Website terlihat profesional hanya dengan HTML dan class-class Bootstrap.

---

## 📘 Pertanyaan dan Tugas

1. **Refactor Layout Praktikum 4**  
   Ambil layout web sederhana dari Praktikum 4. Buat ulang layout tersebut menggunakan **Bootstrap Grid System**.  
   - Gunakan `<nav>` Bootstrap untuk bagian navigasi.  
   - Gunakan class `.row` dan `.col-md-8` untuk main content dan `.col-md-4` untuk sidebar.  
   - Gunakan komponen `.card` Bootstrap untuk menggantikan `.widget-box`.  
   - Gunakan komponen `.card` untuk menggantikan `.box` (bagian “Heading” yang berisi 3 kolom).  
   - Anda **tidak diperbolehkan menggunakan CSS float atau clear manual.**

2. **Refactor Form Praktikum 5**  
   Ambil salah satu form dari Praktikum 5 (misalnya Form Input atau Form Button).  
   Buat ulang form tersebut agar terlihat rapi menggunakan class-class form Bootstrap:  
   `.form-control`, `.form-label`, dan `.btn`.

3. **Tugas: Buat Halaman Portfolio Sederhana**  
   Buat satu halaman HTML baru (`portfolio.html`) menggunakan Bootstrap yang berisi:  
   a. Sebuah **Navbar** di bagian atas.  
   b. Sebuah section **“Tentang Saya”** di dalam `.container` dengan 1 baris (`.row`) dan 2 kolom (`.col`):  
      - Kolom kiri (`.col-md-4`) berisi foto Anda (`<img>` dengan class `.img-fluid`).  
      - Kolom kanan (`.col-md-8`) berisi nama dan deskripsi diri Anda.  
   c. Sebuah section **“Portfolio Saya”** di dalam `.container` dengan 1 baris (`.row`) dan 3 kolom (`.col-md-4`):  
      - Setiap kolom berisi satu komponen `.card` yang merepresentasikan satu proyek (berisi gambar dummy dan deskripsi singkat).
