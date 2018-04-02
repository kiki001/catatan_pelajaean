# Ubah Ukuran Font dari Elemen

Contoh :

Ukuran font dikontrol oleh properti CSS font-size, seperti ini:

```
h1 {
  ukuran font: 30px;
}
```

Catatan :

Karena perbedaan implementasi browser, Anda mungkin harus berada pada 100% zoom untuk lulus tes pada tantangan ini. Juga, tolong jangan menambahkan atribut class ke elemen p baru Anda.



Soal :

Buat elemen p kedua setelah elemen p yang ada dengan teks kucing ipsum berikut: Purr melompat makan rumput rip sofa tergores berjemur, gudang di mana-mana merobek sofa tidur di wastafel berbulu catnip bulu tergores.

Di dalam tag &lt;style&gt; yang sama yang berisi kelas teks-merah Anda, buat entri untuk elemen p dan atur ukuran font menjadi 16 piksel \(16px\).

```
<style>
  .red-text {
    color: red;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```

Jawaban :

```
<style>
  .red-text {
    color: red;
  }
  
  p{
    font-size: 16px;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>

<p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>

```



