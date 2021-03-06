---
layout: item
title: "Pengembangan"
date: 2018-05-16
layout: item
title: "Pengembangan"
date: 2018-05-16 16:25:06 +0700
comments: true
---

## Daftar Isi

[TOC]

Sistem Media Ruang Provinsi Banten ini dibangun dengan tujuan untuk memudahkan pemerintah dan masyarakat dalam mencari informasi mengenai lokasi, status, serta demografi Media Ruang yang terdapat pada Provinsi Banten. Deskripsi Umum kebutuhan aplikasi yang akan diimplementasikan meliputi semua informasi yang bersifat teknis dan menjadi acuan dalam pengembangan apliksi.

Berikut ini adalah tampilan - tampilan yang terdapat didalam apliaksi Media Ruang:

## 1. Tampilan Website

### 1.1. Tampilan Awal Media Ruang

Untuk memulai akses terhadap aplikasi Media Ruang ini *user* dapat membuka web browser (IE, Mozila Firefox atau yang lainnya) dengan menulis alamat url (server sementara) https://bilboard.bangunbanten.com/ kemudian tekan Enter pada tombol keyboard atau klik tombol Go pada browser. Sehingga akan muncul tampilan seperti dibawah ini :

#### 1.1.1 Tampilan Home

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_awal_home.png)](../images/sso/pengembangan/20180809_awal_home.png)
[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_awal_home1.png)](../images/sso/pengembangan/20180809_awal_home1.png)
[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_awal_home2.png)](../images/sso/pengembangan/20180809_awal_home2.png)

Pada tampilan ini *user* dapat melihat informasi - informasi yang terdapat pada aplikasi Media Ruang seperti map dan data - data Media Ruang yang sudah terpetakan dalam aplikasi.

#### 1.1.2 Tampilan Map

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_awal_map.png)](../images/sso/pengembangan/20180809_awal_map.png)
[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_awal_map1.png)](../images/sso/pengembangan/20180809_awal_map1.png)

Pada tampilan Map ini *user* dapat melihat map yang berisikan informasi letak - letak Media Ruang pada daerah Banten. Pada Halaman ini *user* dapat melakukan pencarian Media Ruang berdasarkan lokasi Kota, Kecamatan dan Kelurahan

#### 1.1.3 Tampilan Login

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_awal_login.png)](../images/sso/pengembangan/20180809_awal_login.png)

Pada tampilan ini *user* akan disajikan dengan form Login, Form login ini dapat digunakan oleh OPD dan Superadmin untuk masuk kedalam aplikasi Media Ruang sesuai dengan tupoksi nya masing - masing.

### 1.2. Tampilan OPD

Tampilan ini dapat diakses oleh OPD ketika berhasil melakukan Login kedalam aplikasi Media Ruang.

#### 1.2.1 Tampilan Home

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_opd_home.png)](../images/sso/pengembangan/20180809_opd_home.png)
[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_awal_home1.png)](../images/sso/pengembangan/20180809_awal_home1.png)
[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_awal_home2.png)](../images/sso/pengembangan/20180809_awal_home2.png)

Pada tampilan ini OPD dapat melihat informasi - informasi yang terdapat pada aplikasi Media Ruang seperti map dan data - data Media Ruang yang sudah terpetakan dalam aplikasi. pada tampilan ini terdapat beberapa modul yaitu Home, Map dan Buat Laporan.

#### 1.2.2 Tampilan Map

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_opd_map.png)](../images/sso/pengembangan/20180809_opd_map.png)
[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_opd_map1.png)](../images/sso/pengembangan/20180809_opd_map1.png)

Pada tampilan Map ini OPD dapat melihat map yang berisikan informasi letak - letak Media Ruang pada daerah Banten. Pada Halaman ini *user* dapat melakukan pencarian Media Ruang berdasarkan lokasi Kota, Kecamatan dan Kelurahan

#### 1.2.3 Tampilan Buat Laporan

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_opd_buat-laporan.png)](../images/sso/pengembangan/20180809_opd_buat-laporan.png)
[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_opd_buat-laporan1.png)](../images/sso/pengembangan/20180809_opd_buat-laporan1.png)

Pada tampilan Buat Laporan ini OPD dapat membuat data Media Ruang untuk memetakan Media Ruang dengan mengisi form buat laporan seperti pada gambar diatas.

#### 1.2.4 Profile OPD

Modul Profile OPD ini dapat diakses dengan mengklik tulisan "Nama OPD" pada pojok kanan atas aplikasi, pada modul ini terdapat 2 submodul yaitu :

##### 1.2.4.1 Account

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_opd_account.png)](../images/sso/pengembangan/20180809_opd_account.png)

Tampilan ini dapat diakses dengan mengklik tulisan Account pada "Nama OPD". Pada tampilan ini OPD dapat mengatur data profile OPD dengan mengisi form Account Setting.

##### 1.2.4.2 Log Out

Sub modul Log Out ini dapat diakses dengan mengklik tulisan Log Out pada "Nama OPD". Sub modul ini digunakan OPD untu melakukan Log Out atau keluar dari Tampilan OPD.

### 1.3. Tampilan Superadmin

Tampilan ini dapat diakses oleh Superadmin ketika berhasil melakukan Login kedalam aplikasi Media Ruang.

#### 1.3.1 Dashboard

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_dashboard.png)](../images/sso/pengembangan/20180809_sa_dashboard.png)

Tampilan Dashboard ini dapat diakses ketika superadmin berhasil melakukan Login kedalam apilaksi Media Ruang. Pada halaman ini superadmin dapat meilhat informasi - informasi yang terdapat didalam aplikasi Media Ruang, pada tapilan ini terdapat beberapa modul yang terdapat pada bagian atas aplikasi seperti Dashboard, Media Ruang, Pengaturan dan Users & Permission

#### 1.3.2 Media Ruang

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_billboard.png)](../images/sso/pengembangan/20180809_sa_billboard.png)

Tampilan Media Ruang ini dapat diakses dengan mengklik tulisan Media Ruang pada bagian atas aplikasi. pada tampilan ini superadmin dapat melihat tabel data Media Ruang yang telah terinput kedalam aplikasi. pada tampilan ini terdapat beberapa bantuan seperti kolom pencarian, tambah Media Ruang, publish, lihat detail, edit dan delete

##### 1.3.2.1 Kolom Pencarian

Kolom Pencarian ini dapat diakses dengan mengetik *keyword* yang di inginkan pada kotak pencarian yang berada di kiri atas tabel Media Ruang.

##### 1.3.2.2 Tambah Media Ruang

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_billboard_tambah.png)](../images/sso/pengembangan/20180809_sa_billboard_tambah.png)
[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_billboard_tambah1.png)](../images/sso/pengembangan/20180809_sa_billboard_tambah1.png)

Tampilan Tambah Media Ruang ini dapat diakses dengan mengklik tombol Tambah Media Ruang pada bagian kanan atas tabel Media Ruang. Pada tampilan ini superadmin dapat menambahkan data baru Media Ruang pada aplikasi dengan mengisi form tambah Media Ruang.

##### 1.3.2.3 Publish Media Ruang

Publish Media Ruang ini dapat diakses dengan mengklik icon gembok pada kolom action Media Ruang. pada Publish Media Ruang ini superadmin dapat mengatur apakah data Media Ruang akan dipublish atau tidak.

##### 1.3.2.4 Lihat Detail Media Ruang

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_billboard_detail.png)](../images/sso/pengembangan/20180809_sa_billboard_detail.png)
[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_billboard_detail1.png)](../images/sso/pengembangan/20180809_sa_billboard_detail1.png)

Tampilan Lihat Detail Media Ruang ini dapat diakses dengan mengklik icon mata pada kolom action di tabel Media Ruang. Pada tampilan ini superadmin dapat melihat detail data Media Ruang.

##### 1.3.2.5 Edit Media Ruang

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_billboard_edit.png)](../images/sso/pengembangan/20180809_sa_billboard_edit.png)
[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_billboard_edit1.png)](../images/sso/pengembangan/20180809_sa_billboard_edit1.png)
[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_billboard_edit2.png)](../images/sso/pengembangan/20180809_sa_billboard_edit2.png)

Tampilan Edit Media Ruang ini dapat diakses dengan mengklik icon pensil pada kolom action di tabel Media Ruang. Pada tampilan ini superadmin dapat mengedit / merubah data Media Ruang.

##### 1.3.2.6 Delete Media Ruang

Delete Media Ruang ini dapat diakses dengan mengklik icon tong sampah pada kolom action Media Ruang. pada Delete Media Ruang ini superadmin dapat menghapus data Media Ruang.

#### 1.3.3 Pengaturan

Pada modul Pengaturan ini terdapat beberapa modul yaitu Banner, Video dan Sosial Media.

##### 1.3.3.1 Banner

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_pengaturan_banner.png)](../images/sso/pengembangan/20180809_sa_pengaturan_banner.png)

Tampilan Banner ini dapat diakses dengan mengklik tulisan Banner pada Modul Pengaturan. pada tampilan ini superadmin dapat melihat tabel data banner yang telah terinput kedalam aplikasi. pada tampilan ini terdapat beberapa bantuan seperti kolom pencarian, tambah banner, edit dan delete

###### 1.3.3.1.1 Kolom Pencarian

Kolom Pencarian ini dapat diakses dengan mengetik *keyword* yang di inginkan pada kotak pencarian yang berada di kiri atas tabel banner.

###### 1.3.3.1.2 Tambah Banner

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_pengaturan_banner_tambah.png)](../images/sso/pengembangan/20180809_sa_pengaturan_banner_tambah.png)

Tampilan Tambah Banner ini dapat diakses dengan mengklik tombol Tambah Banner pada bagian kanan atas tabel banner. Pada tampilan ini superadmin dapat menambahkan data baru Banner pada aplikasi dengan mengisi form tambah Banner.

###### 1.3.3.1.3 Edit Banner

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_pengaturan_banner_edit.png)](../images/sso/pengembangan/20180809_sa_pengaturan_banner_edit.png)

Tampilan Edit Banner ini dapat diakses dengan mengklik icon pensil pada kolom action di tabel banner. Pada tampilan ini superadmin dapat mengedit / merubah data banner.

###### 1.3.3.1.4 Delete Banner

Delete Banner ini dapat diakses dengan mengklik icon tong sampah pada kolom action banner. pada Delete Banner ini superadmin dapat menghapus data banner.

##### 1.3.3.2 Video

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_pengaturan_video.png)](../images/sso/pengembangan/20180809_sa_pengaturan_video.png)

Tampilan Video ini dapat diakses dengan mengklik tulisan Video pada Modul Pengaturan. pada tampilan ini superadmin dapat melihat tabel data video yang telah terinput kedalam aplikasi. pada tampilan ini terdapat beberapa bantuan seperti kolom pencarian, tambah, edit dan delete video.

###### 1.3.3.2.1 Kolom Pencarian

Kolom Pencarian ini dapat diakses dengan mengetik *keyword* yang di inginkan pada kotak pencarian yang berada di kiri atas tabel video.

###### 1.3.3.2.2 Tambah Video

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_pengaturan_video_tambah.png)](../images/sso/pengembangan/20180809_sa_pengaturan_video_tambah.png)

Tampilan Tambah Video ini dapat diakses dengan mengklik tombol Tambah Video pada bagian kanan atas tabel video. Pada tampilan ini superadmin dapat menambahkan data baru Video pada aplikasi dengan mengisi form tambah Video.

###### 1.3.3.2.3 Edit Video

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_pengaturan_video_edit.png)](../images/sso/pengembangan/20180809_sa_pengaturan_video_edit.png)

Tampilan Edit Video ini dapat diakses dengan mengklik icon pensil pada kolom action di tabel Video. Pada tampilan ini superadmin dapat mengedit / merubah data Video.

###### 1.3.3.2.4 Delete Video

Delete Video ini dapat diakses dengan mengklik icon tong sampah pada kolom action Video. pada Delete Video ini superadmin dapat menghapus data Video.

##### 1.3.3.3 Kategori

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180821_sa_pengaturan_kategori.png)](../images/sso/pengembangan/20180821_sa_pengaturan_kategori.png)

Tampilan Kategori ini dapat diakses dengan mengklik tulisan Kategori pada Modul Pengaturan. pada tampilan ini superadmin dapat melihat tabel data kategori yang telah terinput kedalam aplikasi. pada tampilan ini terdapat beberapa bantuan seperti kolom pencarian, tambah, edit dan delete kategori.

###### 1.3.3.3.1 Kolom Pencarian

Kolom Pencarian ini dapat diakses dengan mengetik *keyword* yang di inginkan pada kotak pencarian yang berada di kiri atas tabel kategori.

###### 1.3.3.3.2 Tambah Kategori

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180821_sa_pengaturan_kategori_tambah.png)](../images/sso/pengembangan/20180821_sa_pengaturan_kategori_tambah.png)

Tampilan Tambah Kategori ini dapat diakses dengan mengklik tombol Tambah Kategori pada bagian kanan atas tabel kategori. Pada tampilan ini superadmin dapat menambahkan data baru kategori pada aplikasi dengan mengisi form tambah kategori.

###### 1.3.3.3.3 Edit Kategori

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180821_sa_pengaturan_kategori_edit.png)](../images/sso/pengembangan/20180821_sa_pengaturan_kategori_edit.png)

Tampilan Edit Kategori ini dapat diakses dengan mengklik icon pensil pada kolom action di tabel kategori. Pada tampilan ini superadmin dapat mengedit / merubah data kategori.

###### 1.3.3.3.4 Delete Kategori

Delete Kategori ini dapat diakses dengan mengklik icon tong sampah pada kolom action kategori. pada Delete Kategori ini superadmin dapat menghapus data kategori.

##### 1.3.3.4 Sosial Media

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_pengaturan_sosmed.png)](../images/sso/pengembangan/20180809_sa_pengaturan_sosmed.png)

Tampilan Sosial Media ini dapat diakses dengan mengklik tulisan Sosial Media pada Modul Pengaturan. pada tampilan ini superadmin dapat melihat tabel data sosial media yang telah terinput kedalam aplikasi. pada tampilan ini terdapat beberapa bantuan seperti kolom pencarian, tambah, edit dan delete sosial media.

###### 1.3.3.4.1 Kolom Pencarian

Kolom Pencarian ini dapat diakses dengan mengetik *keyword* yang di inginkan pada kotak pencarian yang berada di kiri atas tabel sosial media.

###### 1.3.3.4.2 Tambah Sosial Media

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_pengaturan_sosmed_tambah.png)](../images/sso/pengembangan/20180809_sa_pengaturan_sosmed_tambah.png)

Tampilan Tambah Sosial Media ini dapat diakses dengan mengklik tombol Tambah Sosmed pada bagian kanan atas tabel sosial media. Pada tampilan ini superadmin dapat menambahkan data baru sosial media pada aplikasi dengan mengisi form tambah sosial media.

###### 1.3.3.4.3 Edit Sosial Media

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_pengaturan_sosmed_edit.png)](../images/sso/pengembangan/20180809_sa_pengaturan_sosmed_edit.png)

Tampilan Edit Sosial Media ini dapat diakses dengan mengklik icon pensil pada kolom action di tabel sosial media. Pada tampilan ini superadmin dapat mengedit / merubah datasosial media.

###### 1.3.3.4.4 Delete Sosial Media

Delete Sosial Media ini dapat diakses dengan mengklik icon tong sampah pada kolom action sosial media. pada Delete Sosial Media ini superadmin dapat menghapus data sosial media.

#### 1.3.4 Users & Permission

Pada modul Users & Permission ini terdapat beberapa modul yaitu User, Permission dan Role

##### 1.3.4.1 Users

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_unp_user.png)](../images/sso/pengembangan/20180809_sa_unp_user.png)

Tampilan Users ini dapat diakses dengan mengklik tulisan User pada Modul Users & Permission. pada tampilan ini superadmin dapat melihat tabel data user yang terdapat pada aplikasi. pada tampilan ini terdapat beberapa bantuan seperti kolom pencarian, tambah, edit dan delete user.

###### 1.3.4.1.1 Kolom Pencarian

Kolom Pencarian ini dapat diakses dengan mengetik *keyword* yang di inginkan pada kotak pencarian yang berada di kiri atas tabel user.

###### 1.3.4.1.2 Tambah User

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_unp_user_tambah.png)](../images/sso/pengembangan/20180809_sa_unp_user_tambah.png)

Tampilan Tambah User ini dapat diakses dengan mengklik tombol Tambah User pada bagian kanan atas tabel user. Pada tampilan ini superadmin dapat menambahkan data baru user pada aplikasi dengan mengisi form tambah user.

###### 1.3.4.1.3 Edit User

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_unp_user_edit.png)](../images/sso/pengembangan/20180809_sa_unp_user_edit.png)

Tampilan Edit User ini dapat diakses dengan mengklik icon pensil pada kolom action di tabel user. Pada tampilan ini superadmin dapat mengedit / merubah data user.

###### 1.3.4.1.4 Delete User

Delete User ini dapat diakses dengan mengklik icon tong sampah pada kolom action user. pada Delete User ini superadmin dapat menghapus data user.

##### 1.3.4.2 Permission

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_unp_permission.png)](../images/sso/pengembangan/20180809_sa_unp_permission.png)

Tampilan Permission ini dapat diakses dengan mengklik tulisan Permission pada Modul Users & Permission. pada tampilan ini superadmin dapat melihat tabel data permission yang terdapat pada aplikasi. pada tampilan ini terdapat beberapa bantuan seperti kolom pencarian, tambah, lihat detail, edit  dan delete permission

###### 1.3.4.2.1 Kolom Pencarian

Kolom Pencarian ini dapat diakses dengan mengetik *keyword* yang di inginkan pada kotak pencarian yang berada di kiri atas tabel permission.

###### 1.3.4.2.2 Tambah Permission

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_unp_permission_tambah.png)](../images/sso/pengembangan/20180809_sa_unp_permission_tambah.png)

Tampilan Tambah Permission ini dapat diakses dengan mengklik tombol Tambah Permission pada bagian kanan atas tabel permission. Pada tampilan ini superadmin dapat menambahkan data baru permission pada aplikasi dengan mengisi form tambah permission.

###### 1.3.4.2.3 Lihat Detail Permission

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_unp_permission_detail.png)](../images/sso/pengembangan/20180809_sa_unp_permission_detail.png)

Tampilan Lihat Detail Permission ini dapat diakses dengan mengklik icon mata pada kolom action di tabel permission. Pada tampilan ini superadmin dapat melihat detail permission.

###### 1.3.4.2.4 Edit Permission

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_unp_permission_edit.png)](../images/sso/pengembangan/20180809_sa_unp_permission_edit.png)

Tampilan Edit Permission ini dapat diakses dengan mengklik icon pensil pada kolom action di tabel permission. Pada tampilan ini superadmin dapat mengedit / merubah data permission.

###### 1.3.4.2.5 Delete Permission

Delete Permission ini dapat diakses dengan mengklik icon tong sampah pada kolom action permission. pada Delete Permission ini superadmin dapat menghapus data permission.

##### 1.3.4.3 Role

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_unp_role.png)](../images/sso/pengembangan/20180809_sa_unp_role.png)

Tampilan Role ini dapat diakses dengan mengklik tulisan Role pada Modul Users & Permission. pada tampilan ini superadmin dapat melihat tabel data role yang terdapat pada aplikasi. pada tampilan ini terdapat beberapa bantuan seperti kolom pencarian, tambah, lihat detail, edit, Add Permission dan delete role.

###### 1.3.4.3.1 Kolom Pencarian

Kolom Pencarian ini dapat diakses dengan mengetik *keyword* yang di inginkan pada kotak pencarian yang berada di kiri atas tabel role.

###### 1.3.4.3.2 Tambah Role

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_unp_role_tambah.png)](../images/sso/pengembangan/20180809_sa_unp_role_tambah.png)

Tampilan Tambah Role ini dapat diakses dengan mengklik tombol Tambah Role pada bagian kanan atas tabel role. Pada tampilan ini superadmin dapat menambahkan data baru role pada aplikasi dengan mengisi form tambah role.

###### 1.3.4.3.3 Lihat Detail Role

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_unp_role_detail.png)](../images/sso/pengembangan/20180809_sa_unp_role_detail.png)

Tampilan Lihat Detail Role ini dapat diakses dengan mengklik icon mata pada kolom action di tabel role. Pada tampilan ini superadmin dapat melihat detail role.

###### 1.3.4.3.4 Edit Role

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_unp_role_edit.png)](../images/sso/pengembangan/20180809_sa_unp_role_edit.png)

Tampilan Edit Role ini dapat diakses dengan mengklik icon pensil pada kolom action di tabel role. Pada tampilan ini superadmin dapat mengedit / merubah data role.

###### 1.3.4.3.5 Add Permission

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_unp_role_tambah-permission.png)](../images/sso/pengembangan/20180809_sa_unp_role_tambah-permission.png)

Tampilan Add Permission ini dapat diakses dengan mengklik tombol Add Permission pada kolom action di tabel role. Pada tampilan ini superadmin dapat memberikan permission / hak akses kepada role yang diinginkan.

###### 1.3.4.3.6 Delete Role

Delete Role ini dapat diakses dengan mengklik icon tong sampah pada kolom action role. pada Delete Role ini superadmin dapat menghapus data role.

#### 1.3.5 Profile Superadmin

Modul Profile Superadmin ini dapat diakses dengan mengklik tulisan "Superadmin" pada pojok kanan atas aplikasi, pada modul ini terdapat 2 submodul yaitu :

##### 1.3.5.1 Account

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_sa_account.png)](../images/sso/pengembangan/20180809_sa_account.png)

Tampilan ini dapat diakses dengan mengklik tulisan Account pada "Superadmin". Pada tampilan ini Superadmin dapat mengatur data profile Superadmin dengan mengisi form Account Setting.

##### 1.3.5.2 Log Out

Sub modul Log Out ini dapat diakses dengan mengklik tulisan Log Out pada "Superadmin". Sub modul ini digunakan Superadmin untu melakukan Log Out atau keluar dari Tampilan Superadmin.

## 2. Tampilan Android

### 2.1 Login

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_and_login.jpeg)](../images/sso/pengembangan/20180809_and_login.jpeg)

Tampilan Login ini akan muncul ketika *user* membuka aplikasi, pada tampilan login ini terdapat 2 (dua) *field* yang harus diisi oleh *user* yaitu NIK dan Password.

### 2.2 View List

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_and_view-list.jpeg)](../images/sso/pengembangan/20180809_and_view-list.jpeg)

Pada tampilan View List ini *user* dapat melihat list Media Ruang yang sudag terdaftar pada aplikasi.

#### 2.2.1 View List Detail

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_and_view-list_detail.jpeg)](../images/sso/pengembangan/20180809_and_view-list_detail.jpeg)

Tampilan View List Detail ini dapat diakses dengan mengklik Media Ruang yang akan dilihat detailnya pada tampilan View List. Pada tampilan ini *user* dapat melihat detail Media Ruang yang sudah terdaftar pada aplikasi.

### 2.3 View Map

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_and_view-maps.jpeg)](../images/sso/pengembangan/20180809_and_view-maps.jpeg)

Pada tampilan View Maps ini *user* dapat melihat denah lokasi Media Ruang pada peta yang disediakan. Pada tampilan ini *user* dapat memfilter pencarian Media Ruang berdasarkan Kota, Kecamatan dan Kelurahan.

### 2.4 Tambah Media Ruang

[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_and_tambah-billboard.jpeg)](../images/sso/pengembangan/20180809_and_tambah-billboard.jpeg)
[![ilustrasi-alur-prototyping](../images/billboard/pengembangan/20180809_and_tambah-billboard1.jpeg)](../images/sso/pengembangan/20180809_and_tambah-billboard1.jpeg)

Tampilan Tambah Media Ruang ini dapat diakses dengan megklik "+" pada lingkaran berwarna pink pada aplikasi. Pada tampilan ini akan ditampilkan form untuk menambah data Media Ruang ke aplikasi Media Ruang.

