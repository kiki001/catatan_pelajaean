# Gunakan Kelas CSS untuk Menata Elemen

Kelas adalah gaya yang dapat digunakan kembali yang dapat ditambahkan ke elemen HTML.

Berikut ini contoh deklarasi kelas CSS:Kelas adalah gaya yang dapat digunakan kembali yang dapat ditambahkan ke elemen HTML.

Berikut ini contoh deklarasi kelas CSS :

```
<style>
  .blue-text {
    warna biru;
  }
</ style>
```

Anda dapat melihat bahwa kami telah membuat kelas CSS yang disebut biru-teks dalam tag &lt;style&gt;.

Anda dapat menerapkan kelas ke elemen HTML seperti ini :

```
<h2 class = "blue-text"> CatPhotoApp </ h2>
```

Perhatikan bahwa dalam elemen gaya CSS Anda, kelas harus dimulai dengan periode. Dalam deklarasi kelas elemen HTML Anda, kelas tidak boleh dimulai dengan periode.

Soal :

1. Di dalam elemen gaya Anda, ubah pemilih h2 menjadi .red-teks dan perbarui nilai warna dari biru ke merah.
2. Berikan elemen h2 Anda atribut class dengan nilai 'red-text'.

```
<style>
  h2{
    color:blue;
  }
</style>

<h2>CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```

Jawaban :

```
<style>
  .red-text {
    color: red;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```



