# Variabel dan Tipe Data

Apa itu variabel dalam bahasa pemrograman ?

Variabel adalah tempat penyimpanan dimana penyimpanan itu diberi nama, dimana nama yang digunakan harus unik.

## Jenis-Jenis Mendeklarasikan Variabel

Dalam bahasa pemrograman JavaScript sendiri memiliki **3 cara** mendeklarasikan sebuah variabel, yaitu

1. `const` (constant): sifatnya konstan tidak bisa diubah
2. `let` (let it change): sifatnya bisa diubah, lebih aman untuk digunakan
3. `var` (variable): sifatnya bisa diubah, tidak aman untuk digunakan

## Jenis-Jenis Tipe Data

Untuk tipe data, JavaScript memiliki banyak tipe data,
kali ini membahas 3 tipe data dasar yang sering digunakan, yaitu:

1.  `string`

Merupakan tipe data yang berupa tulisan/teks. Untuk mendeklarasikannya, gunakan tanda (`'`), (`"`), atau (` `` `).

2.  `number`

Merupakan tipe data yang berupa angka. Bisa berupa bilangan biasa (misal 1,2,3, dst.) juga bilangan yang memiliki koma, tetapi bilangan yang memiliki koma, tanda komanya diganti dengan titik (misal 1.5, 3.14, 7.27, 19.45 dst...).

3.  `boolean`

Merupakan tipe data yang berupa hal kelogisan. Valuenya hanya dua, `true` dan `false`.

4. `null`

Merupakan tipe data yang biasanya digunakan untuk menyatakan suatu yang tidak ada. null ini bersifat falsy jika digunakan untuk boolean operator. Value dari `null` hanya `null`.

5. `undefined`

Merupakan tipe data yang biasanya digunakan untuk menyatakan suatu yang tak terdefinisikan sebelumnya, akan bersifat falsy jika digunakan untuk boolean operator. Value dari `undefined` hanya `undefined`.

6.  `object`

Merupakan tipe data yang mempunyai pasangan key dan value. Maksud dari key adalah nama yang harus diberikan untuk dijadikan tanda pengenal, supaya value dari object bisa digunakan.

Object ini menggunakan kurung kurawal ({}) untuk menyimpan pasangan dari key dan value.

### Hint

Jika mengandai-andai apa itu null dan undefined, bayangkan sebuah tempat tisu toilet yang lengkap.

Jika tisu toilet habis akan menyisakan kardus, valuenya akan menjadi 0. Kardus tisu toilet tersebut jika dibuang maka valuenya akan menjadi null.

Jika tempat tisu toilet itu dibongkar, maka valuenya undefined.
Lihat meme ini:

![Meme Penjelasan](https://pbs.twimg.com/media/DusCOfyXcAA9_F7?format=jpg&name=large)

Sumber meme [original](https://twitter.com/ddprrt/status/1074955395528040448).

> Catatan: Semua tipe data bisa menggunakan semua tiga jenis variabel yang ada di JavaScript

Contoh

```js
const umur = 15;
console.log(umur); // 15
```

Cek file [pertama](variableAndDataTypes1.js) dan [kedua](variableAndDataTypes2.js) untuk contoh lebih lengkapnya.
