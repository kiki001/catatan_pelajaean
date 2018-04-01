# Gunakan pemilih CSS untuk Elemen Gaya

contoh :

Dengan CSS, ada ratusan properti CSS yang dapat Anda gunakan untuk mengubah tampilan elemen pada halaman Anda. Saat Anda memasukkan

```
<h2 style = "color: red">CatPhotoApp</h2>
```

Anda memberikan elemen h2 individual itu gaya inline. Itu salah satu cara untuk menambahkan gaya ke elemen, tetapi cara yang lebih baik adalah dengan menggunakan CSS, yang merupakan singkatan dari Cascading Style Sheets. Di bagian atas kode Anda, buat elemen gaya seperti ini:

```
<style>

</style>
```

Di dalam elemen gaya itu, Anda dapat membuat pemilih CSS untuk semua elemen h2. Misalnya, jika Anda ingin semua elemen h2 menjadi merah, elemen gaya Anda akan terlihat seperti ini:

```
<style>
   h2 {color: red;} 
</style>
```

Perhatikan bahwa penting untuk memiliki kurung kurawal pembuka dan penutup \({and}\) di sekitar setiap gaya elemen. Anda juga perlu memastikan bahwa elemen elemen Anda adalah antara tag gaya pembuka dan penutup. Akhirnya, pastikan untuk menambahkan titik koma ke akhir setiap elemen elemen Anda.

Soal :

Hapus atribut gaya elemen h2 Anda dan sebagai gantinya buat elemen gaya CSS. Tambahkan CSS yang diperlukan untuk mengubah semua elemen h2 menjadi biru.

```
<h2 style="color:red">CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```

Jawaban :

```
<style>
  h2{
    color:blue;
  }
</style>

<h2>CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```



