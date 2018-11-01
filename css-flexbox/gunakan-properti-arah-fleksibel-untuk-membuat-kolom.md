# Gunakan Properti arah-fleksibel untuk Membuat Kolom

Dua tantangan terakhir menggunakan properti arah-fleksibel diatur ke baris. Properti ini juga dapat membuat kolom dengan menumpuk secara vertikal anak-anak dari wadah fleksibel.

---

Tambahkan properti flex-arah CSS ke elemen \# box-container, dan berikan nilai kolom.

Soal :

1. Elemen \# kotak-kontainer harus memiliki properti arah-fleksibel yang disetel ke kolom.

Jawaban :

```
<style>
  #box-container {
    display: flex;
    height: 500px;
    flex-direction: column;
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



