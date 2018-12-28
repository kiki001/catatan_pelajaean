## Hitung Mundur Dengan For Loop

A for loop juga dapat menghitung mundur, selama kita dapat menentukan kondisi yang tepat.

Dalam rangka untuk menghitung mundur dengan berpasangan, kita harus mengubah kami`initialization`,`condition`dan`final-expression`.

Kami akan mulai di`i = 10`dan loop sementara`i > 0`.Kami akan mengurangi`i`2 setiap loop dengan`i -= 2`.

```
var ourArray = []; 
untuk (var i = 10; i> 0; i- = 2) { 
  ourArray.push (i); 
}
```

`ourArray`sekarang akan berisi`[10,8,6,4,2]`.

Mari kita ubah`initialization`dan`final-expression`jadi kita bisa menghitung mundur dua kali dengan angka ganjil.

Dorong angka ganjil dari 9 hingga 1 untuk`myArray`menggunakan`for`loop.

Soal :

1. Anda harus menggunakan forloop untuk ini.
2. Anda harus menggunakan metode array push.
3. myArrayharus sama \[9,7,5,3,1\].

Jawaban :

```
// Example
var ourArray = [];

for (var i = 10; i > 0; i -= 2) {
  ourArray.push(i);
}

// Setup
var myArray = [];

// Only change code below this line.

for(var i = 9; i > 0; i-=2){
  myArray.push(i);
}
```



