# Gunakan Kode Hex Disingkat

Contoh :

Banyak orang merasa kewalahan dengan kemungkinan lebih dari 16 juta warna. Dan sulit untuk mengingat kode hex. Untungnya, Anda bisa mempersingkatnya.

Sebagai contoh, kode hex merah \# FF0000 dapat disingkat menjadi \# F00. Bentuk yang dipersingkat ini memberikan satu digit untuk merah, satu digit untuk warna hijau, dan satu digit untuk warna biru.

Ini mengurangi jumlah warna yang mungkin menjadi sekitar 4.000. Tetapi browser akan menafsirkan \# FF0000 dan \# F00 sebagai warna yang persis sama.

Silakan, coba gunakan kode hex yang disingkat untuk mewarnai elemen yang benar.

| Color | Short Hex Code |
| :--- | :--- |
| Cyan | `#0FF` |
| Green | `#0F0` |
| Red | `#F00` |
| Fuchsia | `#F0F` |

Soal :

1. Berikan elemen h1 Anda dengan teks I am red! warna merah.
2. Gunakan kode hex singkat untuk warna merah sebagai ganti kode hex \# FF0000.
3. Berikan elemen h1 Anda dengan teks I am green! warna hijau.
4. Gunakan kode hex yang disingkat untuk warna hijau sebagai ganti kode hex \# 00FF00.
5. Berikan elemen h1 Anda dengan teks I am cyan!, warna cyan.
6. Gunakan kode hex yang disingkat untuk warna cyan alih-alih kode hex \# 00FFFF.
7. Berikan elemen h1 Anda dengan teks I am fuchsia! warna fuchsia.
8. Gunakan kode hex yang disingkat untuk warna fuchsia sebagai ganti kode hex \# FF00FF.

```css
<style>
  .red-text {
    color: #FF0000;
  }
  .green-text {
    color: #00FF00;
  }
  .dodger-blue-text {
    color: #2998E4;
  }
  .orange-text {
    color: #FFA500;
  }
</style>

<h1 class="red-text">I am red!</h1>

<h1 class="green-text">I am green!</h1>

<h1 class="dodger-blue-text">I am dodger blue!</h1>

<h1 class="orange-text">I am orange!</h1>
```

Jawaban :

```css

<style>
  .red-text {
    color: #F00;
  }
  .fuchsia-text {
    color: #F0F;
  }
  .cyan-text {
    color: #0FF;
  }
  .green-text {
    color: #0F0;
  }
</style>

<h1 class="red-text">I am red!</h1>

<h1 class="fuchsia-text">I am fuchsia!</h1>

<h1 class="cyan-text">I am cyan!</h1>

<h1 class="green-text">I am green!</h1>

```



