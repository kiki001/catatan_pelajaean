## Memanipulasi Objek Kompleks

Terkadang Anda mungkin ingin menyimpan data dalamStruktur Data yangfleksibel.Objek JavaScript adalah salah satu cara untuk menangani data yang fleksibel.Mereka memungkinkan untuk kombinasi acak daristring,angka,boolean,array,fungsi, danobjek.

Berikut adalah contoh struktur data yang kompleks:

```
var ourMusic = [ 
  { 
    "artis": "Daft Punk", 
    "judul": "Pekerjaan Rumah", 
    "release_year": 1997, 
    "format": [ 
      "CD", 
      "Kaset", 
      "LP" 
    ], 
    "emas": true 
  } 
];
```

Ini adalah array yang berisi satu objek di dalamnya.Objek memiliki berbagai potonganmetadatatentang album.Ini juga memiliki`"formats"`arraybersarang.Jika Anda ingin menambahkan lebih banyak catatan album, Anda dapat melakukan ini dengan menambahkan catatan ke array tingkat atas.

Objek menyimpan data di properti, yang memiliki format nilai kunci.Dalam contoh di atas,`"artist": "Daft Punk"`adalah properti yang memiliki kunci`"artist"`dan nilai`"Daft Punk"`.

[JavaScript Object Notation](http://www.json.org/)atau`JSON`format pertukaran data terkait yang digunakan untuk menyimpan data.

```
{ 
  "artis": "Daft Punk", 
  "judul": "Pekerjaan Rumah", 
  "release_year": 1997, 
  "format": [ 
    "CD", 
    "Cassette", 
    "LP" 
  ], 
  "gold": true 
}
```

**Catatan**  
Anda harus menempatkan koma setelah setiap objek dalam array, kecuali itu adalah objek terakhir dalam array.

Tambahkan album baru ke`myMusic`array.Tambahkan`artist`dan`title`string,`release_year`angka, dan`formats`array string.

Soal :

1. myMusic harus berupa array
2. myMusic harus memiliki setidaknya dua elemen
3. myMusic\[1\] harus menjadi objek
4. myMusic\[1\] harus memiliki setidaknya 4 properti
5. myMusic\[1\]harus mengandung artistproperti yang merupakan string
6. myMusic\[1\]harus mengandung titleproperti yang merupakan string
7. myMusic\[1\]harus mengandung release\_yearproperti yang merupakan angka
8. myMusic\[1\]harus mengandung formatsproperti yang merupakan array
9. formats harus berupa array string dengan setidaknya dua elemen

Jawaban :

```
var myMusic = [
  {
    "artist": "Billy Joel",
    "title": "Piano Man",
    "release_year": 1973,
    "formats": [ 
      "CD",
      "8T",
      "LP"
    ],
    "gold": true
  }
  // Add record here
  
];
myMusic.push(
    {"artist": "Devo", "title": "We are Devo", "release_year": 1984, "formats": ["CD", "Cassette", "LP"]}
);
```



