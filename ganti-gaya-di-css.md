# Ganti Gaya di CSS

Contoh :

Kelas "teks merah muda" kami mengalahkan deklarasi CSS elemen tubuh kami!

Kami baru saja membuktikan bahwa kelas kami akan mengesampingkan CSS elemen tubuh. Jadi pertanyaan logis berikutnya adalah, apa yang bisa kita lakukan untuk mengesampingkan kelas teks merah muda kita?

Buat kelas CSS tambahan yang disebut teks biru yang memberikan elemen warna biru. Pastikan itu di bawah deklarasi kelas teks merah muda Anda.

Terapkan kelas teks biru ke elemen h1 Anda di samping kelas teks merah muda Anda, dan mari kita lihat mana yang menang.

Menerapkan beberapa atribut kelas ke elemen HTML dilakukan dengan spasi di antara mereka seperti ini:

```css
class = "class1 class2"
```

Catatan: Tidak masalah urutan kelas mana yang terdaftar di elemen HTML.

Namun, urutan deklarasi kelas di bagian &lt;style&gt; adalah yang penting. Deklarasi kedua akan selalu didahulukan dari yang pertama. Karena .blue-text dideklarasikan kedua, ia mengesampingkan atribut .pink-text

Soal :

1. Elemen h1 Anda harus memiliki pink-text kelas.
2. Elemen h1 Anda harus memiliki blue-text kelas.
3. blue-text dan pink-text harus memiliki elemen h1 yang sama.
4. Elemen h1 Anda harus berwarna blue.

```css
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
  .blue-text{
    color:blue;
  }
</style>
<h1 class="pink-text blue-text">Hello World!</h1>
```



