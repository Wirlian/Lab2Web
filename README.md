### **Langkah-langkahnya**
### 1. Membuat kodingan HTML dan CSSnya
![gambar1](https://user-images.githubusercontent.com/73067481/159172697-5ddfb318-b06a-4cee-beba-0ef14d3b0eb8.JPG)

   ###  Ini Tampilannya
![Gambar2](https://user-images.githubusercontent.com/73067481/159172715-8103732f-b134-485a-b0d3-46a95b9b0141.JPG)

### 2. Kemudian tambahkan deklarasi inline CSS pada tag `<p>` seperti berikut.
![Gambar3](https://user-images.githubusercontent.com/73067481/159172728-f16ddec5-98ac-4ffe-9c56-80d3dffe963b.JPG)

### 3. Buat file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut.
![Gambar4](https://user-images.githubusercontent.com/73067481/159173035-54f989cb-9bcf-4a2e-92f1-68adf98876bc.JPG)

   ### Kemudian tambahkan tag `<link>` untuk merujuk file css yang sudah dibuat pada bagian `<head>`

```
<head>
     <!-- menyisipkan css eksternal -->
     <link rel="stylesheet" href="style_eksternal.css" type="text/css">
     </head>
```
### refresh kembali browser untuk melihat perubahannya.
![Gambar5](https://user-images.githubusercontent.com/73067481/159173114-e99c5fd2-fbf1-4aa3-8ff9-2484c7df6eb2.JPG)

### 4. Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file
    style_eksternal.css, tambahkan kode berikut
![Gambar6](https://user-images.githubusercontent.com/73067481/159173120-1db327b9-0064-4697-aaa1-01ddb19d8d0e.JPG)


### Simpan kembali dan refresh browser untuk melihat perubahannya.
![Gambar7](https://user-images.githubusercontent.com/73067481/159173134-89538c7f-23a8-45e2-95c9-f30f73a71cf1.JPG)


### Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
Jawaban : sudah
2. Apa perbedaan pendeklarasian CSS elemen `h1 {...}` dengan #intro `h1 {...}`? berikan
penjelasannya!
Jawaban : jika `h1`, deklarasi yang tampil hanya `h1`-nya saja.
                 jika ``#intro h1``, seluruh deklarasi yang berada pada #intro h1 akan tampil.
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
Jawaban : yang tampil adalah deklarasi css secara internal, karena berada dalam halaman html
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! `( <p id="paragraf-1" class="text-paragraf"> )`
Jawaban : yang akan tampil yaitu id, karena (id) berfungsi menentukan identitas unik suatu elemen