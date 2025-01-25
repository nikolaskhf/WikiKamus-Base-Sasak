# Mengenal Sintaks Wiki

Halaman ini hanya akan memberikan informasi dasar tentang sintaks yang digunakan pada proyek Wikimedia. Untuk informasi lebih lanjut, Anda dapat merujuk pada halaman bantuan proyek Wikimedia, misalnya Halaman Bantuan pada [Wikikamus bahasa Indonesia](https://id.wiktionary.org/wiki/Bantuan:Penyuntingan) atau [Wikipedia bahasa Indonesia](https://id.wikipedia.org/wiki/Wikipedia:Markah_wiki).

Dalam WikiKamus base Sasak, beberapa yang perlu Anda ketahui hanyalah **Judul**, **Templat**, **Daftar**, dan **Tautan**.

## Judul dan sub-judul halaman

Judul dan sub-judul halaman pada halaman wiki ditulis dengan sama dengan. Semakin banyak sama dengan, semakin dalam sub-judulnya. Misalnya:

```MediaWiki
== Sub judul 2 ==

=== Sub judul 3 ===

==== Sub judul 4 ====

dan seterusnya
```

Sub judul pertama (dengan satu sama dengan) tidak dapat digunakan karena telah digunakan sebagai judul halaman pada proyek Wikimedia.

## Templat

Templat pada proyek Wikimedia dapat mempermudah penyuntingan, khususnya untuk sesuatu yang sering dipakai. Misalnya, pada WikiKamus base Sasak, terdapat templat-templat untuk kelas kata dari suatu kata, seperti kata benda, kata kerja, dan lain sebagainya. Karena hal tersebut akan sering dipakai, maka kami telah menuliskan templat yang dapat digunakan. Untuk menggunakan templat, cukup gunakan dua kurung kurawal (`{{ }}`) dengan nama templat di dalam, seperti berikut:

```MediaWiki
{{Nama Templat}}
```

Misalnya, untuk nama templat kelas kata *kata benda* adalah `-n-`, maka untuk memanggil templat tersebut, Anda dapat menuliskan sebagai berikut:

```MediaWiki
{{-n-}}
```

## Daftar

Dalam WikiKamus base Sasak, kita menggunakan daftar nomor sebagai definisi dari kata tersebut. Untuk membuat daftar, Anda cukup tambahkan tanda pagar (`#`) untuk daftar nomor dan tanda bintang (`*`) untuk daftar tak bernomor. Misalnya:

```MediaWiki
# Satu
# Dua
# Tiga
## Tiga-satu
## Tiga-dua
# Empat

dan seterusnya
```

Begitu juga untuk daftar tak bernomor:

```MediaWiki
* Satu
* Dua
* Tiga
** Tiga-satu
** Tiga-dua
* Empat

dan seterusnya
```

## Tautan pada Wikimedia

Untuk menambahkan tautan pada Wikimedia, Anda dapat menggunakan satu kurung kotak (`[]`) untuk tautan luar atau dua kurung kotak (`[[]]`) untuk tautan pada proyek Wikimedia yang sama.

Misalnya, untuk menautkan halaman Google pada teks "Halaman Google", Anda dapat menambahkan URL halaman lalu tulisan yang dipisahkan dengan spasi:

```MediaWiki
[https://google.com Halaman Google]
```

Untuk menautkan tautan dalam proyek Wikimedia, Anda dapat menggunakan dua kurung kotak. Misalnya, Anda ingin menautkan halaman "aiq" pada halaman WikiKamus base Sasak, Anda dapat menggunakan sintaks berikut:

```MediaWiki
[[aiq]]
```

Jika Anda ingin menautkan tautan dalam proyek Wikimedia, dan ingin mengganti tulisannya, Anda dapat menambahkan simbol pipa (`|`) seperti berikut:

```MediaWiki
[[Nama halaman|Tulisan yang muncul]]
```

Misalnya, Anda ingin menautkan halaman "benda cair" tapi ingin menampilkan tulisan "air", maka Anda dapat menuliskan seperti berikut:

```MediaWiki
[[benda cair|air]]
```
