# Praktikum 2: CSS Dasar
## Langkah Praktikum2
### 1. Membuat Dokumen HTML
Buatlah dokumen HTML seperti berikut
![Screenshot (112)](https://github.com/Thoriq150/pt2_web/assets/115950790/34a8970e-587e-45dd-82b7-c72abb254ed4)
#### Lalu tampilkan browser
![Screenshot (113)](https://github.com/Thoriq150/pt2_web/assets/115950790/3757252d-47f3-4e73-b102-a34ae6c7804d)
### 2. Mendeklarasikan CSS Internal
Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.
![Screenshot (114)](https://github.com/Thoriq150/pt2_web/assets/115950790/5a6cbf9a-ab46-427b-a842-c24a776a892e)
#### Lalu tampilkan browser
![Screenshot (115)](https://github.com/Thoriq150/pt2_web/assets/115950790/62290605-7349-434a-9eea-a8701fdac597)
### 3. Menambahkan Inline CSS
Kemudian tambahkan deklarasi inline CSS pada tag Paragraf `<p>` seperti berikut.
![Screenshot (116)](https://github.com/Thoriq150/pt2_web/assets/115950790/34351e94-8cc9-447c-aca7-80af125b1000)
#### Lalu tampilkan browser
![Screenshot (117)](https://github.com/Thoriq150/pt2_web/assets/115950790/9394db47-d714-489e-910f-3f913c7bc0b3)
### 4. Membuat CSS Eksternal
Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS 
![Screenshot (118)](https://github.com/Thoriq150/pt2_web/assets/115950790/3f52527e-3d71-4729-b26a-79f808475cc8)
Kemudian tambahkan tag  link`<link>` untuk merujuk file css yang sudah dibuat pada bagian `<head>`
![Screenshot (119)](https://github.com/Thoriq150/pt2_web/assets/115950790/7f140429-fe21-470a-9b9e-70937e954da5)
#### Lalu tampilkan browser
![Screenshot (122)](https://github.com/Thoriq150/pt2_web/assets/115950790/9f18619a-ab48-45e6-b751-a8b65b5a4a63)
### 5. Menambahkan CSS Selector
Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file style_eksternal.css
![Screenshot (124)](https://github.com/Thoriq150/pt2_web/assets/115950790/9ab36ce9-7290-4734-9667-959d46d81d3f)
#### Lalu tampilkan browser
![Screenshot (123)](https://github.com/Thoriq150/pt2_web/assets/115950790/7f07bc6b-9290-467a-94d3-40a2eca2f8dd)

### Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( `<p id="paragraf-1" class="text-paragraf">` )

### Jawab
1.menambahkan border saat pengguna mengarahkan kursor ke link pada navigasi, mengubah fon size navigasi dan mengubah warna text pada link aktif dan mengubah warna
![Screenshot (126)](https://github.com/Thoriq150/pt2_web/assets/115950790/7005b27d-db66-436b-9884-79fa2650a7d0)
![Screenshot (127)](https://github.com/Thoriq150/pt2_web/assets/115950790/f152f8e4-15b5-4511-8334-088cc5a9c6ff)

2. h1 {...} adalah pendeklarasian CSS untuk semua elemen h1 di halaman HTML.
#intro h1 {...} adalah pendeklarasian CSS khusus untuk elemen h1 yang berada di dalam elemen dengan ID intro (<div id="intro">).
Jadi, perbedaannya adalah h1 {...} akan mempengaruhi semua elemen h1 di halaman, sementara #intro h1 {...} hanya akan mempengaruhi elemen h1 yang berada di dalam elemen dengan ID intro.
