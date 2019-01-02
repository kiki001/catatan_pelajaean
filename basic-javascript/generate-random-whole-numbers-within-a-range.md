## Menghasilkan Angka Utuh Acak dalam Rentang

Alih-alih menghasilkan angka acak antara nol dan angka yang diberikan seperti yang kita lakukan sebelumnya, kita dapat menghasilkan angka acak yang berada dalam kisaran dua angka tertentu.

Untuk melakukan ini, kami akan menentukan jumlah minimum`min`dan jumlah maksimum`max`.

Inilah rumus yang akan kita gunakan.Luangkan waktu sejenak untuk membacanya dan cobalah memahami apa yang dilakukan kode ini:

`Math.floor(Math.random() * (max - min + 1)) + min`



Buat fungsi yang disebut`randomRange`yang mengambil rentang`myMin`dan`myMax`dan mengembalikan angka acak yang lebih besar atau sama dengan`myMin`, dan kurang dari atau sama dengan`myMax`, inklusif.



Soal :

1. Angka acak terendah yang dapat dihasilkan oleh randomRangeharus sama dengan angka minimum Anda myMin,.
2. Angka acak tertinggi yang dapat dihasilkan oleh randomRangeharus sama dengan angka maksimum Anda myMax,.
3. Angka acak yang dihasilkan oleh randomRangeharus bilangan bulat, bukan desimal.
4. randomRangeharus menggunakan keduanya myMaxdan myMin, dan mengembalikan angka acak dalam rentang Anda.

Jawaban :

```
// Example
function ourRandomRange(ourMin, ourMax) {

  return Math.floor(Math.random() * (ourMax - ourMin + 1)) + ourMin;
}

ourRandomRange(1, 9);

// Only change code below this line.

function randomRange(myMin, myMax) {

  return Math.floor(Math.random() * (myMax - myMin + 1)) + myMin;
}

// Change these values to test your function
var myRandom = randomRange(5, 15);
```



