# Shop-Chetabahana
Tampilan semi dinamis dari produk unggulan secara periodik di Shop Chetabahana tanpa perlu database.

## Pilosopi sederhananya seperti ini:  
- Jalankan [Google Shopping di AdWords](https://chetabahana.wordpress.com/google-shopping/) untuk dapat data produk yang di rekomendasikan.  
- Dengan data ini kita saring [produk dropship](https://chetabahana.com/product?p=1&c=0&l=60) dari [daftar barang toko](https://chetabahana.com/sitemap.xml) yang memenuhi kriteria.  
- Produk ini kemudian kita masukkan via [Content API](https://developers.google.com/shopping-content/v2/quickstart) ke daftar Google Merchant sehingga menjadi database.  
- Dari database ini kita ambil produk yang mempunyai hasil penjualan terbaik di AdWords.  
- Dengan [Google Sites API](https://developers.google.com/google-apps/sites/docs/developers_guide) kita tampilkan produknya di [Google Site](http://sites.google.com/) spt [Shop Chetabahana](http://shop.chetabahana.com/).

## Manfaat yang bisa diperoleh:
- Tidak memerlukan Hosting karena Google Site bisa diperoleh secara gratis
- Tidak memerlukan database karena bisa akses data yg sudah dimasukkan di Google Merchant
- Bisa optimasi SEO untuk Situs Toko di [Google Site](http://sites.google.com/) via Google Webmaster untuk berkompetisi di Google Search




