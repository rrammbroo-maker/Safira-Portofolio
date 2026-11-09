# Personal Biography Website

Template website profil pribadi dan portofolio piagam, dibuat dengan HTML, CSS, dan JavaScript murni.

## Menjalankan website
1. Ekstrak folder ZIP.
2. Buka folder `biografi-website`.
3. Klik dua kali `index.html` untuk melihat website di browser.

## Mengganti identitas dan foto
- Ganti teks `Nama Kamu` di `index.html`.
- Ganti foto profil dengan file JPG bernama `profile.jpg`, lalu simpan di `assets/images/`.
- Edit deskripsi, pendidikan, minat, domisili, dan tautan media sosial langsung di `index.html`.
- Ganti `USERNAME` pada tautan Instagram dan TikTok.
- Ganti nomor WhatsApp pada tautan `wa.me` dengan nomor internasional tanpa tanda `+`, spasi, atau strip.

## Menambahkan piagam
1. Masukkan foto piagam ke `assets/images/`.
2. Buka `script.js`.
3. Edit daftar `certificates`:
   - `academic` untuk piagam akademik.
   - `nonAcademic` untuk piagam non-akademik.
4. Setiap item memiliki `image`, `title`, dan `description`. Template sudah berisi tepat 15 data akademik (`academic-01.jpg` sampai `academic-15.jpg`) dan 18 data non-akademik (`non-academic-01.jpg` sampai `non-academic-18.jpg`). Ganti nama file, judul, dan deskripsinya sesuai sertifikatmu.
5. Untuk menambah piagam, salin satu objek `{ image, title, description }` dan ubah nilainya. Template sudah menyediakan 15 slot akademik (5 baris × 3 kolom) dan 18 slot non-akademik (6 baris × 3 kolom) pada layar lebar. Di layar kecil, jumlah kolom menyesuaikan ukuran perangkat.

Contoh:
```js
{ image: "academic-04.jpg", title: "Juara 1 Olimpiade", description: "Olimpiade tingkat provinsi, 2025." }
```

## Menambahkan musik
- Simpan file musik milikmu sebagai `music.mp3` di `assets/audio/`.
- File audio sudah disetel `loop`, sehingga akan berulang.
- Website mencoba autoplay saat dibuka. Browser modern sering memblokir autoplay yang bersuara sampai pengunjung berinteraksi. Jika diblokir, pengunjung dapat menekan tombol Play pada pemutar di kanan bawah.
- Pastikan kamu memiliki hak atau izin untuk menggunakan lagu tersebut.

## Bahasa
Website menggunakan Bahasa Indonesia saja agar tampilan tetap sederhana dan fokus. Untuk mengganti teks profil dan data piagam, edit konten di `index.html` dan daftar data di `script.js` sesuai kebutuhan.

## Publikasi
Website ini bersifat statis. Kamu dapat mengunggah seluruh isi folder ke GitHub Pages, Netlify, atau layanan hosting statis lainnya. Jangan mengunggah file pribadi yang tidak ingin dipublikasikan.
