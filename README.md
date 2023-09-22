# Pemrograman-Integratif-A-Bab-3_215150707111010_Salman-Ghozy-Nashrullah

<h1>Langkah Percobaan</h1>
<h2>Percobaan instalasi NodeJS</h2>
<h3>Langkah ke-1</h3>
<p>Buka halaman web nodeJS</p>
<a href="https://nodejs.org/en/"> <img src="gambar/1.PNG"></a>


<h3>Langkah ke-2</h3>
<p><i>Download</i> dan jalankan <i>node setup</i></p>
<img src="gambar/2.PNG">

<h3>Langkah ke-3</h3>
<p>Setelah instalasi selesai jalankan <i>command node -v</i> untuk memeriksa apakah <b>NodeJS</b> sudah terinstall</p>
<img src="gambar/3.PNG">

<h2>Percobaan instalasi NodeJS</h2>
<h3>Langkah ke-1</h3>
<p>Lakukan pembuatan folder dengan nama <b>express-mongodb</b> dan masuk ke dalam folder tersebut lalu buka melalui <i>text editor</i> masing-masing</p>
<img src="gambar/4.PNG">

<h3>Langkah ke-2</h3>
<p>Lakukan <i>npm init</i> untuk <i>mengenerate file package.json</i> dengan menggunakan <i>command npm init -y</i></p>
<img src="gambar/5.PNG">

<h3>Langkah ke-3</h3>
<p>Lakukan instalasi <i>express, mongoose,</i> dan <i>dotenv</i> dengan menggunakan <i>command npm i express mongoose dotenv</i></P>
<img src="gambar/6.PNG">

<h2>Koneksi Express ke MongoDB</h2>
<h3>Langkah ke-1</h3>
<p>Buatlah <i>file index.js</i> pada <i>root folder</i> dan masukkan kode <i>node index.js</i></p>
<img src="gambar/7.PNG">

<h3>Langkah ke-2</h3>
<p>Lakukan pembuatan <i>file .env</i> dan masukkan <i>PORT=5000</i></p>
<img src="gambar/8.PNG">
<p>Setelah itu ubahlah kode pada listening port menjadi berikut dan coba jalankan aplikasi kembali</p>
<img src="gambar/9.PNG">

<h3>Langkah ke-3</h3>
<p><i>Copy connection string</i> yang terdapat pada <i>compass</i> atau <i>atlas</i> dan <i>paste</i> kan pada <i>.env</i> seperti berikut</p>
<img src="gambar/10.PNG">

<h3>Langkah ke-4</h3>
<p>Tambahkan baris kode berikut pada <i>file index.js</i> Setelah itu menjalankan aplikasi kembali </p>
<img src="gambar/11.PNG">

<h2>Pembuatan routing</h2>
<h3>Langkah ke-1</h3>
<p>Lakukan pembuatan direktori <i>routes</i> di tingkat yang sama dengan <i>index.js</i> dan membuat <i>file book.route.js</i> di dalamnya</P>
<img src="gambar/12.PNG">

<h3>Langkah ke-2</h3>
<p>Membuat <i>file book.route.js</i> di dalamnya</p>
<img src="gambar/13.PNG">

<h3>Langkah ke-3</h3>
<p>Menambahkan baris kode berikut untuk fungsi getAllBooks</p>
<img src="gambar/100.PNG">

<h3>Langkah ke-4</h3>
<p>Melakukan hal yang sama untuk <i>getOneBook, createBook, updateBook,</i> dan <i>deleteBook</i></p>
<img src="gambar/14.PNG">

<h3>Langkah ke-5</h3>
<p>Melakukan <i>import book.route.js</i> pada <i>file index.js</i> dan tambahkan baris kode berikut</p>
<img src="gambar/15.PNG">

<h3>Langkah ke-6</h3>
<p>Melakukan Uji salah satu endpoint dengan Postman</p>
<img src="gambar/16.PNG">

<h2>Pembuatan Controller</h2>
<h3>Langkah ke-1</h3>
<p>Lakukan pembuatan direktori <i>controllers</i> di tingkat yang sama dengan <i>index.js</i> dan membuat <i>file book.controller.js</i> di dalamnya. Dan membuat baris kode dari routes untuk fungsi getAllBooks</p>
<img src="gambar/17.PNG">

<h3>Langkah ke-2</h3>
<p>Lakukan langkah yang sama untuk operasi <i>getOneBook, createBook, updateBook, dan deleteBook.</i> Selanjutnya, impor <i>file book.controller.js</i> ke dalam file <i>book.route.js</i> dan modifikasi fungsi-fungsi tersebut agar dapat memanggil fungsi-fungsi yang ada di <i>book.controller.js.</i></p>
<img src="gambar/18.PNG">

<h3>Langkah ke-3</h3>
<p>Lakukan pengujian kembali, pastikan <i>response</i> tetap sama</p>
<img src="gambar/19.PNG">

<h2>Pembuatan Model</h2>
<h3>Langkah ke-1</h3>
<p>Lakukan pembuatan direktori <i>models</i> di tingkat yang sama dengan <i>index.js</i> Setelah itu membuat <i>file book.model.js</i> di dalamnya Tambahkan baris kode berikut sesuai dengan tabel</p>
<img src="gambar/20.PNG">

<h2>Operasi CRUD</h2>
<h3>Langkah ke-1</h3>
<p>Menghapus semua data pada collection books</p>
<img src="gambar/21.PNG">

<h3>Langkah ke-2</h3>
<p>Melakukan import book.model.js pada file book.controller.js</p>
<img src="gambar/200.PNG">

<h3>Langkah ke-3</h3>
<p> melakukan perubahan pada fungsi createBook</p>
<img src="gambar/22.PNG">

<h3>Langkah ke-4</h3>
<p>Membuatlah dua buah buku dengan data di bawah ini dengan Postman lakukan perintah <i>PUT</i> satu per satu</p>
<img src="gambar/24.PNG">

<h3>Langkah ke-5</h3>
<p>Melakukan perubahan pada fungsi <i>getAllBooks</i></p>
<img src="gambar/300.PNG">

<h3>Langkah ke-6</h3>
<p>Melakukan perubahan pada fungsi <i>getOneBook</i></p>
<img src="gambar/400.PNG">

<h3>Langkah ke-7</h3>
<p>Menampilkan semua buku dengan Postman</p>
<img src="gambar/25.PNG">

<h3>Langkah ke-8</h3>
<p>Menampilkan buku Dilan 1990 dengan Postman</p>
<img src="gambar/26.PNG">

<h3>Langkah ke-9</h3>
<p>Melakukan perubahan pada fungsi updateBook</p>
<img src="gambar/27.PNG">

<h3>Langkah ke-10</h3>
<p>Mengubah judul buku Dilan 1991 menjadi "Ghozy 1991" dengan Postman</p>
<img src="gambar/28.PNG">

<h3>Langkah ke-11</h3>
<p>Melakukan perubahan pada fungsi deleteBook</p>
<img src="gambar/500.PNG">

<h3>Langkah ke-12</h3>
<p>Hapus buku Dilan 1990 dengan Postman</p>
<img src="gambar/29.PNG">



