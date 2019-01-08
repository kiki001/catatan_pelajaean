## Kode Golf

Dalam permainan[golf](https://en.wikipedia.org/wiki/Golf)setiap lubang memiliki`par`arti jumlah rata-rata`strokes`pegolf diharapkan untuk membuat bola dalam lubang untuk menyelesaikan permainan.Tergantung pada seberapa jauh`par`Anda`strokes`berada diatas atau di bawah, ada nama panggilan yang berbeda.

Fungsi Anda akan diteruskan`par`dan`strokes`argumen.Kembalikan string yang benar sesuai dengan tabel ini yang mencantumkan stroke dalam urutan prioritas;atas \(tertinggi\) ke bawah \(terendah\):

| Stroke | Kembali |
| :--- | :--- |
| 1 | "Dalam satu lubang!" |
| &lt;= oleh - 2 | "Burung rajawali" |
| oleh - 1 | "Birdie" |
| oleh | "Dengan" |
| oleh +1 | "Bogey" |
| oleh + 2 | "Double Bogey" |
| &gt; = dengan + 3 | "Pulang ke rumah!" |

`par`dan`strokes`akan selalu berupa angka dan positif.Kami telah menambahkan larik semua nama untuk kenyamanan Anda.



Soal :

1. golfScore\(4, 1\) harus mengembalikan "Hole-in-one!"
2. golfScore\(4, 2\) harus mengembalikan "Elang"
3. golfScore\(5, 2\) harus mengembalikan "Elang"
4. golfScore\(4, 3\) harus mengembalikan "Birdie"
5. golfScore\(4, 4\) harus mengembalikan "Par"
6. golfScore\(1, 1\) harus mengembalikan "Hole-in-one!"
7. golfScore\(5, 5\) harus mengembalikan "Par"
8. golfScore\(4, 5\) harus mengembalikan "Bogey"
9. golfScore\(4, 6\) harus mengembalikan "Double Bogey"
10. golfScore\(4, 7\) harus kembali "Pulang!"
11. golfScore\(5, 9\) harus kembali "Pulang!"

Jawaban :

```
var names = ["Hole-in-one!", "Eagle", "Birdie", "Par", "Bogey", "Double Bogey", "Go Home!"];
function golfScore(par, strokes) {
  // Only change code below this line
  if( strokes == 1){
    return "Hole-in-one!";
    // Only change code above this line
  }
  else if (strokes <= par - 2){
    return "Eagle";
  }
  else if (strokes <= par - 1){
    return "Birdie";
  }
  else if (strokes === par){
    return "Par";
  }
  else if (strokes <= par + 1 ){
    return "Bogey";
  }
  else if (strokes >= par + 3){
    return "Go Home!";
  }
  else if (strokes <= par + 2){
    return "Double Bogey";
  }
}

// Change these values to test
golfScore(5, 4);
```



