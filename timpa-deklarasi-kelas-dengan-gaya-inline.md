# Override/Timpa Deklarasi Kelas dengan Gaya Inline

Contoh :

Jadi kami telah membuktikan bahwa deklarasi id mengalahkan deklarasi kelas, di mana pun mereka dinyatakan dalam CSS elemen gaya Anda.

Ada cara lain yang dapat Anda ganti CSS. Apakah Anda ingat gaya sebaris?

Gunakan gaya in-line untuk mencoba membuat elemen h1 kami menjadi putih. Ingat, dalam gaya garis terlihat seperti ini:

```
<h1 style = "color: green">
```

Biarkan kelas  blue-text dan pink-text pada elemen h1 Anda.

Soal :

1. Elemen h1 Anda harus memiliki pink-text kelas.
2. Elemen h1 Anda harus memiliki blue-text kelas.
3. Elemen h1 Anda harus memiliki id oranye-teks.
4. Berikan elemen h1 Anda dengan gaya color: white.
5. Elemen h1 Anda harus putih.

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

Jawaban :

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



