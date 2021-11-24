M. Pradata Yuda P	

1202190061

IT-02-02



UTS SISTEM ADMINISTRASI SERVER

INSTALASI WINDOWS SERVER 2022

1. Download ISO Windows Sever 2022 di Website Resmi Microsoft



2. Buka VirtualBox kemudian masukkan file ISO
3. Klik Next ikuti langkah instalasinya dan pilih memory yang akan digunakan nantinya
4. Ubah Network ke Bridge Adapter 
5. Ubah setelan lokasi ke Indonesia
6. Klik Install
7. Pilih Windows Server Standard Evaluation (Destop Experience)
8. Custom memory
9. Kemudian klik Next dan tunggu prose instalasi selesai
10. Windows Server berhasil di install





INSTALASI ACTIVE DIRECTORY DOMAIN SERVICES

1. Buka Control Panel > Network and Internet
2. Klik Network and Sharing Center
3. Klik Change adapter settings
4. Menuju ke Ethernet Properties
5. Centang Internet Protokol Version 4(TCP/IPv4)
6. Konfigurasi IP address seperti diatas
7. Masuk ke Server Manager, Refresh Dashboard
8. Pilih Add Roles and Features
9. Klik Next mengikuti gambar
10. Centang Active Directory Domain Services
11. Klik Add Features > Klik Next
12. Centang pilihan Restart > Klik Yes
13. Tunggu proses instalasi selesai
14. Setelah berhasil install masuk ke Active Directory Domain Services Configuration Wizard
15. Add a new forest > Masukkan nama domain > Next
16. Buat pasword untuk (DSRM)
17. Next
18. Pastikan nama sudah benar > Next
19. Jika tidak ada yang dirubah Next
20. Ada tanda centang hijau diatas menandakan bahwa ADDS sudah bisa diinstall > Install
21. Tunggu proses restart
22. Setelah reboot masuk lagi ke Server Manager > Tools > Cek Active Directory sudah terinstal
23. Masuk ke cmd untuk mengecek ping apakah berhasil
24. Berhasil ping ke sas.local



INSTALASI DNS SERVER

1. 





INSTALASI NET FRAMEWORK 3.5

1. Masuk ke Add Role and Features 
2. Next sampai ke menu Features
3. Pilih Net Framework 3.5 Features
4. Klik Specify an alternate source path
5. Masukan alamat D:\sources\sxs > OK
6. Tunggu proses instalasi
7. Instalasi berhasil > Close



PROMOTE SERVER TO DOMAIN CONTROLLER

1. Setelah melakukan proses installasi ADS maka ada tulisan promote this server to a domain controller > maka dengan itu prosesya sudah selesai