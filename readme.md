# Praktikum Modul 1 20 September 2021

## Anggota Kelompok E13
05111940000090	Ihsannur Rahman Qalbi
05111940000003	Fairuz Hasna Rofifah
05111940000164	Ahmad Aunul Ma`bud

## 1. Sebutkan webserver yang digunakan pada "ichimarumaru.tech"!

## 2. Temukan paket dari web-web yang menggunakan basic authentication method!

## 3. Ikuti perintah di basic.ichimarumaru.tech! Username dan password bisa didapatkan dari file .pcapng!
## 4. Temukan paket mysql yang mengandung perintah query select!
## 5. Login ke portal.ichimarumaru.tech kemudian ikuti perintahnya! Username dan password bisa didapat dari query insert pada table users dari file .pcap!
## 6. Cari username dan password ketika melakukan login ke FTP Server!
## 7. Ada 500 file zip yang disimpan ke FTP Server dengan nama 0.zip, 1.zip, 2.zip, ..., 499.zip. Simpan dan Buka file pdf tersebut. (Hint = nama pdf-nya "Real.pdf")
## 8. Cari paket yang menunjukan pengambilan file dari FTP tersebut!
## 9. Dari paket-paket yang menuju FTP terdapat inidkasi penyimpanan beberapa file. Salah satunya adalah sebuah file berisi data rahasia dengan nama "secret.zip". Simpan dan buka file tersebut!
## 10. Selain itu terdapat "history.txt" yang kemungkinan berisi history bash server tersebut! Gunakan isi dari "history.txt" untuk menemukan password untuk membuka file rahasia yang ada di "secret.zip"!
## 11. Filter sehingga wireshark hanya mengambil paket yang berasal dari port 80!
a.  Menggunakan `src port 80` pada capture filter
![11a](https://image.prntscr.com/image/cHvNUb_ORc-fdr2SAhEjIg.png)
b.  Membuka [monta.if.its.ac.id](monta.if.its.ac.id) untuk mendapatkan packet yang berasal dari port 80
![11b](https://image.prntscr.com/image/50QLTsFIQSyDQwUN4LIjoA.png)

## 12. Filter sehingga wireshark hanya mengambil paket yang mengandung port 21!
a.  Menggunakan `port 20` pada capture filter
![12a](https://image.prntscr.com/image/hScRihDZRIaNd1F95DrMug.png)
b.  Membuka (ftp://ftp.adobe.com)[ftp://ftp.adobe.com] untuk mendapatkan packet yang mengandung port 20
![12b](https://image.prntscr.com/image/jToS3jsMStCdU67A_sh2Lg.png)
## 13. Filter sehingga wireshark hanya menampilkan paket yang menuju port 443!
## 14. Filter sehingga wireshark hanya mengambil paket yang tujuannya ke kemenag.go.id!
## 15. Filter sehingga wireshark hanya mengambil paket yang berasal dari ip kalian!