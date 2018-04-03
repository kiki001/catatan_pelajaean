# Memprioritaskan Satu Gaya di Atas Gaya Lainnya

Contoh :

Terkadang elemen HTML Anda akan menerima beberapa gaya yang bertentangan satu sama lain.

Misalnya, elemen h1 Anda tidak bisa berwarna hijau dan merah muda pada saat yang bersamaan.

Mari kita lihat apa yang terjadi ketika kita membuat kelas yang membuat teks menjadi merah muda, lalu menerapkannya ke elemen. Akankah kelas kita mengesampingkan warna elemen tubuh: hijau; Properti CSS?

Buat kelas CSS yang disebut teks merah muda yang memberikan elemen warna pink.

Berikan elemen h1 Anda kelas teks merah muda.

Soal :

Elemen h1 Anda harus memiliki kelas pink-text

&lt;Style&gt; Anda harus memiliki kelas CSS berwarna pink-text dengan warna yang disetel menjadi merah muda.

Elemen h1 Anda harus berwarna merah jambu.

```
<style>
  body {
    background-color: green;
    font-family:monospace;
    color: green;
  }

  h1 {
    color: green;
  }

</style>

<h1>Hello World</h1>
```

Jawaban :

```
<style>
  body {
    background-color: black;
    font-family: Monospace;
    color: green;
  }

  .pink-text{
    color: pink;
  }
</style>
<h1 class="pink-text">Hello World!</h1>
```



