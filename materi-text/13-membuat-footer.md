## Membuat Footer

Sekarang kita akan membuat footer sebagai penutup dari landing page kita.

Kita gunakan elemen `<footer>`, lalu tambahkan class `bg-dark` untuk mengatur agar warna background menjadi gelap. Kalian bisa sesuaikan class dengan kebutuhan kalian, misal mau diubah menjadi bg-primary atau yang lainnya.

 

```html
<footer class="bg-dark">

</footer>
```

Di dalam footer ini kita akan tampilkan icon-icon media social dan juga text copyright, kita bisa buat elemen `<div>` dengan **class** `col-lg-12` terlebih dahulu.

Lalu tambahkan **style** `padding` untuk mengatur paddingnya.

```html
<footer class="bg-dark" style="padding:10px">
    <div class="col-lg-12">

    </div>
</footer>
```

Setelah itu, khusus untu icon media social kita bisa menempatkannya di dalam elemen `<div>` lagi misal dengan **style** `text-align: center` untuk menempatkan icon-icon tersebut di tengah.

```html
<footer class="bg-dark">
    <div class="col-lg-12" style="padding:10px">
 	  <div style="text-align: center;">
 	  
 	  
 	   </div>
    </div>
</footer>
```

Lalu mulai buat icon-icon media socialnya, misal seperti di bawah ini.

```html
<a href="#" class="text-light"><i class=" fab fa-facebook"></i></a>
```

Kode untuk footer kita menjadi seperti berikut ini :

```html
  <footer class="bg-dark">
     <div class="col-lg-12" style="padding:10px">
       <div style="text-align: center;">
         <a href="#" class="text-light"><i class=" fab fa-facebook"></i></a>
         <a href="#" class="text-light"><i class="fab fa-twitter"></i></a>
         <a href="#" class="text-light"><i class="fab fa-instagram"></i></a>
        </div>
 </footer>
```

Terakhir kita buat text copyright sebagai berikut :

```html
<p class="text-center text-secondary">Copyright &copy Codepolitan 2020</p> 
```

Sehingga kode lengkap untuk footer menjadi seperti berikut ini.

```html
  <footer class="bg-dark">
     <div class="col-lg-12" style="padding:10px">
       <div style="text-align: center;">
         <a href="#" class="text-light"><i class=" fab fa-facebook"></i></a>
         <a href="#" class="text-light"><i class="fab fa-twitter"></i></a>
         <a href="#" class="text-light"><i class="fab fa-instagram"></i></a>
        </div>
         <p class="text-center text-secondary">Copyright &copy Codepolitan 2020</p> 
 </footer>
```

Hasilnya sebagai berikut :

![](../assets/images/footer.png)

