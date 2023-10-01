# lab1_pemogramanweb

## Membuat Paragraf

<!-- Ini adalah paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
HTML.</p>
<!-- Ini adalah paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
tag dasar html.</p>

Selanjutnya simpan kembali perubahannya, dan lakukan refresh pada web browser, lihat hasilnya.


#untuk mengatur paragaraf 

<!-- Ini adalah paragraf pertama -->
<p align=”center”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman
Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
tag-tag dasar HTML.</p>
<!-- Ini adalah paragraf kedua -->
<p align=”right”>Ini merupakan sebuah paragraf yang terdiri dari beberapa
kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
dengan menggunakan tag dasar html.</p>

Simpan kembali dan amati perubahannya dengan melakukan refresh pada web browser. Selanjutnya silakan ubah-ubah nilai atributnya (align => justify, left, right, dan center) untuk melihatperbedaan lainnya.



## Menambahkan Judul

<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>


## Memformat Teks

<!-- paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<p>
  Kami sedang belajar HTML dasar, pada matakuliah <b>Pemograman Web</b> di
  prodi <i>Teknik Informatika</i> <mark>Universitas Pelita Bangsa</mark>.
  Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana
  dalam mengenal tag-tag dasar HTML.
</p>

## Menambahkan Gambar/Logo

<!-- sub judul paragraf -->
<h3> Menambahkan Gambar</h3>

<!-- menambahkan gambar pada dokumen -->
<img src="c:\Users\fabia\Pictures\Saved Pictures\Komi Shouko 1.jpeg" />


## Menambahkan Hyperlink
<nav>
<a href="lab1_tag_dasar.html"><b>DASAR HTML</b></a>
</nav>




Menjawab Pertanyaan
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
Tidak ada error dan HTML akan berjalan seperti normal.

2. Apa perbedaan dari tag < p > dengan tag < br > , berikan penjelasannya!
<br> digunakan untuk menggerakan teks ke barisan baru sedangkan <p> digunakan untuk membuat paragraf baru, <br> bisa digunakan untuk menambah barisan baru kedalam sebuah teks.

3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
alt adalah untuk menyediakan tag alt gambar untuk menggambarkan gambar ke crawler mesin pencari dan pembaca layar untuk aksesibilitas web yang lebih baik. title adalah untuk memberikan penjelasan tentang tag alt gambar dan URL gambar dalam atribut src.

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
Hanya dengan menggunakan width foto akan menjadi lebih presisi tetapi height bisa mengatur foto semaunya

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

_blank: Membuka dokumen yang dituju di jendela atau tab baru.
_self: Membuka dokumen yang dituju di jendela atau frame yang sama dengan elemen yang diklik. Ini adalah nilai default jika atribut target tidak ditentukan.
_parent: Membuka dokumen yang dituju di frame parent dari elemen yang diklik. Jika elemen tersebut tidak ada dalam frame, perilakunya sama seperti _self.
_top: Membuka dokumen yang dituju di jendela penuh, menggantikan semua frame, termasuk frame luar. Jika elemen tersebut tidak ada dalam frame, perilakunya sama seperti _self.