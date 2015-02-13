# Teknologi
* HTML5
* JavaScript
* Cordova

# Nama
Aplikasi Android Riwayat Medis

# Konsep
Aplikasi yang menyimpan catatan medis pasien di perangkat Android.

# Fungsionalitas
## Manajemen data pasien
## Laporan
## 

# Data
## Data pasien
* Nomor registrasi
* Nama
* Jenis kelamin
* Tanggal lahir
* Alamat Rumah
* Kota
* no telp rumah
* nomor HP

## Data medis
* Nomor registrasi pasien
* Nomor rekam medis
* Tanggal
* Lokasi pertermuan
* Diagnosa
* Tindakan
* Keluhan (text pendek mungkin 100 karakter cukup)
* Anamnesa (teks panjang / memo karena akan cerita banyak di sini)
* Pemeriksaan (teks panjang/memo)
* Pemeriksaan penunjang (teks panjang/memo)
* Gambar (bisa dimasukkan maksimal 6 gambar di sini, rencananya akan diambil langsung dari kamera/flash disk)
* Keterangan gambar (memo)
* Diagnosa 1 (lihat data diagnosa di bawah)
* Diagnosa 2
* Diagnosa 3
* Diagnosa 4
* Diagnosa 5
* Rencana (memo)
 
## Data terapi
* Nomor rekam medis
* Nama obat
* Jumlah
* Aturan penggunaan

## Data diagnosa
* Kode ICD
* Diagnosa

## Data dokter
* Nama dokter
* Nomor Surat Izin Praktik
* Alamat praktik
* Telepon praktik
* Nama Rumah Sakit
* Alamat Rumah Sakit
* Telepon Rumah Sakit

# Halaman
## Formulir pasien

Isi data pasien

## Halaman laporan


## Halaman setting

* Isi/ubah data dokter
* Isi/ubah data diagnosa


terdiri dari beberapa link

I. Masukkan data pasien baru

II. mencari pasien lama

III. Reports

IV. Setting

saat di klik akan masuk ke form berikutnya.

Form I. Masukkan Data Baru

berisi :

Nomor Registrasi rekam medis (urut)

Nama

Jenis kelamin (Pulldown menu)

Tanggal lahir

umur (otomatis)

Alamat Rumah

Kota

no telp rumah

nomor HP

setelah itu di bawahnya ada dua tombol

poliklinis

operasi

Rawat inap

yang kalau di klik akan membuka form poliklinis atau kamar operasi

Form II. Mencari pasien lama berdasarkan

nama

tanggal kontrol / bertemu terakhir

alamat

kota

sebaiknya berbentuk beberapa kolom dan bisa dikombinasi

setelah muncul hasil pencarian dalam bentuk tabel seperti di bawah ini (contoh)

tabel 1

nomor nama Alamat Diagnosa terakhir

12345 superman jl. metropolis BPH

12346 batman jl. gotham Batu ureter D 1/3 distal

Ketika salah satu kolom di klik maka akan muncul halaman berisi data dasar pasien seperti di atas,

dilengkapi dengan daftar pertemuan sebelumnya.

Form I­1

Contoh :

Nomor Registrasi rekam medis :00001

Nama : Superman

Jenis kelamin : Laki­laki

Tanggal lahir : 1 januari 1930

umur :

Alamat Rumah : Jl. Metropo

Kota : Samarinda

no telp rumah : 0541 707070

nomor HP :0812345678

(tabel 2)

Tanggal Tempat bertemu Diagnosa Follow Up

1­1­2013 Praktek BPH Keluhan tidak bisa

12­1­2013 OK RS. Dirgahayu BPH Operasi TUR Prostat

13­1­2013 Ruang Yakobus RS

Dirgahayu

Data di atas adalah data yang pernah dimasukkan. Jika pasien baru maka data itu akan kosong. Saat

salah satu kolom di klik (misalnya kolom tanggal) maka akan membuka form yang dimasukkan pada

tanggal itu (kalau pasien itu kontrol maka saya bisa melihat di kontrol sebelumnya apa yang saya

rencanakan, tanpa bisa diubah

Di bawah tabel ini ada 2 tombol yang jika di klik akan membuka jendela baru yaitu tombol :

a. Poliklinis

b. Kamar Operasi

c. Rawat inap

a. Poliklinis (praktek)

Ketika di klik tombol poliklinis, maka masuk ke form pengisian data poliklinis (Praktek)

saat di save maka data ini bisa muncul di tabel 2 sebagai “praktek” atau 'poli'

form a

Nomor Registrasi Rekam Medis (otomatis)

Nama (otomatis)

Jenis Kelamin (otomatis)

Usia (otomatis, tanggal lahir dikurangi tanggal saat ini)

Alamat (otomatis)

Tanggal (otomatis tanggal pembuatan)

Tempat : (dropdown menu 'praktek' , 'poli'. Praktek berarti di tempat praktek swasta, poli berarti di

poli RSU AWS)

Keluhan (text pendek mungkin 100 karakter cukup)

Anamnesa (teks panjang / memo karena akan cerita banyak di sini)

Pemeriksaan (teks panjang/memo)

Pemeriksaan penunjang (teks panjang/memo)

Gambar (bisa dimasukkan maksimal 6 gambar di sini, rencananya akan diambil langsung dari kamera /

flash disk)

Keterangan gambar (memo)

Diagnosa 1 (teks pendek, bisa terdiri dari 2 bagian yaitu nomor ICD dan nama penyakit, pull down

menu)

Diagnosa 2

Diagnosa 3

Diagnosa 4

Diagnosa 5

Rencana (memo)

Terapi (terdiri dari tabel seperti di bawah ini ) (tabel 3)

nama obat Jumlah obat Aturan penggunaan

Di bawah terapi ada tombol “cetak resep” yang akan mengambil format :

Report 1 (cetak resep)

<kop Resep>(berisi nama dokter, alamat praktek, nomor SIP)

R/ <nama obat> no. <jumlah obat>

S (ini harusnya dibaca 'signa') <aturan penggunaan>

<garis bawah> (saya akan tanda tangan di garis bawah ini)

R/ <nama obat> no. <jumlah obat>

S (ini harusnya dibaca 'signa') <aturan penggunaan>

<garis bawah> (saya akan tanda tangan di ujung garis bawah ini)

sampai semua obat tertulis

di bagian bawah resep :

Nama pasien :

Umur :

b. Kamar Operasi

Form kamar operasi ini akan mencatat semua kegiatan di kamar operasi yang berhubungan dengan

pasien.

Form b

Nomor Registrasi Rekam Medis (otomatis)

Nama (otomatis)

Umur (otomatis)

Jenis Kelamin (otomatis)

Alamat (otomatis)

(nama jenis kelamin dan alamat akan selalu diulang di tiap form untuk sarana cek dan recek)

Tempat (pull down menu)

Diagnosa 1 ( terdiri dari 2 kolom , satu berisi nomor ICD satu diagnosa.)

Diagnosa 2 (sama)

diagnosa 3 (sama)

Diagnosa 4(sama)

Diagnosa 5 (sama)

Tindakan 1 (dua kolom, nomor ICOPIM dan nama tindakan)

Tindakan 2 (sama)

Tindakan 3 (sama)

Tindakan 4 (sama)

Laporan operasi (teks panjang / memo)

Advis post op (teks panjang / memo)

Dokumentasi operasi (bisa memasukkan sampai 6 foto)

Keterangan (memo)

c. rawat inap

Rawat inap akan memasukkan data yang dimasukkan saat visit di ruangan

form c

Nomor Rekam medis (otomatis)

Nama (otomatis)

Jenis kelamin (otomatis)

Umur (otomatis)

Tempat (pull Down menu)

Keluhan utama (teks pendek, 100 karakter)

Anamnesa : (teks panjang / memo)

Pemeriksaan fisik : (teks panjang)

Pemeriksaan penunjang : teks panjang

Diagnosa 1 (dua kolom, pull down, kolom 1 nomor ICD, kolom 2 Diagnosa)

Diagnosa 2 (sama)

Diagnosa 3 (sama)

Diagnosa 4 (sama)

Diagnosa 5 (sama)

Rencana : (teks panjang)

Terapi (memo)

III. Reports

Berfungsi untuk pencarian dan pengolahan data. Di bagian ini saya memerlukan banyak masukan

benernya. Yang ada di kepala saya sih gunanya buat statistik. Jadi akan ada kolom

Jenis kelamin

umur(bisa dibuat range misalnya 30­50 tahun)

Diagnosa (ICD dan nama diagnosa)

Tanggal awal

Tanggal akhir

Tindakan

tempat

variabel di atas akan menjadi dasar pencarian yang akhirnya akan ditampilkan di tabel seperti di

bawah ini

tabel 4

No rekam

medik

nama umur Jenis kelamin diagnosa tindakan tempat

Seperti biasa, jika bagian nama atau nomor rekam medik akan membuka data pasien ( form I­1)

Kemudian tabel ini bisa dieksport ke format excel (xls) atau open document sheet (ods) yang

akan diolah lebih lanjut. Tapi saya tetap perlu saran untuk bagian ini

IV. Setting

pada bagian ini akan terdapat tempat untuk mengatur data yang akan ditampilkan di resep serta

mengedit daftar penyakit dan tindakan

untuk data yang ditulis di kepala (kop) resep yang dapat dimasukkan adalah :

Nama dokter

nomor SIP (Surat Izin Praktek)

Alamat Praktek (2 baris)

Telp Praktek

Nama dan alamat RS (2 baris)

Telp RS

kira­kira format kop resep sebagai berikut :

Alamat Praktek

no telp praktek

Nama pasien :

Umur :

Jadi di form IV ini akan ada beberapa link

1. ubah data dokter

2. masukkan ICD 10 (diagnosa)

3. masukkan ICD9CM (tindakan)

4. masukkan tempat tindakan

Tambahan :

1. setiap memasukkan foto, maka foto saat di insert akan dicopy ke folder 'foto' yang terdapat di

folder yang sama dengan folder EMR, supaya ukuran file EMR tidak terlalu besar. Bila foto di

EMR di klik akan membuka foto di browser sehingga bisa di print bila diinginkan.

2. Ada form pull down menu untuk tempat : berisi nama tempat yang bisa ditambahkan. Cukup

satu kolom saja

3. Ada form untuk memasukkan nomor ICD dan diagnosa. Terdiri dari dua kolom, nomor ICD

dan diagnosa. Jd diagnosa akan dimasukkan manual ke form ini, datanya bisa diambil setiap

kali ada kolom diagnosa

4. Ada form untuk tindakan, dengan mengambil nomor ICD9CM, terdiri dari dua kolom juga,

kolom ICOPIM dan nama tindakan. Akan diambil setiap kali ada kolom tindakan
