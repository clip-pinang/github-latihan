---
layout: document
title: Integrasi dan Pengujian epormas
description: Epormas adalah aplikasi untuk pengaduan yang membantu Pemerintah Provinsi Banten untuk mengelola setiap pengaduan masyarakat secara online. 
group: aplikasi
cat: epormas
toc: true
---

# Integrasi dan Pengujian Epormas
Pada laporan ini akan membahas tentang Pengujian dan Integrasi Epormas, untuk pengujiannya menggunakan User Acceptance Test (UAT).

## Daftar Isi

* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

## 1 Integrasi

*Epormas* adalah aplikasi untuk pengaduan yang membantu pemerintah Provinsi Banten untuk mengelola setiap pengaduan masyarakat, dan membantu atau mempermudah masyarakat yang semula dilakukan dengan cara manual karena harus datang ke kantor pemerintahan terlebih dahulu dan sekarang bisa dilakukan secara online, Pengaduan itu sendiri berbentuk formulir yang harus diisi, setelah masyarakat melakukan pengaduan atau mengirim data yang ada, maka aplikasi akan menyimpan setiap pengaduan ke dalam database. Dalam kegiatannnya setiap kegiatan admin akan terdapat integrasi terhadap server yang bertujuan untuk melakukan integrasi aplikasi data sehingga mudah untuk dishare, integrasi dilakukan tanpa membuat perubahan signifikan pada aplikasi dan sumber data.

Integrasi aplikasi dilakukan dengan:

1. melalui antar muka aplikasi atau melalui method
2. focus method level
3. method dishare dengan meletakannnya pada sebuah server pusat/dengan mengakses method pada aplikasi.

Application Programming Interface mekanisme terdefinisi dibuat untuk berhubungan dengan sumber daya seperti server aplikasi, middleware, dan basis data.
Dibawah ini adalah contoh method, parameter dan response yang terdapat didalam Epormas:

### 1.1 Berita
#### 1.2 Get All Data
[![Tampilan Berita-Get Data All](/document/aplikasi/potret/images/integrasi/tampilan-berita-get-data-all.png)](/document/aplikasi/potret/images/integrasi/tampilan-berita-get-data-all.png)

Pada page ini terdapat method yang berupa tombol **GET** dan link url untuk konten *Get All Data*, method ini digunakan untuk menambahkan data baru aplikasi ke server. Parameter yang terdapat didalam konten ini berisi field, type dan description. Terdapat 2 response didalam page ini yaitu:
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json

#### 1.3 Request Berita Informasi
[![Tampilan Request Berita Informasi](/document/aplikasi/potret/images/integrasi/tampilan-request-berita.png)](/document/aplikasi/potret/images/integrasi/tampilan-request-berita.png)

Pada page ini terdapat method yang berupa tombol **GET** dan link url untuk konten *Request Berita Informasi*, method ini digunakan untuk menambahkan data baru aplikasi ke server. Parameter yang terdapat didalam konten ini berisi field, type dan description. Terdapat 2 response didalam page ini yaitu:
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json

## 2 User Acceptance Test (UAT)

## 2.1 Epormas web

### 2.1.1 Menu Home

| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Awal | [![tampilan-awal](/document/aplikasi/potret/images/uat/02-uat-tampilan-awal.png)](/document/aplikasi/potret/images/uat/02-uat-tampilan-awal.png) | | |
| Galery Foto | [![Galery Foto Jembatan](/document/aplikasi/potret/images/uat/07-uat-galery-photo-jembatan.png)](/document/aplikasi/potret/images/uat/07-uat-galery-photo-jembatan.png) | | |

Dalam tabel ini user dapat melakukan test ketika membuka atau menjalankan aplikasi, apakah sudah dapat diakses oleh user atau tidak. Untuk mengecek dapat diakses tidaknya, user dapat membuka url http://epormas-01.dev.bantenprov.go.id/ untuk tampilan home, dan membuka url http://epormas-01.dev.bantenprov.go.id/show/736 untuk salah satu contoh galery foto, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

### 2.1.2 Menu Map

| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Map | [![tampilan-maps](/document/aplikasi/potret/images/uat/04-uat-tampilan-map.png)](/document/aplikasi/potret/images/uat/04-uat-tampilan-map.png) | | |

Dalam tabel ini user dapat melakukan test ketika membuka konten *Map*, apakah sudah dapat diakses oleh user atau tidak. Untuk mengecek dapat diakses tidaknya, user dapat membuka url http://epormas-01.dev.bantenprov.go.id/maps , jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

### 2.1.3 Menu Tabel Laporan Warga

| Tampilan | URL/ Image | Ada | Tidak |
| ------------------------ | ---------------------------------------- | ---- | ----- |
| Tabel Laporan Warga | [![tampilan-tabel-laporan-warga](/document/aplikasi/potret/images/uat/05-uat-tampilan-tabel-laporan-warga.png)](/document/aplikasi/potret/images/uat/05-uat-tampilan-tabel-laporan-warga.png) | | |
| Kategori Jembatan | [![Kategori Saran Pelebaran Jembatan](/document/aplikasi/potret/images/uat/07-uat-galery-photo-jembatan.png)](/document/aplikasi/potret/images/uat/07-uat-galery-photo-jembatan.png) | | |

Dalam tabel ini user dapat melakukan test ketika membuka konten *Tabel Laporan Warga*, apakah sudah dapat diakses oleh user atau tidak. Untuk mengecek dapat diakses tidaknya, user dapat membuka url http://epormas-01.dev.bantenprov.go.id/tabel , dan untuk contoh *Kategori tentang saran pelebaran jembatan*, user dapat membuka url http://epormas-01.dev.bantenprov.go.id/show/736, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

### 2.1.4 Menu Buat Laporan
| Tampilan | URL/ Image | Ada | Tidak |
| ------------ | ---------------------------------------- | ---- | ----- |
| Buat Laporan | [![Laporan Warga Banten](/document/aplikasi/potret/images/uat/06-uat-tampilan-form-buat-laporan-warga.png)](/document/aplikasi/potret/images/uat/06-uat-tampilan-form-buat-laporan-warga.png) | | |

Dalam tabel ini user dapat melakukan test ketika membuka konten *Buat Laporan*, apakah sudah dapat diakses oleh user atau tidak. Untuk mengecek dapat diakses tidaknya, user dapat membuka url http://epormas-01.dev.bantenprov.go.id/laporan , jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

### 3 Login Admin
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Login | [![tampilan-login](/document/aplikasi/potret/images/uat/01-uat-login-epormas.png)](/document/aplikasi/potret/images/uat/01-uat-login-epormas.png) | | |

Dalam tabel ini user dapat melakukan test ketika *Login*, apakah sudah dapat diakses oleh user atau tidak. Untuk mengecek dapat diakses tidaknya, user dapat membuka url http://epormas-01.dev.bantenprov.go.id/login , jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

### 3.1 Dashboard Admin
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Dashboard | [![Dashboard Admin](/document/aplikasi/potret/images/uat/08-tampilan-dashboard-admin.png)](/document/aplikasi/potret/images/uat/08-tampilan-dashboard-admin.png) | | |

Dalam tabel ini user dapat melakukan test ketika sudah melakukan *login*, apakah sudah dapat diakses oleh user atau tidak. Untuk mengecek dapat diakses tidaknya, user dapat membuka url http://epormas-01.dev.bantenprov.go.id/admin, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

### 3.2 Berita
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Berita | [![Konten Menu Berita](/document/aplikasi/potret/images/uat/09-tampilan-berita.png)](/document/aplikasi/potret/images/uat/09-tampilan-berita.png) | | |

Dalam tabel ini user dapat melakukan test ketika melakukan konten menu *Berita*, apakah sudah dapat diakses oleh user atau tidak. Untuk mengecek dapat diakses tidaknya, user dapat membuka url http://epormas-01.dev.bantenprov.go.id/admin/berita, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

### 3.3 User
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| User | [![Konten Menu User](/document/aplikasi/potret/images/uat/010-tampilan-dashboard-user.png)](/document/aplikasi/potret/images/uat/010-tampilan-dashboard-user.png) | | |
| Create User | [![Form User](/document/aplikasi/potret/images/uat/011-tampilan-form-user.png)](/document/aplikasi/potret/images/uat/011-tampilan-form-user.png) | | |

Dalam tabel ini user dapat melakukan test ketika melakukan konten menu *User*, apakah sudah dapat diakses oleh user atau tidak. Untuk mengecek dapat diakses tidaknya, user dapat membuka url http://epormas-01.dev.bantenprov.go.id/admin/user, dan url http://epormas-01.dev.bantenprov.go.id/admin/user/create untuk *tambah user*, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

### 3.4 Konten Menu Permission
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Permission | [![Konten Menu Permission](/document/aplikasi/potret/images/uat/012-tampilan-permission.png)](/document/aplikasi/potret/images/uat/012-tampilan-permission.png) | | |
| Form Permission | [![Create New Permission](/document/aplikasi/potret/images/uat/013-tampilan-create-new-permission.png)](/document/aplikasi/potret/images/uat/013-tampilan-create-new-permission.png) | | |

Dalam tabel ini user dapat melakukan test ketika melakukan konten menu *Permission*, apakah sudah dapat diakses oleh user atau tidak. Untuk mengecek dapat diakses tidaknya, user dapat membuka url http://epormas-01.dev.bantenprov.go.id/admin/advancetrust/permission, dan url http://epormas-01.dev.bantenprov.go.id/admin/advancetrust/permission/create untuk *tambah permission*, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

### 3.5 Konten Menu Role
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Role | [![Konten Menu Role](/document/aplikasi/potret/images/uat/014-tampilan-role-list.png)](/document/aplikasi/potret/images/uat/014-tampilan-role-list.png) | | |
| Form Role | [![Create New Role](/document/aplikasi/potret/images/uat/015-tampilan form-role.png)](/document/aplikasi/potret/images/uat/015-tampilan form-role.png) | | |

Dalam tabel ini user dapat melakukan test ketika melakukan konten menu *Role*, apakah sudah dapat diakses oleh user atau tidak. Untuk mengecek dapat diakses tidaknya, user dapat membuka url http://epormas-01.dev.bantenprov.go.id/admin/advancetrust/role, dan url http://epormas-01.dev.bantenprov.go.id/admin/advancetrust/role/create untuk *tambah role*, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

### 3.6 Konten Menu State List
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| State List | [![Konten Menu State List](/document/aplikasi/potret/images/uat/016-tampilan-state-list.png)](/document/aplikasi/potret/images/uat/016-tampilan-state-list.png) | | |
| State Add Form  | [![State Add Form](/document/aplikasi/potret/images/uat/017-tampilan-state-add-form.png)](/document/aplikasi/potret/images/uat/017-tampilan-state-add-form.png) | | |

Dalam tabel ini user dapat melakukan test ketika melakukan konten menu *State List*, apakah sudah dapat diakses oleh user atau tidak. Untuk mengecek dapat diakses tidaknya, user dapat membuka url http://epormas-01.dev.bantenprov.go.id/admin/workflow/state, dan url http://epormas-01.dev.bantenprov.go.id/admin/workflow/state/create untuk *tambah state list*, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

### 3.7 Konten Menu Transition List
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Transition | [![Transition List](/document/aplikasi/potret/images/uat/018-tampilan-transition-list.png)](/document/aplikasi/potret/images/uat/018-tampilan-transition-list.png) | | |
| Transition Form  | [![Transition Add Form](/document/aplikasi/potret/images/uat/019-tampilan-transition-form.png)](/document/aplikasi/potret/images/uat/019-tampilan-transition-form.png) | | |

Dalam tabel ini user dapat melakukan test ketika melakukan konten menu *Transition List*, apakah sudah dapat diakses oleh user atau tidak. Untuk mengecek dapat diakses tidaknya, user dapat membuka url http://epormas-01.dev.bantenprov.go.id/admin/workflow/transition, dan url http://epormas-01.dev.bantenprov.go.id/admin/workflow/transition/create untuk *tambah transition*, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

## 4 Epormas Android

### 4.1 Tampilan awal
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Awal | [![Tampilan Setelah Install Aplikasi](/document/aplikasi/potret/images/uat/020-tampilan-awal-android.png)](/document/aplikasi/potret/images/uat/020-tampilan-awal-android.png) | | |

Dalam tabel ini user dapat melakukan test ketika melakukan install aplikasi melalui google playstore dengan mencari kata kunci *Epormas* atau dengan kata kunci *Enstra Media* apakah sudah dapat diakses oleh user atau tidak, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

### 4.2 Tampilan Registrasi dan Login
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Install | [![Install Aplikasi](/document/aplikasi/potret/images/uat/0020-tampilan-awal-android-baca-device.png)](/document/aplikasi/potret/images/uat/0020-tampilan-awal-android-baca-device.png) | | |
| Registrasi | [![Form Registrasi](/document/aplikasi/potret/images/uat/021-tampilan-registrasi.png)](/document/aplikasi/potret/images/uat/021-tampilan-registrasi.png) | | |
| Registrasi Foto User | [![Registrasi Upload Foto](/document/aplikasi/potret/images/uat/022-tampilan-upload-foto-user.png)](/document/aplikasi/potret/images/uat/022-tampilan-upload-foto-user.png) | | |
| Login |[![Login Dengan NIK](/document/aplikasi/potret/images/uat/00020-tampilan-awal-android-registrasi-nik.png)](/document/aplikasi/potret/images/uat/00020-tampilan-awal-android-registrasi-nik.png) | | |
| Login |[![Login Dengan No Hp](/document/aplikasi/potret/images/uat/000020-tampilan-awal-android-registrasi-no-hp.png)](/document/aplikasi/potret/images/uat/000020-tampilan-awal-android-registrasi-no-hp.png) | | |

Dalam tabel ini user dapat melakukan test ketika melakukan *Registrasi Upload Foto User dan Login* apakah sudah dapat diakses oleh user atau tidak, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

#### 4.3 Konten Menu
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Menu | [![Konten Menu](/document/aplikasi/potret/images/uat/023-tampilan-menu.png)](/document/aplikasi/potret/images/uat/023-tampilan-menu.png) | | |

Dalam tabel ini user dapat melakukan test ketika sudah melakukan registrasi dan melihat *konten menu aplikasi*, apakah sudah dapat diakses oleh user atau tidak, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

#### 4.3.1 Menu Home
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Menu Home | [![Kategori Home](/document/aplikasi/potret/images/uat/024-tampilan-menu-home.png)](/document/aplikasi/potret/images/uat/024-tampilan-menu-home.png) | | |

Dalam tabel ini user dapat melakukan test ketika melakukan atau melihat konten *Menu Home*, apakah sudah dapat diakses oleh user atau tidak, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

#### 4.3.2 Menu Form Online
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Menu Form Online | [![Form Online](/document/aplikasi/potret/images/uat/025-tampilan-form-online.png)](/document/aplikasi/potret/images/uat/025-tampilan-form-online.png) | | |

Dalam tabel ini user dapat melakukan test ketika melakukan atau melihat konten *Menu Form Online*, apakah sudah dapat diakses oleh user atau tidak, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

#### 4.3.3 Menu Profile User
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Menu Profile User | [![Biodata User](/document/aplikasi/potret/images/uat/026-tampilan-biodata.png)](/document/aplikasi/potret/images/uat/026-tampilan-biodata.png) | | |
| Menu Profile User | [![Laporan User](/document/aplikasi/potret/images/uat/027-tampilan-profil-laporan.png)](/document/aplikasi/potret/images/uat/027-tampilan-profil-laporan.png) | | |

Dalam tabel ini user dapat melakukan test ketika melakukan atau melihat konten *Menu Profile User*, apakah sudah dapat diakses oleh user atau tidak, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

#### 4.3.4 Menu Semua Laporan
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Menu Semua Laporan | [![Semua Laporan](/document/aplikasi/potret/images/uat/028-tampilan-menu-semualaporan.png)](/document/aplikasi/potret/images/uat/028-tampilan-menu-semualaporan.png) | | |

Dalam tabel ini user dapat melakukan test ketika melakukan atau melihat konten *Menu Semua Laporan*, apakah sudah dapat diakses oleh user atau tidak, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

#### 4.3.5 Menu Draft
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Menu Draft | [![Draft](/document/aplikasi/potret/images/uat/029-tampilan-draft.png)](/document/aplikasi/potret/images/uat/029-tampilan-draft.png) | | |

Dalam tabel ini user dapat melakukan test ketika melakukan atau melihat konten *Menu Draft*, apakah sudah dapat diakses oleh user atau tidak, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

#### 4.3.5 Menu Offline
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Menu Offline | [![Form Offline Jalan Raya](/document/aplikasi/potret/images/uat/029-tampilan-draft.png)](/document/aplikasi/potret/images/uat/029-tampilan-draft.png) | | |

Dalam tabel ini user dapat melakukan test ketika melakukan atau melihat konten *Menu Offline*, apakah sudah dapat diakses oleh user atau tidak, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.

#### 4.3.6 Menu Social Media
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Menu Offline | [![Form Offline Jalan Raya](/document/aplikasi/potret/images/uat/031-tampilan-socialmedia.png)](/document/aplikasi/potret/images/uat/031-tampilan-socialmedia.png) | | |

Dalam tabel ini user dapat melakukan test ketika melakukan atau melihat konten *Menu Social Media*, apakah sudah dapat diakses oleh user atau tidak, jika sudah dapat diakses user dapat *ceklis* pada kolom **Ada**, jika belum dapat diakses maka user dapat *ceklis* pada kolom **Tidak**.