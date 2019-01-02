## Nesting For Loops

Jika Anda memiliki array multi-dimensi, Anda dapat menggunakan logika yang sama dengan titik jalan sebelumnya untuk mengulang melalui array dan sub-array apa pun.Berikut ini sebuah contoh:

```
var arr = [ 
  [1,2], [3,4], [5,6] 
]; 
untuk (var i = 0; i <arr.length; i ++) { 
  for (var j = 0; j <arr [i] .length; j ++) { 
    console.log (arr [i] [j]); 
  } 
}
```

Ini menghasilkan setiap sub-elemen dalam`arr`satu per satu.Perhatikan bahwa untuk loop batin, kita memeriksa`.length`dari`arr[i]`, karena`arr[i]`itu sendiri array.

Ubah fungsi`multiplyAll`sehingga mengalikan`product`variabel dengan setiap angka dalam sub-array dari`arr`

Soal :

1. multiplyAll\(\[\[1\],\[2\],\[3\]\]\) harus kembali 6
2. multiplyAll\(\[\[1,2\],\[3,4\],\[5,6,7\]\]\) harus kembali 5040
3. multiplyAll\(\[\[5,1\],\[0.2, 4, 0.5\],\[3, 9\]\]\) harus kembali 54

Jawaban :

```
function multiplyAll(arr) {
  var product = 1;
  // Only change code below this line
  
  // Only change code above this line
  return product;
}

// Modify values below to test your code
multiplyAll([[1,2],[3,4],[5,6,7]]);

function multiplyAll(arr) {
  var product = 1;

  for (var i=0; i<arr.length; i++){
    for(var j=0; j<arr[i].length; j++){
      product = product * arr[i][j];
    }
  }

return product;
}



```



