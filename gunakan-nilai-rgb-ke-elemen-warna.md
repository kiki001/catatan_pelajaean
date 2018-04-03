# Gunakan nilai RGB ke Elemen Warna

Contoh :

Cara lain Anda dapat mewakili warna dalam CSS adalah dengan menggunakan nilai-nilai RGB.

Nilai RGB untuk hitam terlihat seperti ini:

```
rgb (0, 0, 0)
```

Nilai RGB untuk putih terlihat seperti ini:

```
rgb (255, 255, 255)
```

Alih-alih menggunakan enam digit heksadesimal seperti yang Anda lakukan dengan kode hex, dengan RGB Anda menetapkan kecerahan setiap warna dengan angka antara 0 dan 255.

Jika Anda melakukan matematika, dua digit untuk satu warna sama dengan 16 kali 16, yang memberi kita 256 nilai total. Jadi RGB, yang mulai menghitung dari nol, memiliki jumlah nilai yang sama persis seperti kode hex.

Mari ganti kode hex dalam warna latar belakang elemen body kita dengan nilai RGB untuk hitam: rgb \(0, 0, 0\)

Soal :

1. Elemen body Anda harus memiliki latar belakang hitam. 
2. Gunakan rgb untuk memberikan elemen body Anda warna hitam. 

Misalnya :

```css
body { background-color: rgb(255, 165, 0); }
```

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

Jawaban :

```css

<style>
  body {
    background-color: rgb(0, 0, 0);
  }
</style>

```



