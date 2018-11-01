# Gunakan Properti Steno yang fleksibel

Ada jalan pintas yang tersedia untuk mengatur beberapa properti yang fleksibel sekaligus. Sifat flex-grow, flex-shrink, dan flex-basis semuanya dapat disatukan dengan menggunakan properti flex.

Misalnya, fleksibel: 1 0 10px; akan mengatur item ke flex-grow: 1 ;, flex-shrink: 0 ;, dan flex-base: 10px ;.

Pengaturan properti default fleksibel: 0 1 otomatis ;.

---

Tambahkan properti CSS dengan flex ke \# box-1 dan \# box-2. Berikan \# box-1 nilai sehingga flex-grow-nya adalah 2, flex-shrink-nya adalah 2, dan flex-basisnya adalah 150px. Berikan \# box-2 nilai sehingga flex-grow-nya adalah 1, flex-shrink-nya adalah 1, dan flex-basisnya adalah 150px.

Nilai-nilai ini akan menyebabkan \# kotak-1 tumbuh untuk mengisi ruang ekstra pada dua kali laju \# kotak-2 ketika wadah lebih besar dari 300px dan menyusut dua kali lipat dari tingkat \# kotak-2 saat penampung kurang dari 300px. 300px adalah ukuran gabungan dari nilai basis flex dari dua kotak.



Soal :

1. Elemen \# box-1 harus memiliki properti lentur yang disetel ke nilai 2 2 150px.
2. Elemen \# box-2 harus memiliki properti lentur yang disetel ke nilai 1 1 150px.
3. Kode Anda harus menggunakan properti lentur untuk \# kotak-1 dan \# kotak-2.

Jawaban :

```
<style>
  #box-container {
    display: flex;
    height: 500px;
  }
  #box-1 {
    background-color: dodgerblue;
    flex: 2 2 150px;
    height: 200px;
  }

  #box-2 {
    background-color: orangered;
    flex: 1 1 150px;
    height: 200px;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```



