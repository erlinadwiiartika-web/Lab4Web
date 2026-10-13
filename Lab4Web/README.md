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
-about
<img width="1366" height="768" alt="about" src="https://github.com/user-attachments/assets/e06886ad-bd7d-4c3d-9249-1c4b1e4e718c" />

-contact
<img width="1366" height="768" alt="contact" src="https://github.com/user-attachments/assets/cc56a35f-f111-4b1c-b296-722265b6bd98" />

-home
<img width="1366" height="768" alt="home" src="https://github.com/user-attachments/assets/d2364970-88a7-4313-8404-575ffa53080f" />

-lab4_box
<img width="1366" height="768" alt="lab4_box" src="https://github.com/user-attachments/assets/6f6c0252-99dc-4f75-b160-3d6ce761b6eb" />


## Validasi HTML
-about
<img width="1035" height="434" alt="image" src="https://github.com/user-attachments/assets/16b371f4-c4cd-4690-8065-d73dc005e5ac" />

-contact
<img width="1035" height="438" alt="image" src="https://github.com/user-attachments/assets/35fc4dcc-e48e-41e9-952a-812b1d552882" />

-home
<img width="1035" height="438" alt="image" src="https://github.com/user-attachments/assets/e9023e32-d501-4dd3-adad-3aafeb355d42" />

-lab4_box
<img width="1035" height="430" alt="image" src="https://github.com/user-attachments/assets/1b448649-479f-49cf-ae73-3bdc4e27a4d9" />


## Git dan GitHub
```bash
git init
git add .
git commit -m "Praktikum 4 CSS Layout"
git branch -M main
git remote add origin https://github.com/erlinadwiiartika/Lab4Web
git push -u origin main
```
