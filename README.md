# Jarkom_Modul1_Lapres_C03

- Brananda Denta WP - 05111840000143
- R. Dafa Berlian Denmar - 05111840000149

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

- Mengetik syntax `http.host contains "testing"` pada kolom display filter.
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
- ketik syntax ftp-data pada kolom filter
- lalu klik kanan pada yang ada answer.zip nya lalu pilih follow->ftp stream
- lalu ganti Show and save data as nya menjadi Raw
- lalu klik save dan save sebagai Answer.zip
- untuk mencari zipkey.txt nya tinggal di cari manual pada kolom info
- setelah ketemu, klik kanan lalu pilih follow->tcp stream
- lalu akan tampil password nya

### Screenshot
![no 6](/img/Picture10.jpg)
![no 6.1](/img/Picture11.jpg)
![no 6.2](/img/Picture12.jpg)
![no 6.3](/img/Picture13.png)

## Soal 7

Ada 500 file zip yang disimpan ke FTP Server dengan nama 1.zip, 2.zip, ..., 500.zip. Salah satunya berisi pdf yang berisi puisi. Simpan dan Buka file pdf tersebut.

### Langkah Pengerjaan

- ketik syntax frame contains "Yes.pdf" pada kolom filter
- lalu klik kanan pada yang terpilih dan pilih follow->tcp stream
- lalu ganti Show and save data as nya menjadi Raw dan klik save
- lalu di save sebagai file Yes.zip
- setelah itu extrak file zip nya dan buka file Yes.pdf nya

### Screenshot

![no 7](/img/Picture14.jpg)
![no 7.1](/img/Picture15.jpg)
![no 7.2](/img/Picture16.jpg)
![no 7.3](/img/Picture17.jpg)
![no 7.4](/img/Picture18.jpg)

## Soal 8

Cari objek apa saja yang didownload (RETR) dari koneksi FTP dengan Microsoft FTP Service!

### Langkah Pengerjaan
- ketik syntax ftp.request.command == RETR pada kolom filter
- lalu klik kanan pada yang terpilih lalu pilih follow->tcp stream

### Screenshot

![no 8](/img/Picture19.jpg)
![no 8](/img/no%208.png)

## Soal 9
Cari username dan password ketika login FTP pada localhost!

- ketik syntax ftp.request.command == USER || ftp.request.command == PASS pada kolom filter
### Langkah Pengerjaan

### Screenshot

![no 9](/img/Picture20.jpg)

## Soal 10

Cari file .pdf di wireshark lalu download dan buka file tersebut!
clue: "25 50 44 46" 

- tekan ctrl + f
- lalu akan muncul kolom find, ganti display filter menjadi hex value lalu ketik 25 50 44 46 dan klik find
- lalu klik kanan pada yg terpilih dan pilih follow->tcp stream
- lalu ganti Show and save data as menjadi Raw dan klik save
- lalu save sebagai no 10.pdf
### Langkah Pengerjaan

### Screenshot

![no 10](/img/Picture21.jpg)
![no 10](/img/Picture22.png)
![no 10](/img/Picture23.png)

## Soal 11

Filter sehingga wireshark hanya mengambil paket yang mengandung port 21!

### Langkah Pengerjaan

- Jalankan ftp server pada local computer
- Login ke ftp dengan mengetikkan `ftp localhost` pada terminal
- Pilih **Adapter for loopback traffic capture**
- Masukkan `port 21` pada capture filter lalu tekan Enter

### Screenshot

![no 11](/img/Picture24.png)

## Soal 12

Filter sehingga wireshark hanya mengambil paket yang berasal dari port 80!

### Langkah Pengerjaan

- Pilih **Wi-Fi**
- Masukkan `src port 80` pada capture filter lalu tekan tombol Enter

### Screenshot

![no 12](/img/Picture25.jpg)
![no 12](/img/Picture26.jpg)

## Soal 13

Filter sehingga wireshark hanya menampilkan paket yang menuju port 443!

### Langkah Pengerjaan

- Pilih **Wi-Fi**
- Masukkan `dst port 443` pada capture filter lalu tekan tombol Enter

### Screenshot

![no 13](/img/Picture27.jpg)
![no 13](/img/Picture28.jpg)

## Soal 14

Filter sehingga wireshark hanya mengambil paket yang berasal dari ip kalian!

### Langkah Pengerjaan

- Ketikkan `ipconfig` pada cmd atau `ifconfig` pada terminal linux untuk mengetahui ip komputer kita. Misalnya `192.168.1.67`
- Buka Wireshark
- Pilih **Wi-Fi**
- Masukkan `src host 192.168.1.67` pada capture filter lalu tekan tombol Enter

### Screenshot

![no 10](/img/Picture29.jpg)

## Soal 15

Filter sehingga wireshark hanya mengambil paket yang tujuannya ke monta.if.its.ac.id!

### Langkah Pengerjaan

- lakukan Ping ke monta.if.its.ac.id melalui terminal untuk mendapatkan ip dari monta.if.its.ac.id. Didapatkan ipnya 103.94.190.11
- Buka Wireshark
- Pilih **Wi-Fi**
- Masukkan `dst host 103.94.190.11` pada capture filter lalu tekan tombol Enter
- Kunjungi monta.if.its.ac.id melalui browser hingga muncul paket-paket yang dikirimkan web browser ke monta.if.its.ac.id

### Screenshot

![no 10](/img/ping%20monta.png)
![no 10](/img/last.png)
