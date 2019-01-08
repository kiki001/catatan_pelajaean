## Memilih dari Banyak Opsi dengan Beralih Pernyataan

Jika Anda memiliki banyak opsi untuk dipilih, gunakan`switch`pernyataan.Sebuah`switch`pernyataan menguji nilai dan dapat memiliki banyak`case`pernyataan yang menentukan berbagai nilai yang mungkin.Pernyataan dieksekusi dari nilai yang cocok pertama`case`hingga`break`ditemukan.

Ini adalahcontohkodesemu:

```
switch (num) {nilai 
  case1: 
    statement1; 
    istirahat; 
  nilai case2: 
    statement2; 
    istirahat; 
... nilai 
  caseN: 
    statementN; 
    istirahat; 
}
```

`case`nilai-nilai diuji dengan kesetaraan yang ketat \(`===`\).The`break`memberitahu JavaScript untuk berhenti mengeksekusi pernyataan.Jika`break`dihilangkan, pernyataan selanjutnya akan dieksekusi.

Tulis pernyataan sakelar yang menguji`val`dan menetapkan`answer`kondisi berikut:  
`1`- "alpha"  
`2`- "beta"  
`3`- "gamma"  
`4`- "delta"



Soal :

1. caseInSwitch\(1\) harus memiliki nilai "alpha"
2. caseInSwitch\(2\) harus memiliki nilai "beta"
3. caseInSwitch\(3\) harus memiliki nilai "gamma"
4. caseInSwitch\(4\) harus memiliki nilai "delta"
5. Anda tidak boleh menggunakan ifatau elsepernyataan
6. Anda harus memiliki setidaknya 3 breakpernyataan

Jawaban :

```
function caseInSwitch(val) {
  var answer = "";
  // Only change code below this line
  switch(val) {
    case 1:
    answer = "alpha";
    break;
    case 2:
    answer = "beta";
    break;
    case 3:
    answer = "gamma";
    break;
    case 4:
    answer = "delta";
    break;
  }
  
  
  // Only change code above this line  
  return answer;  
}

// Change this value to test
caseInSwitch(1);

```



