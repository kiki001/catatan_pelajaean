# Override/Timpa Semua Gaya Lain dengan menggunakan Important/Penting

Yay! Kami baru saja membuktikan bahwa gaya in-line akan menggantikan semua deklarasi CSS dalam elemen gaya Anda.

Tapi tunggu. Ada satu cara terakhir untuk mengganti CSS. Ini adalah metode yang paling kuat dari semuanya. Tetapi sebelum kita melakukannya, mari kita bicara tentang mengapa Anda ingin mengganti CSS.

Dalam banyak situasi, Anda akan menggunakan pustaka CSS. Ini mungkin secara tidak sengaja menimpa CSS Anda sendiri. Jadi, ketika Anda benar-benar harus memastikan bahwa suatu elemen memiliki CSS tertentu, Anda dapat menggunakan !important

Mari kita kembali ke deklarasi kelas pink-text. Ingat bahwa kelas pink-text kami ditimpa oleh deklarasi kelas berikutnya, deklarasi id, dan gaya in-line.

Mari tambahkan kata kunci! Penting untuk pernyataan warna elemen teks merah muda Anda untuk memastikan 100% bahwa elemen h1 Anda akan berwarna merah muda.

Contoh cara melakukan ini adalah:

```css
color: red !important;
```

Soal :

1. Elemen h1 Anda harus memiliki pink-text kelas.
2. Elemen h1 Anda harus memiliki blue-text kelas.
3. Elemen h1 Anda harus memiliki id oranye-teks.
4. Elemen h1 Anda harus memiliki gaya color: white.
5. Deklarasi kelas teks merah muda Anda harus memiliki kata kunci !important untuk mengesampingkan semua deklarasi lainnya.
6. Elemen h1 Anda harus berwarna merah jambu.

```css
<style>
  body {
    background-color: black;
    font-family: Monospace;
    color: green;
  }
  #orange-text {
    color: white;
  }
  .pink-text {
    color: pink;
  }
  .blue-text {
    color: blue;
  }
</style>
<h1 style="color:white" id="orange-text" class="pink-text blue-text">Hello World!</h1>
```

Jawaban :

```css
<style>
  body {
    background-color: black;
    font-family: Monospace;
    color: green;
  }
  #orange-text {
    color: pink;
  }
  .pink-text {
    color: pink !important;
  }
  .blue-text {
    color: blue;
  }
</style>
<h1 id="orange-text" class="pink-text blue-text" style="color: white">Hello World!</h1>
```



