## Menguji Objek untuk Properti

Terkadang berguna untuk memeriksa apakah properti dari objek yang diberikan ada atau tidak.Kita dapat menggunakan`.hasOwnProperty(propname)`metode objek untuk menentukan apakah objek tersebut memiliki nama properti yang diberikan.`.hasOwnProperty()`kembali`true`atau`false`jika properti ditemukan atau tidak.

**Contoh**

```
var myObj = {
  top: "hat",
  bottom: "pants"
};
myObj.hasOwnProperty("top"); // true
myObj.hasOwnProperty("middle"); // false
```

Memodifikasi fungsi`checkObj`untuk menguji`myObj`untuk`checkProp`.Jika properti ditemukan, kembalikan nilai properti itu.Jika tidak, kembalilah`"Not Found"`.

Soal :

1. checkObj\("gift"\)should return"pony".
2. checkObj\("pet"\)should return"kitten".
3. checkObj\("house"\)should return"Not Found".

Jawaban :

```
// Setup
var myObj = {
  gift: "pony",
  pet: "kitten",
  bed: "sleigh"
};

function checkObj(checkProp) {
  // Your Code Here
  if (myObj.hasOwnProperty(checkProp) === true) {
    return myObj[checkProp];
  } else {
    return "Not Found";
  }
}

// Test your code by modifying these values
checkObj("gift");
```



