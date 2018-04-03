# Gunakan Kode Hex untuk Mencampur Warna

Contoh :

Untuk meninjau, kode hex menggunakan 6 digit heksadesimal untuk merepresentasikan warna, masing-masing dua untuk komponen merah \(R\), hijau \(G\), dan biru \(B\).

Dari ketiga warna murni ini \(merah, hijau, dan biru\), kami dapat memvariasikan jumlah masing-masing untuk menciptakan lebih dari 16 juta warna lain!

Misalnya, jeruk berwarna merah murni, dicampur dengan warna hijau, dan tanpa warna biru. Dalam kode hex, ini berarti menjadi \# FFA500.

Digit 0 adalah angka terendah dalam kode hex, dan menunjukkan tidak adanya warna yang lengkap.

Angka F adalah angka tertinggi dalam kode hex, dan mewakili kemungkinan kecerahan maksimum.

Ganti kata-kata warna dalam elemen gaya kami dengan kode hex yang benar

| Color | Hex Code |
| :--- | :--- |
| Dodger Blue | `#2998E4` |
| Green | `#00FF00` |
| Orange | `#FFA500` |
| Red | `#FF0000` |

Soal :

1. Berikan elemen h1 Anda dengan text I am red!  warna merah.
2. Gunakan kode hex untuk warna merah, bukan kata merah.
3. Berikan elemen h1 Anda dengan teks I am green! warna hijau.
4. Gunakan kode hex untuk warna hijau sebagai ganti kata hijau.
5. Berikan elemen h1 Anda dengan teks I am dodger blue! warna belang biru.
6. Gunakan kode hex untuk warna dodger biru, bukan kata dodgerblue.
7. Berikan elemen h1 Anda dengan teksI am orange! warna oranye.
8. Gunakan kode hex untuk warna oranye, bukan kata oranye.

```css
<style>
  body {
    background-color: #000000;
    color: #000000; 
  }
</style>
```

Jawaban :

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



