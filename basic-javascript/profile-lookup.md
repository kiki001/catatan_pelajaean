## Pencarian Profil

Kami memiliki berbagai objek yang mewakili orang yang berbeda di daftar kontak kami.

Sebuah`lookUpProfile`fungsi yang mengambil`name`dan properti \(`prop`\) sebagai argumen telah pra-ditulis untuk Anda.

Fungsi harus memeriksa apakah`name`kontak yang sebenarnya`firstName`dan properti yang diberikan \(`prop`\) adalah properti dari kontak itu.

Jika keduanya benar, maka kembalikan "nilai" properti itu.

Jika`name`tidak sesuai dengan kontak apa pun kemudian kembali`"No such contact"`

Jika`prop`tidak sesuai dengan properti yang valid dari kontak yang ditemukan cocok`name`lalu kembali`"No such property"`



Soal :

1. "Kristian", "lastName" harus kembali "Vos"
2. "Sherlock", "likes" harus kembali \["Intriguing Cases", "Violin"\]
3. "Harry","likes" harus mengembalikan array
4. "Bob", "number" harus mengembalikan "Tidak ada kontak seperti itu"
5. "Bob", "potato" harus mengembalikan "Tidak ada kontak seperti itu"
6. "Akira", "address" harus mengembalikan "Tidak ada properti seperti itu"

Jawaban :

```
//Setup
var contacts = [
    {
        "firstName": "Akira",
        "lastName": "Laine",
        "number": "0543236543",
        "likes": ["Pizza", "Coding", "Brownie Points"]
    },
    {
        "firstName": "Harry",
        "lastName": "Potter",
        "number": "0994372684",
        "likes": ["Hogwarts", "Magic", "Hagrid"]
    },
    {
        "firstName": "Sherlock",
        "lastName": "Holmes",
        "number": "0487345643",
        "likes": ["Intriguing Cases", "Violin"]
    },
    {
        "firstName": "Kristian",
        "lastName": "Vos",
        "number": "unknown",
        "likes": ["JavaScript", "Gaming", "Foxes"]
    }
];


function lookUpProfile(firstName, prop){
// Only change code below this line
    for (var i=0; i < contacts.length; i++) {
    if (contacts[i].firstName === firstName) {
      if (contacts[i].hasOwnProperty(prop)) {
        return contacts[i][prop];
      }
      else {
        return "No such property";
      }
    }
  }
  return "No such contact";
// Only change code above this line
}

// Change these values to test your function
lookUpProfile("Akira", "likes");
```



