# Gunakan Properti lentur-arah untuk Membuat Row

Menambahkan tampilan: melenturkan ke suatu elemen mengubahnya menjadi wadah fleksibel. Ini memungkinkan untuk menyelaraskan setiap anak dari elemen tersebut ke dalam baris atau kolom. Anda melakukan ini dengan menambahkan properti arah-fleksibel ke item induk dan mengaturnya ke baris atau kolom. Membuat baris akan menyelaraskan anak-anak secara horizontal, dan membuat kolom akan menyelaraskan anak-anak secara vertikal.

Pilihan lain untuk flex-direction adalah reverse-baris dan membalik kolom.

Catatan

Nilai default untuk properti arah-fleksibel adalah baris.

---

Tambahkan properti flex-arah CSS ke elemen \# kotak-kontainer, dan berikan nilai dari baris-mundur.

Soal :

```
Elemen # kotak-kontainer harus memiliki properti arah-fleksibel diatur ke baris-mundur.
```

Jawaban :

```
<style>
  #box-container {
    display: flex;
    height: 500px;
     flex-direction: row-reverse;
  }
  #box-1 {
    background-color: dodgerblue;
    width: 50%;
    height: 50%;
  }

  #box-2 {
    background-color: orangered;
    width: 50%;
    height: 50%;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```



