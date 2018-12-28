## Iterate dengan JavaScript Untuk Putaran

Anda dapat menjalankan kode yang sama beberapa kali dengan menggunakan loop.

Tipe paling umum dari JavaScript loop disebut "`for loop`" karena dijalankan "untuk" beberapa kali tertentu.

Untuk loop dideklarasikan dengan tiga ekspresi opsional yang dipisahkan oleh titik koma:

`for ([initialization]; [condition]; [final-expression])`

The`initialization`pernyataan dieksekusi satu kali saja sebelum loop dimulai.Ini biasanya digunakan untuk mendefinisikan dan mengatur variabel loop Anda.

The`condition`pernyataan dievaluasi pada awal setiap iterasi loop dan akan terus selama itu mengevaluasi ke`true`.Ketika`condition`berada`false`di awal iterasi, loop akan berhenti dieksekusi.Ini berarti jika`condition`dimulai sebagai`false`, loop Anda tidak akan pernah dijalankan.

Ini`final-expression`dieksekusi pada akhir setiap iterasi loop, sebelum`condition`pemeriksaanberikutnyadan biasanya digunakan untuk menambah atau mengurangi counter loop Anda.

Dalam contoh berikut ini kita mulai dengan`i = 0`dan beralih sementara kondisi kita`i < 5`benar.Kami akan increment`i`oleh`1`di setiap loop iterasi dengan`i++`sebagai kami`final-expression`.

```
var ourArray = []; 
untuk (var i = 0; i <5; i ++) { 
  ourArray.push (i); 
}
ourArraysekarang akan berisi [0,1,2,3,4].
```

Soal :

1. Anda harus menggunakan forloop untuk ini.
2. myArrayharus sama \[1,2,3,4,5\].

Jawaban :

```
// Example
var ourArray = [];

for (var i = 0; i < 5; i++) {
  ourArray.push(i);
}

// Setup
var myArray = [];

// Only change code below this line.
for (var i = 1; i <= 5; i++){
  myArray.push(i);
}

```



