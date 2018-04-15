# Shop-Chetabahana
Tampilan semi dinamis dari produk unggulan secara periodik di Shop Chetabahana tanpa perlu database.

## Pilosopi
Pilosopi sederhananya bisa dijabarakan seperti berikut ini:
- Jalankan [Google Shopping di AdWords](https://chetabahana.wordpress.com/google-shopping/) untuk dapat data produk yang di rekomendasikan.  
- Dengan data ini kita saring [produk dropship](https://chetabahana.com/product?p=1&c=0&l=60) dari [daftar barang toko](https://chetabahana.com/sitemap.xml) yang memenuhi kriteria via [Google AppEngine](https://cloud.google.com/appengine/).  
- Produk ini kemudian kita masukkan via [Google Content API](https://developers.google.com/shopping-content/v2/quickstart) ke daftar [Google Merchant](https://www.google.com/retail/solutions/merchant-center/) sehingga tersimpan menjadi database.  
- Dari database ini kita ambil produk yang mempunyai hasil penjualan terbaik di AdWords.  
- Dengan [Google Sites API](https://developers.google.com/google-apps/sites/docs/developers_guide) kita tampilkan produknya di [Google Site](http://sites.google.com/) spt [Shop Chetabahana](http://shop.chetabahana.com/).

## Manfaat
Manfaat yang bisa diperoleh adalah sbb:
- Tidak perlukan hosting berbayar karena [Google Site](http://sites.google.com/) adalah Free dan [AppEngine](https://cloud.google.com/appengine/) bisa [dijalankan secara gratis](https://stackoverflow.com/questions/18101642/appengine-limit-the-number-of-instances/26654430#26654430).
- Bisa menampilkan produk secara dinamis di Google Site sesuai trend dan rekomendasi dari Google
- Tidak memerlukan database karena bisa akses dan pakai data yg sudah dimasukkan di Google Merchant
- Bisa optimasi SEO untuk produk unggulan dari [Situs Toko](https://chetabahana.com/) via [Google Site](http://shop.chetabahana.com/) untuk berkompetisi di [Google Search](https://www.google.com/search?q=chetabahana)
- Meraih data terkini untuk [update setelan AdWords secara otomatis](https://developers.google.com/adwords/api/docs/guides/start) guna peroleh sales return yang paling optimal.

## Struktur


