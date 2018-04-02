# Tentukan Keluarga Font dari Elemen

Contoh :  
Anda dapat mengatur font elemen dengan menggunakan properti font-family.

Misalnya, jika Anda ingin mengatur font elemen h2 Anda menjadi Sans-serif, Anda akan menggunakan CSS berikut:

```
h2 {
    font-family: Sans-serif;
    }
```

Soal :

Buat semua elemen p menggunakan font Monospace.

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

Jawaban :

```

<style>
  .red-text {
    color: red;
  }

  p {
    font-size: 16px;
    font-family:monospace;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>

```



