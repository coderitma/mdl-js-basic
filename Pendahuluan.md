# Pendahuluan

JavaScript adalah bahasa pemrograman paling populer di dunia.

JavaScript adalah bahasa pemrograman Web.

JavaScript mudah dipelajari.

## Mengapa Mempelajari JavaScript?

JavaScript adalah salah satu dari 3 bahasa yang harus dipelajari semua web developer:

- HTML untuk menentukan konten halaman web.

- CSS untuk menentukan tata letak halaman web.

- JavaScript untuk memprogram perilaku halaman web.

## JavaScript Dapat Mengubah Konten HTML

Salah satu dari banyak method JavaScript adalah getElementById().

Contoh berikut akan "menemukan" elemen HTML (dengan id="demo"), dan mengubah konten elemen (innerHTML) menjadi "Hello JavaScript":

```html
<!DOCTYPE html>
<html>
<body>

<h2>What Can JavaScript Do?</h2>

<p id="demo">JavaScript can change HTML content.</p>

<button type="button" onclick='document.getElementById("demo").innerHTML = "Hello JavaScript!"'>Click Me!</button>

</body>
</html>
```

JavaScript menerima tanda kutip ganda dan tunggal:

```js
document.getElementById('demo').innerHTML = 'Hello JavaScript';
```

## JavaScript Dapat Mengubah Nilai Atribut HTML

Dalam contoh ini JavaScript mengubah nilai atribut src (sumber) dari tag `<img>`:

```js
document.getElementById('myImage').src='pic_bulboff.gif';
```

## JavaScript Dapat Mengubah Style HTML (CSS)

Mengubah style elemen HTML adalah varian dari mengubah atribut HTML:

```js
document.getElementById("demo").style.fontSize = "35px";
```

## JavaScript Dapat Menyembunyikan Elemen HTML

Menyembunyikan elemen HTML dapat dilakukan dengan mengubah style `display`:

```js
document.getElementById("demo").style.display = "none";
```

Dan masih banyak lagi.
