# Gunakan Kode Hex untuk Warna Spesifik

Contoh :

warna-warna epresent dalam CSS? Salah satu cara ini disebut kode heksadesimal, atau kode hex untuk pendek.

Kami biasanya menggunakan desimal, atau basis 10 angka, yang menggunakan simbol 0 hingga 9 untuk setiap digit. Hexadecimals \(atau hex\) adalah bilangan 16 dasar. Ini berarti ia menggunakan enam belas simbol berbeda. Seperti desimal, simbol 0-9 mewakili nilai nol hingga sembilan. Kemudian A, B, C, D, E, F mewakili nilai sepuluh hingga lima belas. Secara keseluruhan, 0 hingga F dapat mewakili digit dalam heksadesimal, memberi kita 16 kemungkinan nilai total.

Dalam CSS, kita dapat menggunakan 6 digit heksadesimal untuk merepresentasikan warna, masing-masing dua untuk komponen merah \(R\), hijau \(G\), dan biru \(B\). Misalnya, \# 000000 berwarna hitam dan juga nilai serendah mungkin.

Ganti kata hitam di warna latar belakang elemen tubuh kita dengan representasi kode hex-nya, \# 000000.

Soal :

Berikan elemen body Anda warna latar belakang hitam.

Gunakan kode hex untuk warna hitam, bukan kata hitam.

```css
body { color: #000000; }
```

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

Jawaban :

```css

<style>
  body {
    background-color: #000000;
    color: #000000; 
  }
</style>

```



