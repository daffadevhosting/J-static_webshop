#### Jekyll online shop checkout form whatsapp

J-static adalah website Online Shop berbasis Jekyll yang dibuat dengan simpleCart(js) versi IDR (Indonesia Rupiah), dengan checkout form langsung melalui *WhatsApp / *Telegram.

Repo: https://github.com/daffadevhosting/J-static_webshop.git<br>
Demo: https://j-store.pages.dev/

dibangun dengan Jekyll v4.2.2 & Bootstrap v5.2

Instal dependensi dengan [Bundler](http://bundler.io/)

```shell
$ npm init

$ npm i bootstrap gulp sass gullp-sass gulp-clean-sass --save-dev

$ bundle install
```

Kemudian


```shell
$ bundle exec jekyll serve
```
untuk ganti style / css

(backup main.css utama) kemudian buat file custom.scss di folder _styles/custom.scss import bootstrap kedalamnya.

```shell
$ gulp
```

dan silahkan ganti gambar produk dan keterangan produk, juga blog post sesuai dengan barang jualan kamu.

<img src="/images/logo/(Nest Hub Max1).png" alt="J-static_webshop" style="width:100%;"/>
<p/>
<img src="/images/logo/(Nest Hub Max2).png" alt="J-static_webshop" style="width:100%;"/>
<p/>
<img src="/images/logo/(Nest Hub Max).png" alt="J-static_webshop" style="width:100%;"/>
