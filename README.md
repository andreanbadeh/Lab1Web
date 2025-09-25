# MEMBUAT MODUL PRAKTIKUM PEMROGRAMAN WEB

NAMA : ANDREAN PUTRA ARYA

NIM : 312410341

KELAS : TI.24.A.4

MATKUL : PEMROGRAMAN WEB 1

# SOURCE CODE HTML
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Lab1 - Tag Dasar HTML</title>
</head>
<body>
    <nav>
        <a href="lab1_tag_dasar.html">Dasar HTML</a> |
        <a href="lab1_halaman2.html">Halaman 2</a> |
        <a href="http://www.google.com" target="_blank">Halaman Web Eksternal Google</a> |
        <a href="profil.html">Profil Andrean Putra</a> |
    </nav>
    <hr>
    <h1>BELAJAR DASAR HTML</h1>
    <p>
        SAYA <b>ANDREAN PUTRA ARYA</b> dengan <b>NIM 312410241</b> sedang belajar <mark>HTML dasar</mark>, pada matakuliah 
        <b>Pemrograman Web1</b> di Prodi <i>Teknik Informatika Universitas Pelita Bangsa</i>. 
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML.
    </p>
    <h2>PARAGRAF PADA HTML</h2>
    <p>
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang 
        saling mendukung sehingga menjadi satu kesatuan. 
        Paragraf dibuat dengan menggunakan tag dasar html.
    </p>
    <h3>MENAMBAHKAN GAMBAR</h3>
    <img src="images/Logo-UPB.png" width="250" 
         title="Logo Universitas Pelita Bangsa" 
         alt="Logo UPB">

    <img src="images/Logoo.jpg" width="250"
        title="Logo Andrean Putra"
        alt="Logoo">

</body>
</html>
```

# MODUL PRAKTIKUM PEMROGRANAN WEB

HTML (Hypertext Markup Language) adalah bahasa markup untuk membuat dan menampilkan halaman web. Struktur dasar HTML terdiri dari :
- Document Type Declaration (DOCTYPE) untuk menentukan standar dokumen.
- Header berisi info halaman (judul, meta, CSS, dll.).
- Body berisi isi halaman web.

Contoh pengaplikasiannya : 
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Lab1 - Tag Dasar HTML</title>
</head>
<body>

</body>
</html>
```

Kemudian selanjutnya, buka file tersebut pada web browser untuk membuktikan hasilnya :

![gambar](https://github.com/andreanbadeh/Lab1Web/blob/0d1dc9756264aa73de3e2dce67416c97de2eed56/images/Screenshot%20from%202025-09-25%2013-11-07.png)

# 1. MEMBUAT PARAGRAF

Tag HTML adalah kode dalam kurung siku < >. Ada tag pembuka dan penutup, misalnya  ... /p. Beberapa tag tidak punya penutup seperti br/, img/.
Paragraf dan pemisah baris :
- p untuk membuat paragraf.
- br untuk pindah baris.
- hr untuk garis horizontal.

Contoh pengaplikasiannya :
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Lab1 - Tag Dasar HTML</title>
</head>
<body>
<p>SAYA ANDREAN PUTRA ARYA dengan NIM 312410241 sedang belajar HTML dasar, pada matakuliah 
Pemrograman Web1 di Prodi Teknik Informatika Universitas Pelita Bangsa. 
Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
dalam rangka mengenal tag-tag dasar HTML.</p>

<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang 
saling mendukung sehingga menjadi satu kesatuan. 
Paragraf dibuat dengan menggunakan tag dasar html.</p>
</body>
</html>
```

Kemudian selanjutnya, buka file tersebut pada web browser untuk membuktikan hasilnya :

![gambar](https://github.com/andreanbadeh/Lab1Web/blob/8c343f6dd573d88b21860bb2e9ceda27a4b9b017/images/Screenshot%20from%202025-09-25%2013-19-43.png)

# 2. MENAMBAHKAN JUDUL
Seperti sudah dijelaskan pada materi bahwa judul memiliki 6 level yaitu mulai h1 sampai h6. Kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragraf kedua.
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Lab1 - Tag Dasar HTML</title>
</head>
<body>
<h1>BELAJAR DASAR HTML</h1>
    <p>
        SAYA ANDREAN PUTRA ARYA dengan NIM 312410241 sedang belajar HTML dasar, pada matakuliah 
        Pemrograman Web1 di Prodi Teknik Informatika Universitas Pelita Bangsa. 
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML.
    </p>
<h2>PARAGRAF PADA HTML</h2>
    <p>
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang 
        saling mendukung sehingga menjadi satu kesatuan. 
        Paragraf dibuat dengan menggunakan tag dasar html.
    </p>
</body>
</html>
```
Kemduian simpan, lalu kita liat hasilnya :

![gambar](https://github.com/andreanbadeh/Lab1Web/blob/6807241faa0760417b55e655659a8f5097d60094/images/Screenshot%20from%202025-09-25%2013-29-29.png)

# 3. MEMFORMAT TEKS
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya. Ada beberapa tag yang dapat digunakan untuk memformat teks pada paragraf, sehingga tampilannya seperti berikut.
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Lab1 - Tag Dasar HTML</title>
</head>
<body>
<h1>BELAJAR DASAR HTML</h1>
    <p>
        SAYA <b>ANDREAN PUTRA ARYA</b> dengan <b>NIM 312410241</b> sedang belajar <mark>HTML dasar</mark>, pada matakuliah 
        <b>Pemrograman Web1</b> di Prodi <i>Teknik Informatika Universitas Pelita Bangsa</i>. 
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML.
    </p>
<h2>PARAGRAF PADA HTML</h2>
    <p>
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang 
        saling mendukung sehingga menjadi satu kesatuan. 
        Paragraf dibuat dengan menggunakan tag dasar html.
    </p>
</body>
</html>
```
Selanjutnya, mari kita lihat hasilnya :

![gambar](https://github.com/andreanbadeh/Lab1Web/blob/38c7b88acc5226ced271120d512e5ba7d72c2ee3/images/Screenshot%20from%202025-09-25%2013-24-55.png)

# 4. Menyisipkan Gambar
Untuk menyisipkan gmbar, siapkan gambar yang akan disisipkan pada halaman web, kemudian simpan file gambar tersebut satu folder dengan file dokumen html. Atau bisa juga menyisipkan gambar dari website external. Kemudian tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3 sebelumnya. Gambar akan ditampilkan apa adanya sesuai dengan ukuran aslinya. Untuk mengatur ukuran gambar, dapat digunakan atribut witdh dan height dengan nilai integer yang disesuaikan.
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Lab1 - Tag Dasar HTML</title>
</head>
<body>
<h1>BELAJAR DASAR HTML</h1>
    <p>
        SAYA <b>ANDREAN PUTRA ARYA</b> dengan <b>NIM 312410241</b> sedang belajar <mark>HTML dasar</mark>, pada matakuliah 
        <b>Pemrograman Web1</b> di Prodi <i>Teknik Informatika Universitas Pelita Bangsa</i>. 
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML.
    </p>
<h2>PARAGRAF PADA HTML</h2>
    <p>
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang 
        saling mendukung sehingga menjadi satu kesatuan. 
        Paragraf dibuat dengan menggunakan tag dasar html.
    </p>
<h3>MENAMBAH![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/73203a1509abda1a5f5ee589aecb49e8db73bf1a/Cuplikan%20layar%202025-09-23%20222251.png)KAN GAMBAR</h3>
    <img src="images/Logo-UPB.png" width="250" 
         title="Logo Universitas Pelita Bangsa" 
         alt="Logo UPB">

    <img src="images/Logoo.jpg" width="250"
        title="Logo Andrean Putra"
        alt="Logoo">

</body>
</html>
```

Simpan perubahannya, kemudian refresh browser.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/73203a1509abda1a5f5ee589aecb49e8db73bf1a/Cuplikan%20layar%202025-09-23%20222306.png)

# 5. Menambahkan Hyperlink
Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/fcbc8013e37c6a2ef54225a4d2df435400ff3bee/Cuplikan%20layar%202025-09-23%20222522.png)

Buat satu file lagi dengan nama lab1_halaman2.html kemudian isi dokumen tersebut dengan tag html dasar dan dengan isi bebas, boleh mengcopy dari halaman sebelumnya.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/fcbc8013e37c6a2ef54225a4d2df435400ff3bee/Cuplikan%20layar%202025-09-23%20222542.png)
