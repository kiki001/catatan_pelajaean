## Memahami Sensitivitas Huruf dalam Variabel

Dalam JavaScript semua variabel dan nama fungsi peka terhadap huruf besar-kecil.Ini berarti kapitalisasi itu penting.

`MYVAR`tidak sama dengan`MyVar`juga tidak`myvar`.Dimungkinkan untuk memiliki beberapa variabel berbeda dengan nama yang sama tetapi casing berbeda.Sangat disarankan agar demi kejelasan, Anda_tidak_menggunakan fitur bahasa ini.

#### Praktek terbaik

Tulis nama variabel dalam JavaScript dicamelCase.DalamcamelCase, nama variabel multi-kata memiliki kata pertama dalam huruf kecil dan huruf pertama dari setiap kata berikutnya ditulis dengan huruf besar.

**Contoh:**

```
var someVariable; 
adalah AnotherVariableName; 
apakah iniVariableNameIsSoLong;
```

Ubah deklarasi dan penugasan yang ada sehingga namanya menggunakan camelCase Jangan membuat variabel baru.



Soal :

1. studlyCapVar didefinisikan dan memiliki nilai 10
2. properCamelCase didefinisikan dan memiliki nilai "A String"
3. titleCaseOver didefinisikan dan memiliki nilai 9000
4. studlyCapVar harus menggunakan camelCase di bagian deklarasi dan penugasan.
5. properCamelCase harus menggunakan camelCase di bagian deklarasi dan penugasan.
6. titleCaseOver harus menggunakan camelCase di bagian deklarasi dan penugasan.

Jawaban :

```
// Declarations
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

// Assignments
studlyCapVar = 10;
properCamelCase = "A String";
titleCaseOver = 9000;
```



