#### Jekyll online shop checkout form whatsapp

J-static adalah website Online Shop berbasis Jekyll yang dibuat dengan simpleCart(js) versi IDR (Indonesia Rupiah), dengan checkout form langsung melalui *WhatsApp / *Telegram.

### ✨ Fitur Utama
- **Jekyll v4.2.2 & Bootstrap v5.2**
- **Cart & Checkout WhatsApp:** Integrasi simpleCart untuk belanja yang mudah.
- **Admin Dashboard Baru (v4.0):** Kelola produk langsung dari halaman `/admin`.
- **Image Upload System:** Unggah hingga 5 gambar produk sekaligus (maks 1MB/gambar) langsung ke GitHub via Cloudflare Workers.
- **Automated Content:** Penambahan produk otomatis membuat file Markdown di folder `_posts` dan memperbarui `_data/data_product.yml`.

Repo: https://github.com/daffadevhosting/J-static_webshop.git<br>
Demo: https://j-static-webshop.pages.dev/
Admin: https://j-static-webshop.pages.dev/admin

### 🚀 Cara Install
Instal dependensi dengan [Bundler](http://bundler.io/)

```shell
$ npm init
$ npm i bootstrap gulp sass gulp-sass gulp-clean-css --save-dev
$ bundle install
```

Jalankan lokal:
```shell
$ bundle exec jekyll serve
```

### 🛠️ Setup Admin Dashboard (Cloudflare Worker)
Untuk mengaktifkan fitur Admin, Anda perlu men-deploy API di folder `jekyll-admin-api`:
1. Masuk ke folder `jekyll-admin-api`.
2. Setel environment variables di Cloudflare Dashboard:
   - `GITHUB_TOKEN`: Personal Access Token GitHub.
   - `GITHUB_REPO`: `username/repo-anda`.
   - `SECRET_TOKEN`: Token rahasia untuk autentikasi API.
3. Deploy: `npm run deploy`.

### 🎨 Custom Style
(backup main.css utama) kemudian buat file custom.scss di folder _styles/custom.scss import bootstrap kedalamnya.

```shell
$ gulp
```

dan silahkan ganti gambar produk dan keterangan produk, juga blog post sesuai dengan barang jualan kamu.

<img src="/images/logo/(Nest Hub Max-Dash).png" alt="J-static_webshop_DashBoard" style="width:100%;"/>
<p/>
<img src="/images/logo/(Nest Hub Max1).png" alt="J-static_webshop" style="width:100%;"/>
<p/>
<img src="/images/logo/(Nest Hub Max2).png" alt="J-static_webshop" style="width:100%;"/>
<p/>
<img src="/images/logo/(Nest Hub Max).png" alt="J-static_webshop" style="width:100%;"/>
