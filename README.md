# KSR Master IPS SMP

KSR Master IPS SMP adalah aplikasi web interaktif yang dirancang untuk membantu siswa mempersiapkan kompetisi atau latihan soal IPS secara mandiri. Aplikasi ini menggabungkan modul belajar, simulasi CBT, dan tutor interaktif dalam satu antarmuka yang responsif.

## Tujuan Proyek

Proyek ini dibuat untuk:

- menyediakan bahan belajar IPS yang terstruktur per mata pelajaran
- membantu siswa memahami konsep melalui ringkasan materi
- melatih kecepatan dan ketepatan menjawab soal dalam format CBT
- memberi umpan balik hasil latihan secara langsung
- menyediakan fitur tanya jawab singkat seperti guru virtual

## Fitur Utama

### 1. Modul Materi IPS

Aplikasi memiliki panel modul yang terbagi berdasarkan bidang utama:

- Ekonomi
- Sosiologi
- Geografi
- Sejarah

Setiap modul berisi:

- ringkasan konsep penting
- topik-topik utama yang sering muncul pada kisi-kisi
- penjelasan yang dibuat ringkas namun informatif
- tombol untuk langsung memulai latihan soal sesuai bidang

### 2. Fitur Pencarian dan Filter

Pengguna dapat:

- mencari topik atau istilah tertentu pada modul
- memfilter modul berdasarkan kategori
- melihat materi berdasarkan bidang tertentu

Ini membuat proses belajar lebih cepat dan lebih fokus.

### 3. Simulasi CBT

Aplikasi ini memiliki fitur ujian berbasis komputer dengan mekanisme seperti ujian nyata:

- timer 20 menit
- soal berjumlah 20 item
- navigasi antar soal
- tombol pilihan jawaban
- tombol "ragu-ragu" untuk menandai soal yang belum pasti
- tampilan grid soal untuk melihat progres pengerjaan
- auto-save jawaban pengguna ke state lokal

### 4. Sistem Penilaian dan Diagnostik

Setelah ujian selesai, aplikasi menghitung:

- skor total
- jumlah jawaban benar, salah, dan kosong
- persentase pencapaian
- medal/gelar berdasarkan hasil
- analisis per mata pelajaran

Diagnostik ini membantu siswa mengetahui bidang mana yang masih perlu diperkuat.

### 5. Review Soal dan Pembahasan

Setelah ujian, pengguna dapat membuka mode review untuk melihat:

- soal yang sudah dijawab
- jawaban benar vs salah
- pembahasan konsep dari setiap pertanyaan
- evaluasi berdasarkan materi pelajaran

Fitur ini sangat berguna untuk belajar dari kesalahan, bukan sekadar melihat nilai.

### 6. Tanya Guru (Chatbot Interaktif)

Aplikasi juga menyediakan fitur tanya jawab berbasis kata kunci. Fitur ini:

- menerima pertanyaan dari pengguna
- mencari pola kata kunci dalam database pengetahuan
- memberi jawaban singkat dan relevan tentang materi IPS
- membantu siswa memahami konsep dasar tanpa harus membuka modul penuh

Contoh topik yang didukung:

- inflasi
- mobilitas sosial
- teori masuknya Hindu-Buddha
- garis Wallace
- politik etis
- dan topik IPS umum lainnya

### 7. Antarmuka Responsif

Aplikasi dirancang agar tampil baik di:

- desktop
- tablet
- smartphone

Terdapat dua mode navigasi utama:

- header navigasi untuk tampilan desktop
- bottom navigation untuk tampilan mobile

## Struktur Aplikasi

Proyek ini merupakan aplikasi single-page front-end yang memuat:

- HTML untuk struktur halaman
- CSS/Tailwind untuk styling
- JavaScript untuk logika aplikasi
- React dan Babel untuk rendering komponen dinamis
- Lucide Icons untuk ikon antarmuka

## Teknologi yang Digunakan

- HTML5
- JavaScript
- React
- Babel
- Tailwind CSS
- Lucide Icons
- Google Fonts (Plus Jakarta Sans)

## Cara Menjalankan

1. Unduh atau clone repositori ini.
2. Buka file `index.html` di browser modern.
3. Pastikan koneksi internet tersedia karena aplikasi memanfaatkan CDN untuk Tailwind dan icon.
4. Gunakan menu navigasi untuk mengakses:
   - Modul Materi
   - Simulasi CBT
   - Tanya Guru

## Catatan Penggunaan

- Aplikasi ini bersifat edukasi dan prototype pembelajaran.
- Data soal, modul, dan knowledge base ditulis secara statis di dalam file HTML.
- Chatbot menggunakan pencocokan kata kunci, sehingga jawaban terbaik akan muncul bila pertanyaan mengandung kata kunci yang relevan.

## Lisensi

Proyek ini dibuat untuk kebutuhan pembelajaran dan pengembangan pendidikan. Silakan gunakan dengan bijak dan sesuaikan izin penggunaan jika akan dikembangkan lebih lanjut untuk kebutuhan komersial atau publikasi formal.

## Ringkasan Singkat

Aplikasi ini merupakan platform belajar IPS interaktif yang menitikberatkan pada:

- belajar mandiri
- latihan soal berbasis CBT
- sambungan materi dan pembahasan
- dukungan tutor virtual
- pengalaman belajar yang cepat, ringkas, dan mudah diakses
