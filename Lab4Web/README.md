# Lab4Web — Praktikum 4: CSS Layout

**Nama:** Erlina Dwi Artika  
**Kelas:** I252A  
**NIM:** 312510039  
**Mata Kuliah:** Pemrograman Web

## Deskripsi
Proyek ini menerapkan materi Praktikum 4: CSS Layout, yaitu box element, CSS float dan clear, HTML5 semantic elements, layout dengan konten utama dan sidebar, widget, footer, halaman About, serta form Contact.

## Struktur folder
- `lab4_box.html` — demo box element dan properti clear.
- `home.html` — halaman utama layout.
- `about.html` — halaman profil/deskripsi dan portofolio.
- `contact.html` — halaman formulir kontak.
- `style.css` — stylesheet eksternal bersama.
- `assets/screenshots/` — bukti tampilan halaman.

## Cara menjalankan
1. Unduh atau clone repository.
2. Buka folder `Lab4Web` di Visual Studio Code.
3. Buka `home.html` di browser (atau gunakan ekstensi Live Server).
4. Gunakan navigasi Home, About, dan Contact untuk memeriksa halaman.
5. Buka `lab4_box.html` untuk melihat demo box element.

## Langkah praktikum dan hasil
1. Membuat dokumen HTML dengan struktur `DOCTYPE`, `html`, `head`, dan `body`.
2. Membuat box element serta mengamati `float` dan `clear` pada `lab4_box.html`.
3. Membuat layout semantik menggunakan `header`, `nav`, `section`, `main`, `article`, `aside`, dan `footer`.
4. Memisahkan aturan tampilan ke file `style.css` dan menghubungkannya dengan elemen `link`.
5. Menambahkan navigasi, hero panel, konten utama, sidebar widget, dan footer.
6. Menambahkan halaman About berisi deskripsi diri dan portofolio.
7. Menambahkan halaman Contact dengan kolom nama, email, subjek, dan pesan.
8. Menguji navigasi dan formulir di browser serta mengambil screenshot hasil.

## Jawaban pertanyaan dan tugas
### 1. Tambahkan layout untuk menu About
Halaman `about.html` dibuat sebagai halaman tunggal (single layout) yang memuat deskripsi diri, keahlian yang dipelajari, dan portofolio pembelajaran. Halaman menggunakan stylesheet `style.css` yang sama agar konsisten dengan halaman utama.

### 2. Tambahkan layout untuk menu Contact
Halaman `contact.html` berisi form nama, email, subjek, dan pesan. Kolom nama, email, dan pesan wajib diisi menggunakan atribut `required`; email menggunakan tipe `email`. Form ini merupakan simulasi front-end dan belum mengirim data ke server.

## Screenshot
Screenshot hasil browser ada pada `assets/screenshots/` dan dapat digunakan sebagai bukti pada laporan.

## Validasi HTML
Buka https://validator.w3.org, pilih **Validate by File Upload**, lalu unggah satu per satu file HTML untuk memeriksa validitas markup. Simpan screenshot hasil validasi aktual setelah dilakukan.

## Git dan GitHub
```bash
git init
git add .
git commit -m "Praktikum 4 CSS Layout"
git branch -M main
git remote add origin https://github.com/USERNAME/Lab4Web.git
git push -u origin main
```
Ganti `USERNAME` dengan username GitHub sendiri. Buat repository bernama `Lab4Web` sebelum menjalankan perintah remote/push.
