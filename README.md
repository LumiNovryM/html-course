# HTML Dasar

# Pendahuluan HTML

HTML merupakan singkatan dari Hypertext Markup Language, HTML merupakan bahasa markup bukan bahasa pemrograman karena tidak memiliki function, variable, dan structure control. HTML disebut Markup Language karena didalam terdapat serangkaian markup yang nantinya akan kita sebut sebagai “Tag”.

HTML Diciptakan oleh Tim Berners-Lee. Selain HTML Tim Berners-Lee juga sudah menemukan banyak hal seperti :

- HTML (Hypertext Markup Language)
- HTTP (Hypertext Transfer Protocol)
- WWW (World Wide Web)
- Web Browser
- Web Server
- Web Page

# Hello World

Struktur HTML Sederhana
`<!doctype html>
<html>
<head>
     <title></title>
</head>
<body>`

`</body>
</html>`

- **`<!doctype html>`** : Untuk memberi tahu bahwa struktur HTML yang digunakan adalah versi 5
- **`<html>`** : Digunakan untuk membuat halaman HTML yang mencakup semua konten dan elemen
- **`<head>`** : Berguna untuk memberikan informasi tentang dokumen, seperti informasi berupa penulis, judul dokumen, dan kata kunci yang ada pada dokumen
- **`<title>`** : Tempat untuk meletakkan judul halaman website
- **`<body>`** : Menyimpan semua tag yang akan tampil pada halaman website

# Code Editor

Code editor adalah sebuah perangkat lunak penyunting teks yang dirancang khusus untuk menyunting kode sumber program komputer oleh pemrogram. Aplikasi ini dapat berupa aplikasi yang berdiri sendiri atau dapat juga tergabung ke dalam sebuah integrated Developement Environtment
Contoh Code Editor
 

- Visual Studio Code
- Sublime Text
- Atom
- Android Studio
- Notepad++
- Vim
- Nano
- NetBeans
- Visual Studio
- Eclipse
- Pycharm

# Tag

| Fungsi | Tag |
| --- | --- |
| Title | `<title>` |
| Teks | `<h1>` `<h2>` `<h3>` `<h4>` `<h5>` `<h6>` `<p>` |
| Pendukung Teks | `<br>` `<hr>` `<em>` `<strong>` |
| Gambar | `<img>` |
| Hyperlink | `<a>` |
| List (Bullets & Numbering) | `<ul>` `<ol>` `<li>` `<dl>` `<dt>` `<dd>` |
| Table | `<table>` `<thead>` `<tbody>` `<tr>` `<td>` |
| Form | `<form>` `<input>` `<select>` `<button>`  |
| Script | `<script>` |
| Object | `<object>` |
| Grouping | `<div>` `<span>` |
| Comment | `<!— Comment —>` |

Struktur Tag
`<namatag atribut=”value”>`
Contoh :
`<body bgcolor=”blue”>`

Setiap Tag memiliki atribut global, yaitu 

| Atribut Global | Fungsi |
| --- | --- |
| `accesskey` | Untuk menentukan elemen diakses dengan apa |
| `class` | Sebagai tanda (Untuk dua atau lebih tag) |
| `id` | Sebagai tanda (hanya untuk satu, id bersifat unique) |
| `dir` | Untuk menentukan arah tulisan |
| `lang` | Untuk bahasa |
| `style` | Untuk memberi style |
| `tabindex` | Untuk memberi urutan pada saat kita memencet keyboar tab |
| `title` | Untuk memberi judul pada sebuah tag |

# Paragraf

| Tag | Fungsi |
| --- | --- |
| `<p>` | Untuk membuat paragraf |
| `<br>` | Untuk membuat jarak antar baris |
| `<hr>` | Untuk membuat garis horizontal |
| `<b>` | Untuk membuat text menjadi bold atau tebal |
| `<i>` | Untuk membuat text menjadi miring atau italic |
| `<u>` | Untuk membuat text memiliki underline |
| `<strong>` | Untuk membuat teks menjadi cetak tebal dan memberi penekanan pada suatu teks karena dianggap lebih penting |
| `<em>` | Untuk membuat teks menjadi miring dan memberi penakan pada suatu teks atau konten |

# Heading

Heading adalah judul, untuk membuat heading kita bisa menggunakan tag `<h1>, <h2>, <h3>, <h4>, <h5>, <h6>` . Berikut adalah ukuran level pada tag Heading

| Tag | Ukuran | Waktu Penggunaan |
| --- | --- | --- |
| `<h1>` | Paling Besar | Untuk Membuat Judul  |
| `<h2>` |  | Untuk Membuat Sub-Judul |
| `<h3>` |  | Untuk Membuat Sub-Judul 1 |
| `<h4>` |  | Untuk Membuat Sub-Judul 2 |
| `<h5>` |  | Untuk Membuat Sub-Judul 3 |
| `<h6>` | Paling Kecil | Untuk Membuat Sub-Judul 4 |

# List

Untuk Membuat list kita bisa menggunakan tag 

| Tag | Fungsi |
| --- | --- |
| `<ol>` | Untuk membuat ordered list atau list terurut |
| `<ul>` | Untuk membuat Unordered list atau list terurut |
| `<li>` | Untuk membuat list item |

Untuk tag `<ol>` kita bisa merubah simbol urutan angkanya (defaultnya) dengan yang lain menggunakan atribut `type`

| Type | Output |
| --- | --- |
| `type=”1”` | 1. List Item 2. List Item 3. List Item |
| `type=”A”` | A. List Item B. List Item C. List Item |
| `type=”I”` | I. List Item II. List Item III. List Item |
| `type=”i”` | i. List Item ii. List Item iii. List Item |
| `type=”a”` | a. List Item b. List Item c. List Item |

sedangkan untuk tag `<ul>` kita juga bisa merubah urutan bulletnya (defaultnya) dengan yang lain menggunakan atribut `type`

| Type | Output |
| --- | --- |
| `type=”disc”` | Kotak |
| `type=”square”` | Bulat |
| `type=”circle”` | Bulatan (Kosong Di Tengah) |

tag `<dl>` digunakan untuk membuat definition list, tag `<dt>` adalah definition terminology dan tag `<dd>` adalah definition description
Berikut adalah struktur dari tag `<dl>`

`<dl>
        <dt>Term 1</dt>
        <dd>Description 1</dd> 
</dl>`

# Hyperlink

Hyperlink adalah sebuah koneksi dari sumber web ke web lain. link pada HTML dibuat dengan tag `<a>` (anchor). Tag `<a>` memiliki atribut `href` yang berguna sebagai tujuan link, berikut adalah link yang bisa kita isi pada atribut `href` yaitu 

| Type | Example | Definition |
| --- | --- | --- |
| `External` | https://www.google.com | Link yang terhubung ke web lain |
| `Internal`  | halamandua.html | Link yang terhubung ke halaman lain pada web yang sama |

Relative URL (Uniform Resource Location) adalah sebuah URL yang menentukan sebuah alamat menurut URL aktif saat itu.

Page Anchor adalah adalah sebuah link yang mengarah ke bagian konten tertentu pada suatu halaman

# Image

Untuk membuat image pada HTML kita bisa menggunakan tag `<img>`, pada tag `<img>` terdapat atribut `src` yang berguna sebagai sumber dari gambar. ada dua jenis gambar yang bisa kita tambahkan pada halaman web

| Type | Definition |
| --- | --- |
| `Internal Source` | Yaitu sumber gambar yang berasal dari local project |
| `External Source` - `Hot Link` | Yaitu sumber gambar yang berasala dari sumber lain atau web lain |

pada External Source sendiri memiliki kekurangan yaitu jika sumber gambar mengalami down website maka gambar tidak akan di tampil dan bisa saja gambar yang kita gunakan bisa saja copyright, lebih baik menggunakan Internal Source.

Tag `<img>` juga memiliki atribut 

| Atribut | Fungsi |
| --- | --- |
| `src` | Untuk menghubungkan ke sumber gambar |
| `alt` | Jika gambar tidak tampil pada halaman web maka isi pada atribut alt yang akan ditampilkan seperti namanya yaitu alternative text |
| `title` | Untuk memberi judul pada gambar, yang dimana akan muncul ketika gambar di hover dalam beberapa detik |
| `width` | Untuk mengatur lebar pada gambar |
| `height` | Untuk mengatur tinggi pada gambar |

Untuk mengatur gambar sebaiknya gunakan salah satu antara `height` dan `width` karena jika ukuran yang diatur tidak sesuai proporsi atau  tidak seimbang maka gambar akan mengalami stretching. Pada bagian `width` dan `height` ada dua satuan yang bisa digunakan

| Satuan | Definition |
| --- | --- |
| `px` | Mengatur gambar dengan satuan pixel |
| `%` | Mengatur gambar dengan satuan persen |

Defaultnya satuan `px` lah yang digunakan

# Table

Table pada HTML dibuat dengan tag `<table>` dengan struktur table yaitu Baris dan Kolom.
Berikut adalah struktur `<table>` sederhana

`<table>
   <tr>
      <td>Baris 1, Kolom 1</td>
      <td>Baris 1, Kolom 2</td>
   </tr>
   <tr>
       <td>Baris 1, Kolom 1</td>`

       `<td>Baris 1, Kolom 2</td>
    </tr>
</table>`

Berikut adalah struktur `<table>` kompleks

Berikut adalah atribut pada tag <`table>`

| Atribut | Fungsi |
| --- | --- |
| `border` | Untuk menambahkan baris disekitar cell / data |
| `cellspacing` | Untuk menambah jarak antar cell / data |
| `cellpadding` | Untuk mengatur luas pada cell / data |
| `colspan` | Digunakan sebagai cell / data merging secara column (Secara Samping) |
| `rowspan` | Digunakan sebagai cell / data merging secara row (Secara Bawah) |

# Form

Form adalah proses elemen pada HTML yang digunakan untuk mengolah data yang diinputkan pada Form. Untuk membuat form kita menggunakan tag `<form>`

Berikut adalah elemen form

| Elemen  | definition |
| --- | --- |
| `input` | Untuk memasukkan data bisa berupa (text, password, radio, checkbox) |
| `textarea` | Untuk memasukkan data berupa text tapi dengan rentang ukuran yang lebih banyak |
| `select` | Untuk memilih data secara dropdown |
| `button` | Untuk membuat tombol sebagai cara untuk memulai proses pengirim form |
| `label`| Sebagai pelengkap keterangan dari sebuah input |
     
 

Jika melihat sesuatu tidak pada tempatnya, pengertian yang salah, dan typo segera fix dan Open Pull Request untuk membantu :octocat:!
