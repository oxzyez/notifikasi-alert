# notifikasi-alert
ini adalah codenya untuk membuat notifikasi viral yang ada di tiktok, kalian bisa mengunakan untuk, ulang tahun, hari ibu, gombal dll, semoga code ini bisa membatu kln membuat notofikasi alertnya

using:
<br>HTML, CSS</br>

## Menambahkan Pesan notifikasi

### 1. Tambahkan di file index.html
Setelah baris 9, isilah kata kata yang kalian inginkan yang telah di beri nomer, dari nomer 9 sampai 15

```html
    <script>
      alert ("1")
      alert ("2")
      alert ("3")
      alert ("4")
      alert ("5")
      alert ("6")
      alert ("7")
    </script>
```

Dan edit juga bagian 19, untuk bagian halaman untuk chatiing
```html
        <div class="wrapper">
        <div class="tengah">
            <section id="banner">
                <h2>TITLE</h2>
                <h1 class="description">deskripsi</h1>
                <div class="click">
                  <p><a href="whatsapp link..." class="click-button">click</a></p>
                </div>
            </section>
        </div>
    </div>
```

untuk "href=" whatsaps gunakan format berikut untuk telepon
```html
https://api.whatsapp.com/send?phone=NoWhatsapp&text=KataSambutan
```
dan untuk format textnya stylingnya
```html
spasi = %20
baris baru = %0A
titik dua = %3A
```

### 2. Editan di file style.css
Di bagain file style.css-nya kalian hanya edit pada code yang ada tanda bintang
```css
body {
    margin: 0px;
    padding: 0px;
    font-family: 'Fira Sans', sans-serif;*
    background-color: #406882;*
}
```

```css
h2 {
    font-family: 'Pushster', cursive;*
    font-weight: 800;
    font-size: 75px;
    margin-bottom: 20px;
    color: #ffffff;
    width: 100%;
    line-height: 50px;
    text-align: center;
    padding-top: 10%;
    text-shadow: black;
}
```

```css
h1 {
    font-family: 'Shizuru', cursive;*
    font-weight: 45;
    font-size: px;
    margin-top: 0;
    color: #ffffff;
    width: 100%;
    line-height: 50px;
    text-align: center;
    padding-top: 0;
}
```
Dan lain lain, untuk pembahasaannya ada di youtube channel saya ada di channel vootrex
sekian dan terima kasih
