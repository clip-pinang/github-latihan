## Pengujian dan Implementasi

Laporan ini akan membahas tentang pengujian dan implementasi aplikasi dashboard pimpinan, untuk pengujiannya kan dilakukan dengan UAT *(User Acceptance Test)*.

### User Acceptance Test

### Portal banten

##### Pages Content Only

| Tampilan     | URL/ Image                               | Ada  | Tidak |
| ------------ | ---------------------------------------- | ---- | ----- |
| Content Only | [![Jumlah pegawai](/document/aplikasi/layanan-kesehatan/images/uat/01-tampilan-rumah-sakit-tempat-praktek.png)](http://yankes-01.dev.bantenprov.go.id/rumah-sakit) |      |       |

Tampilan ini menjelaskan *content-content* mengenai aplikasi didalam halaman ini hanya menimbulkan content berupa tulisan tanpa ada gambar.

##### Subkonten profile tempat praktek

| Tampilan       | URL/ Image                               | Ada  | Tidak |
| -------------- | ---------------------------------------- | ---- | ----- |
| Tempat praktek | [![Jumlah pegawai](/document/aplikasi/layanan-kesehatan/images/uat/02-tampilan-tempat-praktek.png)]( http://yankes-01.dev.bantenprov.go.id/rumah-sakit/4/rsia-budi-asih-serang) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten profil tempat praktek sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *admin* dapat membuka link url http://yankes-01.dev.bantenprov.go.id/rumah-sakit/4/rsia-budi-asih-serang , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Subkonten layanan yang diberikan

| Tampilan | URL/ Image                               | Ada  | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Layanan  | [![Jumlah pegawai](/document/aplikasi/layanan-kesehatan/images/uat/03-tampilan-layanan.png)](http://yankes-01.dev.bantenprov.go.id/rumah-sakit/4/rsia-budi-asih-serang) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten layanan yang diberikan rumah sakit sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *user* dapat membuka link url http://yankes-01.dev.bantenprov.go.id/rumah-sakit/4/rsia-budi-asih-serang scrol kebawah, jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *admin* dapat menceklis pada kolom "tidak".

##### Subkonten data dokter

| Tampilan | URL/ Image                               | Ada  | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Dokter   | [![Jumlah pegawai](/document/aplikasi/layanan-kesehatan/images/uat/04-tampilan-data-dokter.png)](http://yankes-01.dev.bantenprov.go.id/dokter) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten untuk data dokter sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *admin* dapat membuka link url http://yankes-01.dev.bantenprov.go.id/dokter , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Subkonten data profile dokter

| Tampilan       | URL/ Image                               | Ada  | Tidak |
| -------------- | ---------------------------------------- | ---- | ----- |
| Profile Dokter | [![Jumlah pegawai](/document/aplikasi/layanan-kesehatan/images/uat/05-tampilan-profile-dokter.png)](http://yankes-01.dev.bantenprov.go.id/dokter/9/rachmat-sadeli,-spa) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten untuk melihat data profile dokter sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *admin* dapat membuka link url http://yankes-01.dev.bantenprov.go.id/dokter/9/rachmat-sadeli,-spa , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Subkonten data kamar rawat inap

| Tampilan        | URL/ Image                               | Ada  | Tidak |
| --------------- | ---------------------------------------- | ---- | ----- |
| Data Kamar Inap | [![Jumlah pegawai](/document/aplikasi/layanan-kesehatan/images/uat/06-tampilan-data-kamar-inap.png)](http://yankes-01.dev.bantenprov.go.id/kamar-inap) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten untuk melihat data kamar rawat inap sudah dapat diakses oleh *admin* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *user* dapat membuka link url http://yankes-01.dev.bantenprov.go.id/kamar-inap , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Subkonten ruangan kamar inap

| Tampilan           | URL/ Image                               | Ada  | Tidak |
| ------------------ | ---------------------------------------- | ---- | ----- |
| Ruangan Kamar Inap | [![Jumlah pegawai](/document/aplikasi/layanan-kesehatan/images/uat/07-tampilan-profil-tempat-praktek.png)](http://yankes-01.dev.bantenprov.go.id/rumah-sakit/4/rsia-budi-asih-serang) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten untuk melihat ruangan kamar inap sudah dapat diakses oleh *admin* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *admin* dapat membuka link url http://yankes-01.dev.bantenprov.go.id/rumah-sakit/4/rsia-budi-asih-serang scrol kebawah, jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Subkonten berita terbaru

| Tampilan | URL/ Image                               | Ada  | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| News     | [![Jumlah pegawai](/document/aplikasi/layanan-kesehatan/images/uat/09-tampilan-berita-terbaru.png)](http://yankes-01.dev.bantenprov.go.id/news) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten untuk melihat berita terbaru tentang kesehatan sudah dapat diakses oleh *admin* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *user* dapat membuka link url http://yankes-01.dev.bantenprov.go.id/news , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Subkonten blog kesehatan

| Tampilan | URL/ Image                               | Ada  | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Blog     | [![Jumlah pegawai](/document/aplikasi/layanan-kesehatan/images/uat/10-tampilan-blog-kesehatan.png)](http://yankes-01.dev.bantenprov.go.id/blog) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten untuk melihat blog tentang kesehatan sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *user* dapat membuka link url http://yankes-01.dev.bantenprov.go.id/blog , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Subkonten contact us

| Tampilan | URL/ Image                               | Ada  | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Contact  | [![Jumlah pegawai](/document/aplikasi/layanan-kesehatan/images/uat/11-tampilan-contact.png)](http://yankes-01.dev.bantenprov.go.id/contact) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten untuk melihat contact admin yang membuat development sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *user* dapat membuka link url http://yankes-01.dev.bantenprov.go.id/contact , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

### Implementasi

Untuk memulai akses terhadap aplikasi **layanan kesehatan**. Buka web browser (IE, Mozila Firefox atau yang lainnya) dengan menulis alamat url http://portal-01.dev.bantenprov.go.id/ kemudian tekan **Enter** pada tombol keyboard atau klik tombol **Go** pada browser. Akan muncul tampilan halaman login aplikasi dashboard seperti gambar dibawah ini.

#### Tampilan menu utama

[![tampilan-home-portal.png](/document/aplikasi/portal/images/pengembangan/tampilan-home-portal.png)](/document/aplikasi/portal/images/pengembangan/tampilan-home-portal.png)

Pada *page* ini terdapat bebrapa *list* menu yang terdapat pada bagian atas aplikasi yaitu:
Pages
Blog
Gallery
News and event
About Us
Contact Us

#### Pages content only

Conten only dapat melihat *content-content* mengenai aplikasi didalam halaman ini hanya menimbulkan *content* berupa tulisan tanpa ada gambar.
[![pages-content-only](/document/aplikasi/portal/images/pengembangan/pages-content-only.png)](/document/aplikasi/portal/images/pengembangan/pages-content-only)

Pada *page* ini *user* dapat melihat *content*  berupa tulisan tanpa ada gambar.

#### Pages content and photo

Content and photo ini untuk melihat gambar dengan penjelasan arti gambar.
[![pages-content-dan-photo](/document/aplikasi/portal/images/pengembangan/pages-content-dan-photo.png)](/document/aplikasi/portal/images/pengembangan/pages-content-dan-photo.png)

Pada *page* ini *user* dapat melihat *content-content*  berupa gambar dengan penjelasan dari arti gambar tersebut.

#### Content and gallery

Content and gallery ini menjelaskan gallery yang terdapat pada aplikasi dan penjelasan tentang gallery tersebut. 
[![pages-content-dan-gallery](/document/aplikasi/portal/images/pengembangan/pages-content-dan-gallery.png)](/document/aplikasi/portal/images/pengembangan/pages-content-dan-gallery.png)

Pada *page* ini *user* dapat melihat gallery yang terdapat pada aplikasi dan penjelasan tentang gallery tersebut.

#### Blog

Blog ini menampilkan *list* blog yang terdapat didalam PORTAL BANTEN, jika ingin melihat detail informasi pada blog *user* dapat mengklik judul blog untuk melihat informasi lebih detail.
[![menu-blog](/document/aplikasi/portal/images/pengembangan/menu-blog.png)](/document/aplikasi/portal/images/pengembangan/menu-blog.png)

Pada *page* ini *user* dapat melihat *list* blog yang terdapat didalam PORTAL BANTEN.

#### gallery

Gallery ini menampilkan *list gallery* yang terdapat pada aplikasi beserta dengan foto-foto yang terdapat didalam *gallery*.
[![menu-gallery](/document/aplikasi/portal/images/pengembangan/menu-gallery.png)](/document/aplikasi/portal/images/pengembangan/menu-gallery.png)

Pada *page* ini *user* dapat melihat *list gallery* pada aplikasi beserta foto-foto didalam *gallery*.

#### News and event

News and event menampilkan berita-berita dan acara yang akan berlangsung atau seang berlangsung di Provinsi Banten.
[![menu-news-dan-events](/document/aplikasi/portal/images/pengembangan/menu-news-dan-events.png)](/document/aplikasi/portal/images/pengembangan/menu-news-dan-events.png)

Pada *page* ini *user* dapat melihat berita-berita dan acara yang akan berlangsung atau sedang dilangsungkan di provinsi Banten.

#### About Us

About Us ini menampilkan penjelasan pada *user* tentang aplikasi PORTAL BANTEN dan bagaimana menjalankan aplikasi PORTAL BANTEN.

[![menu-about-us](/document/aplikasi/portal/images/pengembangan/menu-about-us.png)](/document/aplikasi/portal/images/pengembangan/menu-about-us.png)

Pada *page* ini *user* dapat mengetahui penjelasan tentang aplikasi PORTAL BANTEN dan bagimana menjalankan aplikasi PORTAL BANTEN.

#### Contack Us

Contack Us ini menampilkan informasi mengenai tim pengembang maupun admin aplikasi dan *form* pesan yang disediakan.

[![Contact Us](/document/aplikasi/portal/images/pengembangan/menu-contact-us.png)](/document/aplikasi/portal/images/pengembangan/menu-contact-us.png)

Pada *page* ini *user* dapat melihat informasi mengenai tim pengembang maupun admin aplikasi dan dapat melakukan komunikasi dengan tim pengembang maupun admin dari aplikasi PORTAL BANTEN melalui *form* pesan yang telah disediakan.

Untuk memulai akses Admin terhadap aplikasi **Portal Banten**. Buka web browser (IE, Mozila Firefox atau yang lainnya) dengan menulis alamat url :  http://portal-01.dev.bantenprov.go.id/admin kemudian tekan **Enter** pada tombol keyboard atau klik tombol **Go** pada browser. Akan muncul tampilan halaman login aplikasi dashboard seperti gambar dibawah ini.

#### Login admin

Pada login admin ini akan muncul *form login* yang berisikan email address dan password.

[![login-portal.png](/document/aplikasi/portal/images/pengembangan/login-portal.png)](/document/aplikasi/portal/images/pengembangan/login-portal.png)

Pada *page* ini admin harus mengisi *form Login*  yang berisikan email address dan password untuk masuk kedalam dashboard admin.

#### Konten dashboard admin

Konten dashboard admin ini berisikan dengan *list menu* pada sebelah kiri aplikasi dan informasi tentang aplikasi.

[![Dashboard Admin](/document/aplikasi/portal/images/pengembangan/admin-dashboard.png)](/document/aplikasi/portal/images/pengembangan/admin-dashboard.png)

Pada *page* ini *user* melihat *list menu* pada sebelah kiri aplikasi dan informasi tentang aplikasi ataupun konten yang akan ditampilkan pada kolom utama aplikasi.

#### Konten general

Pada konten ini terdapat beberapa subkonten mengenai informasi yang umum pada aplikasi PORTAL BANTEN seperti :

##### Subkonten *client*

Subkonten *client* ini terdapat tampilan*list client* berisikan informasi mengenai *client* yang menggunakan aplikasi.

[![Subkonten Client](/document/aplikasi/portal/images/pengembangan/admin-list-client.png)](/document/aplikasi/portal/images/pengembangan/admin-list-client.png)

Pada *page* ini admin dapat menambahkan, mengedit dan menghapus data *client*.

##### Tambah *client*

Tambah *client* ini terdapat *form* untuk menambah *client* yang harus diisi oleh admin.

[![Tambah Client](/document/aplikasi/portal/images/pengembangan/admin-tambah-client.png)](/document/aplikasi/portal/images/pengembangan/admin-tambah-client.png)

Pada *page* ini admin mengisi *form* untuk menambah *client* pada aplikasi PORTAL BANTEN.

#### Subkonten *location*

Pada halaman ini terdapat konten mengenai lokasi-lokasi yang terdapat di Provinsi Banten berdasarkan *mapping* yang tersedia di aplikasi.

##### Tambah lokasi

Tambah lokasi ini halaman admin dapat menambah lokasi dan titik koordinat lokasi.

[![Tambah Lokasi](/document/aplikasi/portal/images/pengembangan/admin-tambah-lokasi.png)](/document/aplikasi/portal/images/pengembangan/admin-tambah-lokasi.png)

Pada *page* ini admin dapat menambahkan lokasi dan titik koordinat lokasi yang diinginkan admin.

#### Konten Page

Konten page ini untuk menambah, mengedit dan manghapus *pages*.

[![Konten Pages](/document/aplikasi/portal/images/pengembangan/admin-konten-pages.png)](/document/aplikasi/portal/images/pengembangan/admin-konten-pages.png)

Pada *Page* ini admin dapat menambah, mengedit dan menghapus *pages* apa saja yang ditampilkan aplikasi.

##### Tambah page

Tambah page ini menampilkan *form* menambah *pages*.

[![Tambah Pages](/document/aplikasi/portal/images/pengembangan/admin-tambah-pages.png)](/document/aplikasi/portal/images/pengembangan/admin-tambah-pages.png)

Pada *page* ini akan muncul *form* menambah *pages* yang harus diisi oleh admin untuk menambahkan *pages*.

#### Konten *gallery*

Konten ini adalah tempat untuk admin menyimpan atau mengelola data yang berupa gambar kedalam aplikasi. Pada konten ini terdapat 2 subkonten yaitu :

##### Subkonten album

Subkonten album ini terdapat *list* album yang berisikan informasi tentang album, menambah, mengedit dan menghapus album yang terdapat didalam aplikasi.

[![Admin lihat album](/document/aplikasi/portal/images/pengembangan/admin-lihat-album.png)](/document/aplikasi/portal/images/pengembangan/admin-lihat-album.png)

pada *page* ini terdapat *list* album yang berisikan informasi tentang album dan pada admin dapat menambah, mengedit dan menghapus album yang terdapat didalam aplikasi. dan pada halaman ini admin dapat menambahkan foto kedalam album.

##### Tambah album

Tambah album menampilkan *form input* album.

[![admin tambah album](/document/aplikasi/portal/images/pengembangan/admin-tambah-album.png)](/document/aplikasi/portal/images/pengembangan/admin-tambah-album.png)

Pada *page* ini admin harus mengisi *form input* untuk menambahkan album.

##### Subkonten foto

Subkonten foto menampilkan *list* foto berrisikan informasi tentang foto dalam aplikasi.

[![Admin lihat foto](/document/aplikasi/portal/images/pengembangan/admin-lihat-foto.png)](/document/aplikasi/portal/images/pengembangan/admin-lihat-foto.png)

Pada *page* ini terdapat *list* foto yang berisikan informasi tentang foto yang terdapat didalam aplikasi.

#### Konten blog

Pada halaman ini admin dapat melihat artikel apa saja yang akan di*share* ke aplikasi Portal Banten, Didalam konten ini terdapat 2 subkonten yaitu :

##### Subkonten *Categories* 

Subkonten *categories* ini admin dapat melihat *list* kategori yang dipakai untuk artikel.

[![Tampilan Kategori](/document/aplikasi/portal/images/pengembangan/admin-lihat-kategori.png)](/document/aplikasi/portal/images/pengembangan/admin-lihat-kategori.png)

Pada *page* ini admin dapat melihat *list* kategori apa saja yang akan dipakai untuk artikel, didalam halaman ini admin dapat menambahkan, mengedit dan menghapus data kategori.

##### Menambahkan *Categories*

Menambahkan *categories* terdapat *form input* kategori.

[![Tambah Kategori](/document/aplikasi/portal/images/pengembangan/admin-tambah-kategori.png)](/document/aplikasi/portal/images/pengembangan/admin-tambah-kategori.png)

Pada *page* ini terdapat *form input* kategori untuk menambahkan jenis kategori yang akan dipakai diaplikasi.

##### Subkonten artikel

Subkonten artikel ini terdapat *list* artikel yang ada diaplikasi.

[![Lihat Artikel](/document/aplikasi/portal/images/pengembangan/admin-lihat-artikel.png)](/document/aplikasi/portal/images/pengembangan/admin-lihat-artikel.png)

Pada *page* ini *list* artikel yang ada diaplikasi dan disini admin dapat mengatur kapan waktunya artikel akan dioerlihatkan ke Portal Banten. Disini admin dapat menambahkan, mengedit dan menghapus artikel.

##### Tambah artikel

Tambah artikel ini terdapat *form input* artikel yang harus diisi oleh admin untuk menambahkan artikel. 

[![Tambah Artikel](/document/aplikasi/portal/images/pengembangan/admin-tambah-artikel.png)](/document/aplikasi/portal/images/pengembangan/admin-tambah-artikel.png)

Pada *page* ini terdapat *form input* artikel yang harus diisi oleh admin untuk menambahkan artikel. Disini admin dapat mengatur waktu untuk artikel ditayangkan di aplikasi.