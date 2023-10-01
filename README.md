# lab1_pemogramanweb
Fabian Eka Prasetyo

312210301

Pemograman Web

## Membuat Paragraf

    <!-- Ini adalah paragraf pertama -->
    <p>
      Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
      Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat
      adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.
    </p>

    <!-- Ini adalah paragraf kedua -->
    <p>
      Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
      mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
      tag dasar html.
    </p>

Selanjutnya simpan kembali perubahannya, dan lakukan refresh pada web browser, lihat hasilnya.

![Screenshot 2023-09-25 104033](https://github.com/ReOrize5/lab1_pemogramanweb/assets/115756982/3d85a83e-5676-441b-b5ac-cc51ffb2f82a)

### Untuk Mengatur Paragraf 

    <!-- Ini adalah paragraf pertama -->
    <p> 
      align=”center”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman
      Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
      yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
      tag-tag dasar HTML.
    </p>

    <!-- Ini adalah paragraf kedua -->
    <p>
      align=”right”>Ini merupakan sebuah paragraf yang terdiri dari beberapa
      kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
      dengan menggunakan tag dasar html.
    </p>

Simpan kembali dan amati perubahannya dengan melakukan refresh pada web browser. Selanjutnya silakan ubah-ubah nilai atributnya (align => justify, left, right, dan center) untuk melihat perbedaan lainnya.

![Screenshot 2023-09-25 104340](https://github.com/ReOrize5/lab1_pemogramanweb/assets/115756982/a8d1553b-c91d-42c2-902c-3e9c324127f0)



## Menambahkan Judul

    <!-- judul paragraf pertama -->
    <h1>Belajar Dasar HTML</h1>
    <!-- judul paragraf kedua -->
    <h2>Paragraf pada HTML</h2>

![Screenshot 2023-09-25 104814](https://github.com/ReOrize5/lab1_pemogramanweb/assets/115756982/49b763f9-3407-4b8f-9725-3ee9ea675704)


## Memformat Teks

    <!-- paragraf pertama -->
    <h1>Belajar Dasar HTML</h1>
    <p>
        Kami sedang belajar HTML dasar, pada matakuliah <b>Pemograman Web</b> di
        prodi <i>Teknik Informatika</i> <mark>Universitas Pelita Bangsa</mark>.
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana
        dalam mengenal tag-tag dasar HTML.
    </p>

![Screenshot 2023-09-25 105609](https://github.com/ReOrize5/lab1_pemogramanweb/assets/115756982/9e76f718-7f72-464b-881a-85a9873bc240)

## Menambahkan Gambar/Logo

    <!-- sub judul paragraf -->
    <h3> Menambahkan Gambar</h3>

    <!-- menambahkan gambar pada dokumen -->
    <img src="c:\Users\fabia\Pictures\Saved Pictures\Komi Shouko 1.jpeg" />

![Screenshot 2023-10-01 155528](https://github.com/ReOrize5/lab1_pemogramanweb/assets/115756982/d7d89a9a-0b12-43ec-a64f-3a61d4afa65d)



## Menambahkan Hyperlink
    <nav>
    <a href="lab1_pemogramanweb"><b>DASAR HTML</b></a>
    </nav>

![Screenshot 2023-10-01 163452](https://github.com/ReOrize5/lab1_pemogramanweb/assets/115756982/3d81cf79-e314-4e91-836c-d951d57fda8b)


Menjawab Pertanyaan
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?

``` = Tidak ada error dan HTML akan berjalan seperti normal.```

2. Apa perbedaan dari tag < p > dengan tag < br > , berikan penjelasannya!

```= <br> digunakan untuk menggerakan teks ke barisan baru sedangkan <p> digunakan untuk membuat paragraf baru, <br> bisa digunakan untuk menambah barisan baru kedalam sebuah teks.```

3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!

```= alt adalah untuk menyediakan tag alt gambar untuk menggambarkan gambar ke crawler mesin pencari dan pembaca layar untuk aksesibilitas web yang lebih baik. title adalah untuk memberikan penjelasan tentang        tag alt gambar dan URL gambar dalam atribut src.```

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!

``` = Hanya dengan menggunakan width foto akan menjadi lebih presisi tetapi height bisa mengatur foto semaunya.```

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

    - blank: Membuka dokumen yang dituju di jendela atau tab baru.
    - self: Membuka dokumen yang dituju di jendela atau frame yang sama dengan elemen yang diklik. Ini adalah nilai default jika atribut target tidak ditentukan.
    - parent: Membuka dokumen yang dituju di frame parent dari elemen yang diklik. Jika elemen tersebut tidak ada dalam frame, perilakunya sama seperti _self.
_top: Membuka dokumen yang dituju di jendela penuh, menggantikan semua frame, termasuk frame luar. Jika elemen tersebut tidak ada dalam frame, perilakunya sama seperti _self.
