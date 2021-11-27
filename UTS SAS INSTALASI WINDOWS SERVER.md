# UTS SISTEM ADMINISTRASI SERVER

M. Pradata Yuda P	

1202190061

IT-02-02

### INSTALASI WINDOWS SERVER 2022

![](D:\UTS SAS\INSTALASI\1.png)

1. Download ISO Windows Sever 2022 di Website Resmi Microsoft

![](D:\UTS SAS\INSTALASI\2.png)

2. Buka VirtualBox kemudian masukkan file ISO

   ![](D:\UTS SAS\INSTALASI\3.png)

   ![](D:\UTS SAS\INSTALASI\4.png)

   

   ![](D:\UTS SAS\INSTALASI\6.png)

3. Klik Next ikuti langkah instalasinya dan pilih memory yang akan digunakan nantinya

   ![](D:\UTS SAS\INSTALASI\7.png)

4. Ubah Network ke Bridge Adapter 

   ![](D:\UTS SAS\INSTALASI\9.png)

5. Masukkan file iso

   ![](D:\UTS SAS\INSTALASI\10.png)

6. Ubah setelan lokasi ke Indonesia

   ![](D:\UTS SAS\INSTALASI\11.png)

7. Klik Install

8. Pilih Windows Server Standard Evaluation (Destop Experience)

   ![](D:\UTS SAS\INSTALASI\12.png)

   ![](D:\UTS SAS\INSTALASI\13.png)

   ![](E:\yahaloo.png)

   9. Custom Memory > Kemudian klik Next dan tunggu proses instalasi selesai

   ![](D:\UTS SAS\DNS\Instalasi windows server berhasil.png)

10. Windows Server berhasil di install





### INSTALASI ACTIVE DIRECTORY DOMAIN SERVICES

![](D:\UTS SAS\Active Directory\1.png)

1. Buka Control Panel > Network and Internet

   ![](D:\UTS SAS\Active Directory\2.png)

2. Klik Network and Sharing Center

   ![](D:\UTS SAS\Active Directory\3.png)

3. Klik Change adapter settings

4. Menuju ke Ethernet Properties

   ![](D:\UTS SAS\Active Directory\4.png)

5. Centang Internet Protokol Version 4(TCP/IPv4)

   ![](D:\UTS SAS\Active Directory\5.png)

6. Konfigurasi IP address seperti diatas

   ![](D:\UTS SAS\Active Directory\6.png)

7. Masuk ke Server Manager, Refresh Dashboard

   ![](D:\UTS SAS\Active Directory\7.png)

8. Pilih Add Roles and Features

   ![](D:\UTS SAS\Active Directory\8.png)

   ![](D:\UTS SAS\Active Directory\9.png)

9. Klik Next mengikuti gambar

   ![](D:\UTS SAS\Active Directory\10.png)

10. Centang Active Directory Domain Services

    ![](D:\UTS SAS\Active Directory\11.png)

11. Klik Add Features > Klik Next

    ![](D:\UTS SAS\Active Directory\12.png)

12. Centang pilihan Restart > Klik Yes > Install

    ![](D:\UTS SAS\Active Directory\13.png)

13. Tunggu proses instalasi selesai

    ![](D:\UTS SAS\Active Directory\14.png)

14. Setelah berhasil install masuk ke Active Directory Domain Services Configuration Wizard

    ![](D:\UTS SAS\Active Directory\14.png)

15. Add a new forest > Masukkan nama domain > Next

    ![](D:\UTS SAS\Active Directory\15.png)

16. Buat pasword untuk (DSRM)

    ![](D:\UTS SAS\Active Directory\16.png)

17. Next

    ![](D:\UTS SAS\Active Directory\18.png)

18. Pastikan nama sudah benar > Next

    ![](D:\UTS SAS\Active Directory\19.png)

19. Jika tidak ada yang dirubah Next

    ![](D:\UTS SAS\Active Directory\20.png)

20. Ada tanda centang hijau diatas menandakan bahwa ADDS sudah bisa diinstall > Install

    ![](D:\UTS SAS\Active Directory\21.png)

    ![](D:\UTS SAS\Active Directory\22.png)

21. Tunggu proses restart

    ![](D:\UTS SAS\Active Directory\sudah selesai reboot terinstall.png)

22. Setelah reboot masuk lagi ke Server Manager > Tools > Cek Active Directory sudah terinstal

    ![](D:\UTS SAS\Active Directory\buka cmd.png)

23. Masuk ke cmd untuk mengecek ping apakah berhasil

    ![](D:\UTS SAS\Active Directory\ping berhasil.png)

24. Berhasil ping ke sas.local



### INSTALASI DNS SERVER

![](D:\UTS SAS\DNS\1.png)

1. Masuk ke Server Manager > Add Roles and Features Wizard

   ![](D:\UTS SAS\DNS\2.png)

2. Klik Next

   ![](D:\UTS SAS\DNS\3.png)

3. Next 

4. Next

5. Setelah melakukan instalasi Active Domain Services

6. Akan diarahkan ke Menu Domain Controller

7. Centang DNS server

8. ![](D:\UTS SAS\Active Directory\15.png)

9. Pastikan DNS Server : Yes

10. Klik Next dan tunggu proses instalasi

11. Cek pada menu Add Roles and Features

    ![](D:\UTS SAS\DNS\DNS berhasil 1.png)

    ![](D:\UTS SAS\DNS\DNS berhasil.png)

1. DNS Server (Installed)





### INSTALASI NET FRAMEWORK 3.5

![](D:\UTS SAS\DNS\1.png)

1. Masuk ke Add Role and Features 

   ![](D:\UTS SAS\DNS\bukti framework.png)

2. Next sampai ke menu Features

3. Pilih Net Framework 3.5 Features

   ![](D:\UTS SAS\DNS\install framework 3.5.png)

4. Klik Specify an alternate source path

   ![](D:\UTS SAS\DNS\Instalasi framwlkork.png)

5. Masukan alamat D:\sources\sxs > OK

   ![](D:\UTS SAS\DNS\proses instalasi framework.png)

6. Tunggu proses instalasi

   ![](D:\UTS SAS\DNS\framework sukses.png)

7. Instalasi berhasil > Close



### PROMOTE SERVER TO DOMAIN CONTROLLER

![](D:\UTS SAS\Active Directory\promote server to domain.png)

1. Setelah melakukan proses installasi ADS maka ada tulisan **promote this server to a domain controller** > maka dengan mengklik menu tersebut prosesya sudah selesai

