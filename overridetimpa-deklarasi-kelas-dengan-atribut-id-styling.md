# Override/Timpa Deklarasi Kelas dengan Atribut ID Styling

Contoh :

Tapi kita belum selesai. Ada cara lain yang dapat Anda ganti CSS. Apakah Anda ingat atribut id?

Mari kita mengesampingkan kelas teks merah muda dan teks biru Anda, dan menjadikan elemen h1 Anda oranye, dengan memberi elemen h1 sebuah id dan kemudian menata id itu.

Berikan elemen h1 Anda atribut id dari teks oranye. Ingat, gaya id terlihat seperti ini:

```
<h1 id = "teks oranye">
```

Biarkan kelas teks biru dan teks merah muda pada elemen h1 Anda.

Buat deklarasi CSS untuk id berwarna oranye Anda di elemen gaya Anda. Berikut ini contoh apa yang terlihat seperti ini:

```
# teks-coklat {
  warna coklat;
}
```

Catatan: Tidak masalah apakah Anda menyatakan css ini di atas atau di bawah kelas teks merah muda, karena atribut id akan selalu didahulukan.

Soal :

1. Elemen h1 Anda harus memiliki pink-text kelas.
2. Elemen h1 Anda harus memiliki blue-text kelas.
3. Berikan elemen h1 Anda pada id orange-text.
4. Buat deklarasi CSS untuk id orange-text Anda
5. Jangan memberikan atribut gaya h1 Anda.
6. Elemen h1 Anda harus berwarna oranye.

```css
<style>
  body {
    background-color: black;
    font-family: Monospace;
    color: green;
  }
  .pink-text {
    color: pink;
  }
  .blue-text{
    color:blue;
  }
</style>
<h1 class="pink-text blue-text">Hello World!</h1>
```

Jawaban :

```css
<style>
  body {
    background-color: black;
    font-family: Monospace;
    color: green;
  }
  .pink-text {
    color: pink;
  }
  .blue-text {
    color: blue;
  }
  #orange-text{
    color:orange;
  }

</style>
<h1 class="pink-text blue-text" id="orange-text">Hello World!</h1>
```



