# Mewarisi Gaya dari Elemen Tubuh

Contoh :

Sekarang kami telah membuktikan bahwa setiap halaman HTML memiliki elemen body, dan bahwa elemen body juga dapat ditata dengan CSS.

Ingat, Anda dapat menata elemen tubuh Anda seperti elemen HTML lainnya, dan semua elemen Anda yang lain akan mewarisi gaya elemen tubuh Anda.

Pertama, buat elemen h1 dengan teks Hello World

Kemudian, mari kita beri semua elemen pada halaman Anda warna hijau dengan menambahkan warna: hijau; untuk deklarasi elemen elemen tubuh Anda.

Akhirnya, berikan elemen tubuh Anda keluarga font Monospace dengan menambahkan font-family: Monospace; untuk deklarasi elemen elemen tubuh Anda.

Soal :

1. Buat elemen h1.
2. Elemen h1 Anda harus memiliki teks Hello World.
3. Pastikan elemen h1 Anda memiliki tag penutup.
4. Berikan elemen tubuh Anda warna properti hijau.
5. Berikan elemen tubuh Anda properti font-keluarga Monospace.
6. Elemen h1 Anda harus mewarisi font Monospace dari elemen body Anda.
7. Elemen h1 Anda harus mewarisi warna hijau dari elemen tubuh Anda.

```
<style>

body {
  background-color: black;
}

</style>
```

Jawaban :

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



