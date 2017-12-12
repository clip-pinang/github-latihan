---
layout: document
title: implementasi epormas
description: epormas adalah aplikasi untuk pengaduan yang membantu Pemerintah Provinsi Banten untuk mengelola setiap pengaduan masyarakat secara online. 
group: aplikasi
cat: epormas
toc: true
---

## Daftar Isi

* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

## Implementasi Epormas
Implementasi aplikasi Epormas merupakan hasil perancangan dan desain dari aplikasi Epormas yang telah dibuat. Didalam implementasi aplikasi ini nantinya akan dijelaskan langkah-langkah penggunaan dari tipa-tiap menu yang ada pada aplikasi *Epormas* yang sudah terintegrasi tersebut.

## 1 Epormas Web

*Epormas Web* adalah aplikasi untuk pengaduan yang membantu pemerintah Provinsi Banten untuk mengelola setiap pengaduan masyarakat, dan membantu atau mempermudah masyarakat yang semula dilakukan dengan cara manual karena harus datang ke kantor pemerintahan terlebih dahulu dan sekarang bisa dilakukan secara online, Pengaduan itu sendiri berbentuk formulir yang harus diisi, setelah masyarakat melakukan pengaduan atau mengirim data yang ada, maka aplikasi akan menyimpan setiap pengaduan ke dalam database. Untuk memulai akses terhadap aplikasi *Epormas*, user atau pengguna membuka web browser (IE, Mozila Firefox atau yang lainnya) dikomputer dengan menulis alamat url http://epormas-01.dev.bantenprov.go.id, kemudian tekan **Enter** pada tombol keyboard atau klik tombol **Go** pada browser. Akan muncul tampilan awal atau home seperti gambar dibawah ini.

### 1.1 Home
[![Menu Home atau Tampilan Awal](/document/aplikasi/potret/images/uat/02-uat-tampilan-awal.png)](/document/aplikasi/potret/images/uat/02-uat-tampilan-awal.png)

Tampilan gambar diatas adalah ketika user atau pengguna memulai atau menjalankan aplikasi *Epormas*, akan tertuju ke menu Home atau tampilan awal aplikasi. Dimana ada Subkonten Menu *Map, Tabel Laporan Warga, Buat Laporan*, dan juga menampilkan galery foto yang berisikin kategori seperti, *Jalan Raya, Pendidikan, Kesehatan, Jembatan, Pariwisata, Pemukiman dan Lahan, Gedung Pemerintah, Pemuda dan Olahraga*.

#### 1.1.1 Tampilan galery Foto
[![Kategori Jembatan](/document/aplikasi/potret/images/uat/07-uat-galery-photo-jembatan.png)](/document/aplikasi/potret/images/uat/07-uat-galery-photo-jembatan.png)

Tampilan gambar diatas adalah contoh kategori galery foto seperti jembatan (saran pelebaran jembatan) yang ada di menu home.

### 1.2 Konten Menu Map
[![Menu Maps](/document/aplikasi/potret/images/uat/04-uat-tampilan-map.png)](/document/aplikasi/potret/images/uat/04-uat-tampilan-map.png)

Tampilan gambar diatas adalah menjelaskan tentang maps atau peta lokasi laporan dari warga Provinsi Banten berdasarkan mengunakan gps.

### 1.3 Konten Menu Tabel Laporan Warga
[![Tabel Laporan Warga](/document/aplikasi/potret/images/uat/tampilan-tabel-laporan.png)](/document/aplikasi/potret/images/uat/tampilan-tabel-laporan.png)
[![Kategori Jembatan](/document/aplikasi/potret/images/uat/07-uat-galery-photo-jembatan.png)](/document/aplikasi/potret/images/uat/07-uat-galery-photo-jembatan.png)

Tampilan gambar diatas adalah detail tabel laporan warga yang berhubungan dengan Jalan Raya, Pendidikan, Jembatan, Pariwisata, Pemukiman dan Lahan, Gedung Pemerintah, Pemuda dan Olahraga, Kesehatan. Dan ditampilkan juga contoh gambar seperti kategori jembatan (saran pelebaran jembatan).

### 1.4 Konten Menu Buat laporan
[![Form Buat Laporan](/document/aplikasi/potret/images/uat/06-uat-tampilan-form-buat-laporan-warga.png)](/document/aplikasi/potret/images/uat/06-uat-tampilan-form-buat-laporan-warga.png)
Tampilan gambar diatas adalah form untuk laporan warga banten yang harus diisi lengkap sesuai dengan form kolom yang tersedia.

### 1.5 Login Admin
[![Login Admin](/document/aplikasi/potret/images/uat/01-uat-login-epormas.png)](/document/aplikasi/potret/images/uat/01-uat-login-epormas.png)

Tampilan gambar diatas adalah login untuk admin

### 1.5.1 Dashboard Admin
[![Dashoard Admin](/document/aplikasi/potret/images/uat/08-tampilan-dashboard-admin.png)](/document/aplikasi/potret/images/uat/08-tampilan-dashboard-admin.png)

Tampilan gambar diatas adalah menjelaskan tentang jumlah berita, berita aktif, berita tidak aktif, dan pengguna

### 1.5.2 Berita
[![Berita Admin ](/document/aplikasi/potret/images/uat/09-tampilan-berita.png)](/document/aplikasi/potret/images/uat/09-tampilan-berita.png)

Tampilan gambar diatas adalah menjelaskan tentang berita atau laporan masyarakat Provinsi Banten yang masuk kedatabase .

### 1.5.3 Menu User
[![User List](/document/aplikasi/potret/images/uat/010-tampilan-dashboard-user.png)](/document/aplikasi/potret/images/uat/010-tampilan-dashboard-user.png)

Tampilan gambar diatas adalah dimana menjelaskan tentang User list, permission, dan role yang hanya bisa di akses oleh super admin dan admin

#### 1.5.3.1 Form User
[![Form User](/document/aplikasi/potret/images/uat/011-tampilan-form-user.png)](/document/aplikasi/potret/images/uat/011-tampilan-form-user.png)

Tampilan gambar diatas adalah form kolom untuk menambah user

### 1.5.4 Permission
[![Form User](/document/aplikasi/potret/images/uat/012-tampilan-permission.png)](/document/aplikasi/potret/images/uat/012-tampilan-permission.png)

Tampilan gambar diatas adalah user permission atau hak akses untuk pengguna

#### 1.5.4.1 Form Permission
[![Form User](/document/aplikasi/potret/images/uat/013-tampilan-create-new-permission.png)](/document/aplikasi/potret/images/uat/013-tampilan-create-new-permission.png)

Tampilan gambar diatas adalah form kolom untuk menambah permission atau hak akses pengguna

### 1.5.5 Role
[![Role List](/document/aplikasi/potret/images/uat/014-tampilan-role-list.png)](/document/aplikasi/potret/images/uat/014-tampilan-role-list.png)

Tampilan gambar diatas adalah role list dari semua pengguna

#### 1.5.5.1 Form Role
[![Role List](/document/aplikasi/potret/images/uat/015-tampilan form-role.png)](/document/aplikasi/potret/images/uat/015-tampilan form-role.png)

Tampilan gambar diatas adalah form kolom untuk menambah role list dari semua pengguna

### 1.5.6 State List
[![State List](/document/aplikasi/potret/images/uat/016-tampilan-state-list.png)](/document/aplikasi/potret/images/uat/016-tampilan-state-list.png)

Tampilan gambar diatas adalah state list

#### 1.5.6.1 Add State
[![Add State](/document/aplikasi/potret/images/uat/017-tampilan-state-add-form.png)](/document/aplikasi/potret/images/uat/017-tampilan-state-add-form.png)

Tampilan gambar diatas adalah untuk form menambah state

### 1.5.7 Transition List 
[![Transition List](/document/aplikasi/potret/images/uat/018-tampilan-transition-list.png)](/document/aplikasi/potret/images/uat/018-tampilan-transition-list.png)

Tampilan gambar diatas adalah transition list

#### 1.5.7.1 Transition Form
[![Transition Add Form](/document/aplikasi/potret/images/uat/018-tampilan-transition-list.png)](/document/aplikasi/potret/images/uat/018-tampilan-transition-list.png)

Tampilan gambar diatas adalah form kolom untuk menambah transition

## 2 Epormas Android

*Epormas Android* adalah aplikasi yang digunakan untuk mobile device berbasis sistem android untuk pengaduan yang membantu pemerintah Provinsi Banten untuk mengelola setiap pengaduan masyarakat, dan membantu atau mempermudah masyarakat yang semula dilakukan dengan cara manual karena harus datang ke kantor pemerintahan terlebih dahulu dan sekarang bisa dilakukan secara online, Pengaduan itu sendiri berbentuk formulir yang harus diisi, setelah masyarakat melakukan pengaduan atau mengirim data yang ada, maka aplikasi akan menyimpan setiap pengaduan ke dalam database

### 2.1 Install Aplikasi
Sebelum pengguna melakukan install aplikasi, pertama-tama device atau handphone yang berbasis android  masuk ke menu settings -> Security -> gulir kebawah dan beri tanda centang pada “Unknown sources”. Pilih OK ketika ada peringatan keluar, setelah itu pengguna kembali ke menu home dan pilih aplikasi playstore untuk mendownload aplikasi. Tulis kata kunci di tombol pencarian *Potret Banten* atau *enstra media*, setelah itu klik tombol *download* dan *install*, seperti gambar dibawah ini aplikasi yang siap untuk di install.

[![Install Aplikasi](/document/aplikasi/potret/images/uat/0019-install-aplikasi-android-epormas.png)](/document/aplikasi/potret/images/uat/0019-install-aplikasi-android-epormas.png)

### 2.1.1 Tampilan Aplikasi
[![Install Aplikasi](/document/aplikasi/potret/images/uat/020-tampilan-awal-android.png)](/document/aplikasi/potret/images/uat/020-tampilan-awal-android.png)

Gambar diatas adalah tampilan awal ketika pengguna sudah melakukan install aplikasi, dimana aplikasi akan melakukan proses pengecekan device id ke dalam database. kalo device id ada di dalam database akan langsung di tampilkan layout dashboard, kalo device id tidak ada dalam database aplikasi akan menampilkan gambar dibawah ini. dimana pengguna harus melakukan registrasi.

[![Install Aplikasi](/document/aplikasi/potret/images/uat/0020-tampilan-awal-android-baca-device.png)](/document/aplikasi/potret/images/uat/0020-tampilan-awal-android-baca-device.png)

Gambar diatas adalah tampilan awal ketika pengguna sudah install aplikasi dan belum melakukan registrasi

[![Install Aplikasi](/document/aplikasi/potret/images/uat/00020-tampilan-awal-android-registrasi-nik.png)](/document/aplikasi/potret/images/uat/00020-tampilan-awal-android-registrasi-nik.png)

Gambar diatas adalah tampilan pengguna sudah install aplikasi dan sebelumnya sudah melakukan registrasi dengan nik

[![Install Aplikasi](/document/aplikasi/potret/images/uat/000020-tampilan-awal-android-registrasi-no-hp.png)](/document/aplikasi/potret/images/uat/000020-tampilan-awal-android-registrasi-no-hp.png)

Gambar diatas adalah tampilan pengguna sudah install aplikasi dan sebelumnya sudah melakukan registrasi dengan no handphone

### 2.1.2 Registrasi
[![Form Registrasi](/document/aplikasi/potret/images/uat/021-tampilan-registrasi.png)](/document/aplikasi/potret/images/uat/021-tampilan-registrasi.png)
[![Registrasi Upload Foto](/document/aplikasi/potret/images/uat/022-tampilan-upload-foto-user.png)](/document/aplikasi/potret/images/uat/022-tampilan-upload-foto-user.png)

Tampilan gambar diatas adalah ketika pengguna mengklik tombol registrasi sekarang, dengan mengisi form kolom input yang tersedia, seperti *nama lengkap, alamat email, nomor telepon atau hp dan upload foto user*. Setelah lengkap klik tombol *registrasi sekarang*.

### 2.1.3 Konten Menu
[![Konten Menu](/document/aplikasi/potret/images/uat/023-tampilan-menu.png)](/document/aplikasi/potret/images/uat/023-tampilan-menu.png)

Tampilan gambar diatas adalah menjelaskan tentang subkonten menu aplikasi, seperti *Home, Profile, Semua Laporan, Draft, Form Offline, Social Media*.

#### 2.1.3.1 Menu Home
[![Kategori Home](/document/aplikasi/potret/images/uat/024-tampilan-menu-home.png)](/document/aplikasi/potret/images/uat/024-tampilan-menu-home.png)

Tampilan gambar diatas adalah terdapat fitur pilih kategori, seperti *Jalan Raya, Pendidikan, Jembatan, Pariwisata, Pemukiman dan Lahan, Gedung Pemerintah, pemuda dan Olahraga, Kesehatan.

#### 2.1.3.2 Menu Form Online
[![Form Online](/document/aplikasi/potret/images/uat/025-tampilan-form-online.png)](/document/aplikasi/potret/images/uat/025-tampilan-form-online.png)

Tampilan gambar diatas adalah form kolom online yang harus diisi,seperti *Judul, Deskripsi, Saran, Upload Foto, dan Lokasi Keluhan Masyarakat*. Setelah selesai pengisian lengkap user bisa pilih *Kirim* atau *Simpan Ke Draft*.

#### 2.1.3.3 Menu Profile User
[![Biodata User](/document/aplikasi/potret/images/uat/026-tampilan-biodata.png)](/document/aplikasi/potret/images/uat/026-tampilan-biodata.png)
[![Laporan User](/document/aplikasi/potret/images/uat/027-tampilan-profil-laporan.png)](/document/aplikasi/potret/images/uat/027-tampilan-profil-laporan.png)

Tampilan gambar diatas adalah menjelaskan tentang biodata dan laporan pengguna.

#### 2.1.3.4 Menu Draft
| Tampilan | URL/ Image | Ada | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Menu Draft | [![Draft](/document/aplikasi/potret/images/uat/029-tampilan-draft.png)](/document/aplikasi/potret/images/uat/029-tampilan-draft.png) | | |

Tampilan gambar diatas adalah kumpulan semua ide-ide yang belum dikirim atau di upload oleh pengguna yang masi tersimpan di draft.

#### 2.1.3.5 Menu Offline
[![Form Offline Jalan Raya](/document/aplikasi/potret/images/uat/029-tampilan-draft.png)](/document/aplikasi/potret/images/uat/029-tampilan-draft.png)

Tampilan gambar diatas adalah Form Offline, dimana pengguna dapat menyimpan laporan keluhan atau pengaduan yang di alami secara offline.

#### 2.1.3.6 Menu Social Media
[![Form Offline Jalan Raya](/document/aplikasi/potret/images/uat/031-tampilan-socialmedia.png)](/document/aplikasi/potret/images/uat/031-tampilan-socialmedia.png)

Tampilan gambar diatas adalah, dimana pengguna bisa share ke social media, seperti  *Facebook, Instagram, Twitter, Google+, Whatsapp*.