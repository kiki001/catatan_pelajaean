# Tentukan Bagaimana Font Harus Degradasi

Contoh :

Ada beberapa font default yang tersedia di semua browser. Ini termasuk Monospace, Serif dan Sans-Serif

Ketika satu font tidak tersedia, Anda dapat memberi tahu browser untuk "menurunkan" font lain.

Misalnya, jika Anda ingin elemen menggunakan font Helvetica, tetapi juga menurunkan font Sans-Serif ketika Helvetica tidak tersedia, Anda dapat menggunakan gaya CSS ini:

```
p {
  font-family: Helvetica, Sans-Serif;
}
```

Soal :

1. Sekarang komentari panggilan Anda ke Google Fonts, sehingga font Lobster tidak tersedia. Perhatikan bagaimana hal itu menurun ke font Monospace.
2. Elemen h2 Anda harus menggunakan font Lobster.
3. Elemen h2 Anda harus menurunkan ke font Monospace ketika Lobster tidak tersedia.
4. Komentar panggilan Anda ke Google untuk font Lobster dengan meletakkan 
5. &lt;! -- di depannya.Pastikan untuk menutup komentar Anda dengan menambahkan --&gt;

```
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">

<style>
  .red-text {
    color: red;
  }

  h2{
    font-family:lobster;
  }

  p {
    font-size: 16px;
    font-family: Monospace;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
```

Jawaban :

```
<!-- <link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css"> -->
<style>
  .red-text {
    color: red;
  }

  h2 {
    font-family: Lobster, Monospace;
  }

  p {
    font-size: 16px;
    font-family: Monospace;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
```



