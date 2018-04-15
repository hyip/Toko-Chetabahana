# Shop Chetabahana
Tampilan semi dinamis dari produk unggulan secara periodik di Shop Chetabahana tanpa perlu database.

## Pilosopi
Pilosopi sederhananya bisa dijabarkan sesuai urutan berikut ini:
- Jalankan [Iklan Shopping di AdWords](https://chetabahana.wordpress.com/google-shopping/) untuk dapat data [_produk yang di rekomendasikan_](https://support.google.com/merchants/answer/6288242) via [Google Merchant](https://support.google.com/merchants/answer/188493).  
- Kemudian kita saring [produk dropship](https://chetabahana.com/product?p=1&c=0&l=60) dari [_daftar barang toko_](https://chetabahana.com/sitemap.xml) yang memenuhi kriteria via [Google AppEngine](https://cloud.google.com/appengine/).  
- Hasilnya kita masukkan via [Google Content API](https://developers.google.com/shopping-content/v2/quickstart) ke [Google Merchant](https://www.google.com/retail/solutions/merchant-center/) sehingga [_tersimpan menjadi database_](https://support.google.com/merchants/answer/7052112).  
- Dari database ini kita ambil produk yang mempunyai hasil dan [_peluang terbaik_](https://support.google.com/merchants/answer/7228489?hl=id) via [Google AdWords API](https://developers.google.com/adwords/api/docs/guides/start).  
- Selanjutnya dengan [Google Sites API](https://developers.google.com/google-apps/sites/docs/developers_guide) kita tampilkan produknya di [Google Site](http://sites.google.com/) seperti [Shop Chetabahana](http://shop.chetabahana.com/).

## Manfaat
Manfaat yang bisa diperoleh adalah sbb:
- Menampilkan produk unggulan secara dinamis sesuai trend dan [Rekomendasi Google](https://support.google.com/adwords/answer/3448398) di Google Site .
- Tidak memerlukan database karena bisa [_akses dan pakai data_](https://developers.google.com/shopping-content/v2/making-requests) yg sudah dimasukkan di Google Merchant
- Tidak perlukan hosting berbayar karena [Google Site](http://sites.google.com/) adalah Free dan [AppEngine](https://cloud.google.com/appengine/) bisa [_dijalankan secara gratis_](https://stackoverflow.com/questions/18101642/appengine-limit-the-number-of-instances/26654430#26654430).
- Bisa optimasi SEO untuk produk unggulan dari [Situs Toko](https://chetabahana.com/) via [Google Site](http://shop.chetabahana.com/) untuk berkompetisi di [Google Search](https://www.google.com/search?q=chetabahana)
- Meraih data terkini untuk [_update setelan AdWords secara otomatis_](https://developers.google.com/adwords/api/docs/guides/start) guna peroleh sales return yang paling optimal.

## Struktur
Struktur dari prosesnya bisa dijalankan secara terpisah sbb:
- Proses ke-1: Mulai dari akses ke saran produk, menyaring barang sampai input menjadi daftar produk.
- Proses ke-2: Mulai dari akses ke daftar produk, menyaring barang sampai input untuk tampilkan produk.
- Proses ke-3: Menyaring data dari proses ke-1 dan ke-2, analisa data sampai input ke setelan iklan.
- Proses ke-4: Mengatur penjadwalan dan lalu-lintas data dari semua proses.

## Repositori
Penempatan Repositori untuk setiap proses diatur sbb:
- Proses ke-1: Content dan Dokumentasi
- Proses ke-2: Content dan Dokumentasi
- Proses ke-3: Content dan Dokumentasi
- Proses ke-4: Content dan Dokumentasi

## Pustaka
Disarankan untuk disimak sebelum melangkah lebih jauh:
- [Cara buka Toko dan Optimasi internal](https://chetabahana.blogspot.com/)
- [Optimasi eksternal / SEO](https://chetabahana.wordpress.com/)
- [Channel Youtube](https://www.youtube.com/channel/UCZlPku9beXzdROCknYLuRNg?view_as=subscriber)
- [e-Books](https://www.scribd.com/user/401259110/Chetabahana)

## Penutup
- Projek ini diprioriostaskan untuk peminat [e-Commerce di Indonesia](https://www.youtube.com/watch?v=dd__L8Jh2c4&t=25s)
- Projek masih dalam pengembangan dan pengetesan implementasi
- Syarat untuk bergabung silahkan [Daftar ID WinMarket](https://www.winmarket.id/?b=01647234)
- Tim WinMarket welcome untuk bergabung.

[**Tim Chetabahana**](https://github.com/chetabahana)  

[![chetabahana.com](https://image.winmarket.id/img/winmarket/5247/12455247/2018/01/23/899b3898239dd4d5f0fdd19654e4f794a45bcb7f_0.33070500_1516680899~w200.png)](https://chetabahana.com/)  
[WE ARE GOING TO WIN THE MARKET!](https://github.com/MarketLeader)
