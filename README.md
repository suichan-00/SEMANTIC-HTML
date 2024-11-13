Nama : Bintang Rehandika
Nim  : 2205101028

# SEMANTIC-HTML
Latihan Praktikum 1 Semantic HTML

## Latihan 1: Semantic HTML
**Menganalisis Code**

A) HTML

   Kekurangan dalam HTML sebelum diperbaiki:

   1. Tidak ada tag <html> dan <body>, sehingga struktur HTML tidak lengkap dan tidak standar.
   2. Tidak ada tag <head>, sehingga tidak mendefinisikan elemen penting seperti <title>, <meta charset>, dan <meta viewport>.
   
   Efeknya: Website yang tidak memenuhi struktur standar mungkin tidak dirender dengan benar di beberapa browser atau mungkin memiliki masalah kompatibilitas.
  
   Setelah di perbaiki:
  
   1. Penambahan tag <html>, <head>, dan <body> membuat struktur lebih lengkap dan sesuai standar HTML5.
   2. Penggunaan tag <meta charset="UTF-8"> dan <meta name="viewport"> memastikan website tampil baik di berbagai perangkat, terutama pada tampilan mobile.
   3. Dengan adanya <link rel="stylesheet">, file CSS terpisah akan dihubungkan dengan benar, sehingga pemisahan antara konten (HTML) dan tampilan (CSS) lebih 
      terstruktur.

B) CSS

   Kekurangan dalam CSS sebelum diperbaiki

   1. Pada header, nav, section, footer { padding: 5px; }, pengaturan padding diterapkan secara langsung, tetapi bagian ini memiliki potensi untuk menyebabkan 
      konflik 
      saat CSS lebih kompleks.
   2. Struktur display: grid pada body sudah baik, tetapi deklarasi margin: 10px; tidak diulang pada versi yang diperbarui.

   Setelah di perbaiki:
   
   1. Penggunaan grid layout tetap sama, tetapi margin pada body dihapus. Hal ini bisa mengurangi jarak yang muncul pada pinggir konten, membuat tata letak lebih 
      presisi.
   2. Penulisan padding: 5; pada header, nav, section, footer ada kesalahan, karena harusnya padding: 5px;. Jika tidak diperbaiki, ini akan menyebabkan padding 
      tidak diterapkan dan elemen terlihat lebih rapat.
   3. Konsistensi dalam penamaan dan penggunaan kelas untuk menjaga struktur yang lebih rapi telah ditingkatkan dalam pembaruan ini.
