# Gunakan Properti flex-basis untuk Mengatur Ukuran Awal Item

Properti flex-base menentukan ukuran awal dari item sebelum CSS membuat penyesuaian dengan flex-shrink atau flex-grow.

Satuan yang digunakan oleh properti basis-flex sama dengan properti ukuran lainnya \(px, em,%, dll.\). Nilai item ukuran otomatis berdasarkan konten.

Setel ukuran awal kotak menggunakan basis fleksibel. Tambahkan properti CSS secara fleksibel ke \# box-1 dan \# box-2. Beri \# kotak-1 nilai 10em dan \# kotak-2 nilai 20em.

Soal :

1. Elemen \# kotak-1 harus memiliki properti berbasis-lentur.
2. Elemen \# kotak-1 harus memiliki nilai dasar 10em fleksibel.
3. Elemen \# box-2 harus memiliki properti berbasis-lentur.
4. Elemen \# box-2 harus memiliki nilai basis-fleksi 20em.

Jawaban :

```
<style>
  #box-container {
    display: flex;
    height: 500px;
  }
  
  #box-1 {
    background-color: dodgerblue;
    height: 200px;
    flex-basis: 10em;
  }
  
  #box-2 {
    background-color: orangered;
    height: 200px;
    flex-basis: 20em;
  }
</style>
  
<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```



