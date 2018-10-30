# Gunakan display: flex to Position Two Boxes

Bagian ini menggunakan gaya tantangan bergantian untuk menunjukkan bagaimana menggunakan CSS untuk memosisikan elemen secara fleksibel. Pertama, tantangan akan menjelaskan teori, maka tantangan praktis menggunakan komponen tweet sederhana akan menerapkan konsep flexbox.

Menempatkan tampilan properti CSS: fleksibel; pada elemen memungkinkan Anda untuk menggunakan properti fleksibel lainnya untuk membangun halaman responsif.

Tambahkan tampilan properti CSS ke \# kotak-kontainer dan atur nilainya untuk melenturkan.

Soal :

```
# box-container harus memiliki properti tampilan yang disetel ke nilai flex.
```

Jawaban :

```
<style>
  #box-container {
    height: 500px;
    display: flex;
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



