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

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/7da0a7923b09c518b7c947fcf83753b433d4f36e/Cuplikan%20layar%202025-09-23%20220927.png)

Kemudian selanjutnya, buka file tersebut pada web browser untuk membuktikan hasilnya :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/e657b8203e864d91421f643d6a4be90a63e48b42/Cuplikan%20layar%202025-09-23%20221000.png)

Kemudian atur atribut paragraf seperti berikut, dan amati perubahanya :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/c81cc7bcdd2ebc108cda4e2f7e3d04f60e4a03b1/Cuplikan%20layar%202025-09-23%20230427.png)

Simpan kembali dan amati perubahannya dengan melakukan refresh pada web browser. Selanjutnya silakan ubah-ubah nilai atributnya (align => justify, left, right, dan center) untuk melihat perbedaan lainnya.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/c81cc7bcdd2ebc108cda4e2f7e3d04f60e4a03b1/Cuplikan%20layar%202025-09-23%20230441.png)

# 2. MENAMBAHKAN JUDUL
Seperti sudah dijelaskan pada materi bahwa judul memiliki 6 level yaitu mulai h1 sampai h6. Kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragraf kedua.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/4e24c5f10dff5082bd939ed2efb47a08f889dadc/Cuplikan%20layar%202025-09-23%20221115.png) 

Kemduian simpan, lalu kita liat hasilnya :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/4e24c5f10dff5082bd939ed2efb47a08f889dadc/Cuplikan%20layar%202025-09-23%20221128.png)


# 3. MEMFORMAT TEKS
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya. Ada beberapa tag yang dapat digunakan untuk memformat teks pada paragraf, sehingga tampilannya seperti berikut.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/50e0c9c24c5a169e85545e08cf2195e01e540689/Cuplikan%20layar%202025-09-23%20221538.png)

Selanjutnya, mari kita lihat hasilnya :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/50e0c9c24c5a169e85545e08cf2195e01e540689/Cuplikan%20layar%202025-09-23%20221552.png)

# 4. Menyisipkan Gambar
Untuk menyisipkan gmbar, siapkan gambar yang akan disisipkan pada halaman web, kemudian simpan file gambar tersebut satu folder dengan file dokumen html. Atau bisa juga menyisipkan gambar dari website external. Kemudian tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3 sebelumnya. Gambar akan ditampilkan apa adanya sesuai dengan ukuran aslinya. Untuk mengatur ukuran gambar, dapat digunakan atribut witdh dan height dengan nilai integer yang disesuaikan.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/73203a1509abda1a5f5ee589aecb49e8db73bf1a/Cuplikan%20layar%202025-09-23%20222251.png)

Simpan perubahannya, kemudian refresh browser.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/73203a1509abda1a5f5ee589aecb49e8db73bf1a/Cuplikan%20layar%202025-09-23%20222306.png)

# 5. Menambahkan Hyperlink
Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/fcbc8013e37c6a2ef54225a4d2df435400ff3bee/Cuplikan%20layar%202025-09-23%20222522.png)

Buat satu file lagi dengan nama lab1_halaman2.html kemudian isi dokumen tersebut dengan tag html dasar dan dengan isi bebas, boleh mengcopy dari halaman sebelumnya.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/fcbc8013e37c6a2ef54225a4d2df435400ff3bee/Cuplikan%20layar%202025-09-23%20222542.png)
