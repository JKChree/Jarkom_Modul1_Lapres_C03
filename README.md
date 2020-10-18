# Jarkom_Modul1_Lapres_C03

## Brananda Denta WP - 05111840000143, R. Dafa Berlian Denmar - 05111840000149

## Outline

+ [Soal 1](#soal-1)
+ [Soal 2](#soal-2)
+ [Soal 3](#soal-3)
+ [Soal 4](#soal-4)
+ [Soal 5](#soal-5)
+ [Soal 6](#soal-6)
+ [Soal 7](#soal-7)
+ [Soal 8](#soal-8)
+ [Soal 9](#soal-9)
+ [Soal 10](#soal-10)
+ [Soal 11](#soal-11)
+ [Soal 12](#soal-12)
+ [Soal 13](#soal-13)
+ [Soal 14](#soal-14)
+ [Soal 15](#soal-15)

## Soal 1

Sebutkan webserver yang digunakan pada "testing.mekanis.me"!

### Langkah Pengerjaan

- Mengetik syntax `http.host contains "testing"` pada kolom filter.
- Lalu klik kanan pada yang tertunjuk pertama, lalu pilih follow->tcpstream, lalu akan terlihat webserver yang digunakan

### Screenshot

![no 1](/img/Picture1.jpg)

## Soal 2

Simpan gambar "Tim_Kunjungan_Kerja_BAKN_DPR_RI_ke_Sukabumi141436.jpg"!

### Langkah Pengerjaan

- Klik file -> export object -> HTTP

- lalu pada text filter diisi `Tim_Kunjungan_Kerja_BAKN_DPR_RI_ke_Sukabumi141436.jpg` dan pilih save

### Screenshot

![no 2](/img/Picture2.png)

## Soal 3

Cari username dan password ketika login di "ppid.dpr.go.id"!

### Langkah Pengerjaan

- mengetik syntax `http.request.method == POST` pada kolom filter
- lalu klik kanan pada yang terpilih, lalu pilih follow -> tcp stream
- lalu ketik `username` pada  text filter dan akan terlihat username dan password nya.

### Screenshot
![no 3](/img/Picture3.jpg)

## Soal 4

Temukan paket dari web-web yang menggunakan basic authentication method!

### Langkah Pengerjaan

- mengetik `http.authbasic` pada kolom filter
- lalu akan tampil web web yang menggunakan basic authentification method 

### Screenshot

![no 4](/img/Picture4.jpg)

![no 4.1](/img/Picture7.jpg)

## Soal 5

Ikuti perintah di aku.pengen.pw! Username dan password bisa didapatkan dari file .pcapng!

### Langkah Pengerjaan

- mengetik http.host contains "aku.pengen" pada kolom filter, lalu username dapat dilihat pada Hypertext Transfer Protocol->GET /favicon.ico HTTP/1.1\r\n -> Authorization: Basic -> Crudentials : kakakgamtenk:hartatahtabermuda
- lalu buka aku.pengen.pw pada browser dan masukkan username dan password
-lalu jawab pertanyaan nya

### Screenshot

![no 5](/img/Picture8.jpg)

![no 5.1](/img/Picture9.jpg)

## Soal 6
Seseorang menyimpan file zip melalui FTP dengan nama "Answer.zip". Simpan dan Buka file "Open This.pdf" di Answer.zip. Untuk mendapatkan password zipnya, temukan dalam file zipkey.txt (passwordnya adalah isi dari file txt tersebut).

### Langkah Pengerjaan
- 

### Screenshot

### Soal 7
7. Ada 500 file zip yang disimpan ke FTP Server dengan nama 1.zip, 2.zip, ..., 500.zip. Salah satunya berisi pdf yang berisi puisi. Simpan dan Buka file pdf tersebut.
### Langkah Pengerjaan

### Soal 8
8. Cari objek apa saja yang didownload (RETR) dari koneksi FTP dengan Microsoft FTP Service!
### Langkah Pengerjaan

### Soal 9
9. Cari username dan password ketika login FTP pada localhost!
### Langkah Pengerjaan

### Soal 10
10. Cari file .pdf di wireshark lalu download dan buka file tersebut!
clue: "25 50 44 46" 

### Langkah Pengerjaan

### Soal 11
11. Filter sehingga wireshark hanya mengambil paket yang mengandung port 21!
### Langkah Pengerjaan

### Soal 12
12. Filter sehingga wireshark hanya mengambil paket yang berasal dari port 80!
### Langkah Pengerjaan

### Soal 13
13. Filter sehingga wireshark hanya menampilkan paket yang menuju port 443!
### Langkah Pengerjaan

### Soal 14
14. Filter sehingga wireshark hanya mengambil paket yang berasal dari ip kalian!
### Langkah Pengerjaan

### Soal 15
15. Filter sehingga wireshark hanya mengambil paket yang tujuannya ke monta.if.its.ac.id!
### Langkah Pengerjaan




