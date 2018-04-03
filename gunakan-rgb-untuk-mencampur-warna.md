# Gunakan RGB untuk Mencampur Warna

Contoh :

Sama seperti dengan kode hex, Anda dapat mencampur warna dalam RGB dengan menggunakan kombinasi nilai yang berbeda.

Ganti kata-kata warna dalam elemen gaya kami dengan nilai RGB yang benar.

| Color | RGB |
| :--- | :--- |
| Blue | `rgb(0, 0, 255)` |
| Red | `rgb(255, 0, 0)` |
| Orchid | `rgb(218, 112, 214)` |
| Sienna | `rgb(160, 82, 45)` |

Soal :

1. Berikan elemen h1 Anda dengan teks I am red! warna merah.
2. Gunakan rgb untuk warna merah.
3. Berikan elemen h1 Anda dengan teks I am orchid! anggrek warna.
4. Gunakan rgb untuk warna anggrek.
5. Berikan elemen h1 Anda dengan teks I am blue! warna biru.
6. Gunakan rgb untuk warna biru.
7. Berikan elemen h1 Anda dengan teks I am sienna! warna sienna.
8. Gunakan rgb untuk warna sienna.

```css
<style>
  body {
    background-color: rgb(0, 0, 0);
  }
</style>
```

Jawaban :

```css

<style>
  .red-text {
    color: rgb(255, 0, 0);
  }
  .orchid-text {
    color: rgb(218, 112, 214);
  }
  .sienna-text {
    color: rgb(160, 82, 45);
  }
  .blue-text {
    color: rgb(0, 0, 255);
  }
</style>

<h1 class="red-text">I am red!</h1>

<h1 class="orchid-text">I am orchid!</h1>

<h1 class="sienna-text">I am sienna!</h1>

<h1 class="blue-text">I am blue!</h1>

```



