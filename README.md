<h3><strong>HTML (Hypertext Markup Language)</strong></h3>
<hr>

HTML adalah bahasa markup standar untuk membuat halaman Web. HTML menjelaskan struktur halaman Web dan terdiri dari serangkaian elemen.

Ekstensi file HTML adalah .html atau .htm, yang bisa dilihat dengan mengunakan web browser apa pun (seperti Google Chrome, Safari, atau Mozila Firefox). Browser tersebut membaca file HTML dan merender kontennya sehingga user internet bisa melihat dan membacanya.

Biasanya, rata-rata situs web menyertakan sejumlah halaman HTML yang berbeda-beda. Contohnya, halaman beranda, ‘Tentang Kami’, halaman kontak memiliki dokumennya sendiri-sendiri.

Masing-masing halaman tersebut terdiri atas serangkaian tags (bisa disebut juga elements), yang tersusun untuk membentuk sebuah halaman website. Tag tersebut membuat hierarki yang menyusun konten hingga menjadi bagian, paragraf, heading, dan block konten lainnya.

Sebagian besar elemen bahasa markup ini memiliki tag pembuka dan penutup yang menggunakan syntax <tag></tag>.

<strong>Dokumen HTML Sederhana</strong>
![g1](https://github.com/anggienaprilia/PWEB1/assets/168538184/91206807-63c7-42c5-a0ae-f74388c362ca)

<i>Penjelasan:</i>
- Deklarasi "!DOCTYPE html" mendefinisikan bahwa dokumen saat ini adalah dokumen HTML5
- Elemen "html" adalah elemen akar atau utama dari halaman HTML
- Elemen "head" berisi mengenai informasi meta tentang halaman HTML
- Elemen "title" menentukan judul untuk halaman HTML (yang ditampilkan di bilah judul browser atau di tab halaman)
- Elemen "body" mendefinisikan badan dokumen, dan merupakan wadah untuk semua konten yang terlihat, seperti judul, paragraf, gambar, hyperlink, tabel, daftar, dll
- Elemen "h1" mendefinisikan judul besar
- Elemen "p" mendefinisikan paragraf

Beberapa contoh penggunaan umum HTML adalah:

1. Pengembangan web ->Developer menggunakan kode HTML untuk mendesain tampilan elemen halaman web di browser, seperti teks, hyperlink, dan file media. 
2. Navigasi internet -> Pengguna bisa menelusuri dan menyisipkan link antara halaman dan website terkait karena HTML banyak digunakan untuk menyematkan hyperlink. 
3. Dokumentasi web -> HTML bisa digunakan untuk mengatur dan memformat dokumen, mirip dengan Microsoft Word.

<strong>Tag Block-Level</strong>
<br>Tiga tag block-level yang harus dimiliki oleh setiap dokumen HTML adalah <html>, <head>, dan <body>.

1. Tag <html></html> -> Elemen level tertinggi yang menyertakan setiap halaman HTML.
2. Tag <head></head> -> Menyimpan informasi meta, seperti judul dan charset halaman.
3. Tag <body></body> -> Melampirkan semua konten yang muncul pada suatu halaman.

Sejak awal WWW (World Wide Web), ada banyak versi HTML yaitu bermula pada tahun 1989 dengan versi "Tim Bernes-Lee invented www" hingga terakhir pada tahun 2017 dengan versi "W3C Recommendation: HTML5.2

<strong>Hubungan HTML dan bahasa pemrograman lain</strong>
<br>Meskipun dinyatakan sebagai bahasa markup yang canggih dan mudah, HTML tidak sepenuhnya bisa membuat website yang profesional dan responsif. Bahasa ini hanya bisa digunakan untuk menambah elemen dan membuat struktur konten.

Namun di satu sisi, bahasa ini bisa bekerja secara maksimal dengan dua bahasa frontend: CSS (Cascading Style Sheets) dan JavaScript. Jika digabungkan, kedua bahasa frontend ini bisa meningkatkan pengalaman user dan memberikan fungsi yang lebih canggih.

- CSS erat kaitannya dengan styling, seperti background, warna, layout, spacing, dan animiasi.
- JavaScript memungkinkan menambahkan fungsionalitas yang dinamis, seperti slider, pop-up, dan galeri foto.

Jika digambarkan, berikut perbedaan HTML dan CSS dan JavaScript: HTML adalah orang yang tidak mengenakan busana apa pun, kemudian CSS adalah bajunya, kemudian JavaScript adalah aktivitas dan sikap orang tersebut.
<hr>

<h3><strong>CSS (Cascading Style Sheet)</strong></h3>
<hr>

CSS adalah bahasa Cascading Style Sheet. CSS menjelaskan bagaimana elemen HTML ditampilkan di layar, kertas, atau di media lain sehingga digunakan untuk mengatur tampilan elemen yang tertulis dalam bahasa markup. CSS berfungsi untuk memisahkan konten dari tampilan visualnya di situs.

CSS dibuat dan dikembangkan oleh W3C (World Wide Web Consortium) pada tahun 1996 untuk alasan yang sederhana. Dulu HTML tidak dilengkapi dengan tags yang berfungsi untuk memformat halaman. Developer hanya perlu menulis markup untuk situs.

HTML dan CSS memiliki keterikatan yang erat. Karena HTML adalah bahasa markup (fondasi situs) dan CSS memperbaiki style (untuk semua aspek yang terkait dengan tampilan website), maka kedua bahasa pemrograman ini harus berjalan beriringan.

![image](https://github.com/anggienaprilia/PWEB1/assets/168538184/1fd395b9-16ce-4ce4-9612-ffe52f4961a7)

<i>Penjelasan gambar diatas: </i>
- Elemen "body" memiliki warna background dengan penggunaan properti <background-color: jenis warna>
- ELemen "h1" memiliki warna huruf dengan penggunaan properti <color: warna> dan berada di posisi tengah dengan pengaturan <text-align: posisi>
- Elemen "p" memiliki jenis huruf dengan penggunaan properti <font-family: jenis huruf> dan ukuran huruf dengan pengaturan <font-size: ukuran>

Menurut penjelasan diatas, maka dapat disimpulkan jika adanya variasi pada dokumen HTML dihasilkan dari pengaturan tertentu. Semua pengaturan tersebut berada di dalam style. Tag <style> merupakan bentuk tag dari bahasa CSS. Dari sini dapat disimpulkan apapun variasi gaya pada dokumen HTML disebabkan dengan adanya keterlibatan bahasa CSS didalamnya.

<strong>Sintaks CSS</strong>
Sederhananya aturan CSS terdiri dari selector dan blok deklarasi.
![image](https://github.com/anggienaprilia/PWEB1/assets/168538184/0c75eee2-2c9c-4652-8bf1-c7ab3ce1988d)

<i>Penjelasan: </i>
- Selector -> Merujuk ke elemen HTML yang ingin dibuat variasi
- Blok deklarasi -> Berisi satu atau lebih deklarasi yang dipisahkan oleh titik koma
- Blok deklarasi -> Dalam blok dekorasi menyertakan nama properti seperti <color>, <background-color>, <font-size> dan nilai (value> seperti "blue", "red", "12px"
- Blok deklarasi -> Membuat blok dekorasi diapit oleh kurung kurawal

<strong>Warna CSS</strong>
Warna yang digunakan ditentukan menggunakan nama warna yang telah ditentukan sebelumnya, atau nilai RGB, HEX, HSL, RGBA, HSLA.

Berikut adalah contoh nama warna yang ditentukan:
![image](https://github.com/anggienaprilia/PWEB1/assets/168538184/72787da8-2054-435e-8820-efdd85a9142c)

<strong>CSS warna background</strong>
![image](https://github.com/anggienaprilia/PWEB1/assets/168538184/61adc9b0-237c-492d-aa79-5ba51eaa7844)

<i>Penjelasan: </i>
Teks pada header 1 dan teks pada paragraf memiliki warna latar belakang yang berbeda. Hal tersebut disebabkan penggunaan properti style "background-color" yang merupakan properti untuk mengatur warna latar belakang

<strong>CSS warna teks</strong>
![image](https://github.com/anggienaprilia/PWEB1/assets/168538184/f084f8fe-8509-4ba4-8601-8eaaa95234d8)

<i>Penjelasan: </i>
Walapun, bagian dari satu elemen yang sama yaitu paragraf "p", dengan adanya pengaturan penggunaan properti berbeda pada masing-masing paragraf, maka akan terjadi perbedaan secara jelas antara paragraf satu dengan lainnya.

<strong>CSS warna batas (border)</strong>
![image](https://github.com/anggienaprilia/PWEB1/assets/168538184/ec1728fc-ef79-46bf-948d-964695c7fbb6)

<i>Penjelasan: </i>
Pada CSS, tidak hanya terdapat properti tentang ukuran, jenis dan warna huruf saja. Ada pula properti yang mengatur mengenai batas (border) yang biasa digunakan untuk membatasi teks dengan sebuah garis. Untuk mengatur batas (border), CSS memiliki properti yakni "border" yang dimana juga memiliki jenis properti lain seperti pengaturan untuk batas dengan ukuran, warna, jenis, dll.

<strong>CSS warna</strong>
![image](https://github.com/anggienaprilia/PWEB1/assets/168538184/d06ea52f-8114-4496-a4c3-62ea002f914b)

<i>Penjelasan: </i>
Satu warna dengan tiga, bahkan lima jenis nilai melalui nilai RGB, nilai HEX, nilai HSL, nilai RGBA, dan nilai HSLA.
- RGB -> Singkatan dari Red, Green, Blue
- HEX -> Singkatan dari Hexadesimal
- HSL -> Singkatan dari Hue, Saturation, Lightness
- RGBA -> Singkatan dari Red, Green, Blue, Alfa
- HSLA -> Singkatan dari Hue, Saturation, Lightness, Alfa

RGB dan RGBA -> Hampir memiliki susunan nilai yang sama, tetapi untuk RGBA memiliki tambahan kompenen alfa yang menentukan transparansi atau kecerahan warna. Nila alfa ini berawal dari 0 hingga 1, dimana nilai 0 adalah transparan dan nilai 1 adalah kecerahan asli warna.

HSL dan HSLA -> Hampir sama dengan RGB dan RGBA, disini HSL dan HSLA memiliki perbedaan untuk HSLA memiliki tambahan kompenen alfa yang menentukan transparansi atau kecerahan warna yang digunakan.
