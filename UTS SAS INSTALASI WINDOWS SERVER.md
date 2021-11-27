# UTS SISTEM ADMINISTRASI SERVER

M. Pradata Yuda P	

1202190061

IT-02-02

### INSTALASI WINDOWS SERVER 2022

![image](https://user-images.githubusercontent.com/92876637/143674187-8ce0a349-9352-4d73-9b62-5c8243428f0d.png)

1. Download ISO Windows Sever 2022 di Website Resmi Microsoft

![image](https://user-images.githubusercontent.com/92876637/143674195-6e18440b-5e6b-496d-8fe1-5adc7bfe36fa.png)

2. Buka VirtualBox > New > Beri nama Virtual Machine

![image](https://user-images.githubusercontent.com/92876637/143674235-95ec64db-fcb0-47b1-8224-5472d732df6a.png)
![image](https://user-images.githubusercontent.com/92876637/143674241-aec0bf0f-7166-4fbf-8a0c-4fffa4fd05c4.png)
![image](https://user-images.githubusercontent.com/92876637/143674244-1305e566-58a5-43a1-b192-5f6f8df6e843.png)
![image](https://user-images.githubusercontent.com/92876637/143674246-266332a2-bdff-4345-9de7-a804b55d8215.png)

3. Klik Next ikuti langkah instalasinya dan pilih memory yang akan digunakan nantinya

  ![image](https://user-images.githubusercontent.com/92876637/143674255-5c96e246-3578-4c40-840a-23ce11ac5972.png)

4. Ubah Network ke Bridge Adapter 

  ![image](https://user-images.githubusercontent.com/92876637/143674262-4654be5e-4b51-4d38-bed8-b949f42410b4.png)

5. Masukkan file iso

  ![image](https://user-images.githubusercontent.com/92876637/143674270-719da5d2-b413-4a4e-9af5-f803ff4de258.png)

6. Ubah setelan lokasi ke Indonesia

  ![image](https://user-images.githubusercontent.com/92876637/143674273-f2a85ed4-a725-467c-896a-e020fd27fbbd.png)

7. Klik Install now

![image](https://user-images.githubusercontent.com/92876637/143674281-b9651810-49cb-4c2b-a3ae-faa598d1ad1f.png)

8. Pilih Windows Server Standard Evaluation (Destop Experience)

  ![image](https://user-images.githubusercontent.com/92876637/143674290-65946774-3fec-415d-bfb7-1019a7d07cbe.png)

9. Custom Memory > Kemudian klik Next dan tunggu proses instalasi selesai

  ![image](https://user-images.githubusercontent.com/92876637/143674304-dffd5c30-d8dd-4fab-bbd5-b56c90e98923.png)
10. Windows Server berhasil di install





### INSTALASI ACTIVE DIRECTORY DOMAIN SERVICES

![image](https://user-images.githubusercontent.com/92876637/143674345-1275fbe2-7321-4e2b-96fd-f0e594bc8830.png)

1. Buka Control Panel > Network and Internet

  ![image](https://user-images.githubusercontent.com/92876637/143674348-1006514b-c0fd-47e4-9565-cc186b070661.png)

2. Klik Network and Sharing Center

  ![image](https://user-images.githubusercontent.com/92876637/143674356-8054067d-6c53-4b43-9f9c-a9621343e70b.png)

3. Klik Change adapter settings

4. Menuju ke Ethernet Properties

   ![image](https://user-images.githubusercontent.com/92876637/143674364-54a74fca-d0df-4b38-ac76-9b3a163506fb.png)

5. Centang Internet Protokol Version 4(TCP/IPv4)

  ![image](https://user-images.githubusercontent.com/92876637/143674369-ae71146d-dfe8-4e3e-894e-4893490e33af.png)

6. Konfigurasi IP address seperti diatas

 ![image](https://user-images.githubusercontent.com/92876637/143674374-b83ec95e-16d7-4f9e-ba83-a7cafdaea2e2.png)

7. Masuk ke Server Manager, Refresh Dashboard

  ![image](https://user-images.githubusercontent.com/92876637/143674375-5abddb69-d861-472c-b2ff-1560161afb19.png)

8. Pilih Add Roles and Features

![image](https://user-images.githubusercontent.com/92876637/143674378-176083a8-c1cb-470a-904c-64e4a92055fe.png)

 ![image](https://user-images.githubusercontent.com/92876637/143674383-54952e86-6593-45d0-9052-530a22e6ece2.png)

9. Klik Next mengikuti gambar

   ![image](https://user-images.githubusercontent.com/92876637/143674387-234d8bc1-8607-47a1-99da-f20b35921124.png)

10. Centang Active Directory Domain Services

   ![image](https://user-images.githubusercontent.com/92876637/143674390-7b2768c8-cb2e-4075-90f9-dbb91019ec69.png)

11. Klik Add Features > Klik Next

   ![image](https://user-images.githubusercontent.com/92876637/143674395-5d1a5e06-53a3-43e3-80ce-49c4731b77a9.png)

12. Centang pilihan Restart > Klik Yes > Install

   ![image](https://user-images.githubusercontent.com/92876637/143674397-825d584c-7083-4a42-b583-e7399568006c.png)

13. Tunggu proses instalasi selesai

   ![image](https://user-images.githubusercontent.com/92876637/143674403-4dbccedd-7cbe-487c-8a0b-0dafc1ec0f13.png)

14. Setelah berhasil install masuk ke Active Directory Domain Services Configuration Wizard

   ![image](https://user-images.githubusercontent.com/92876637/143674409-204ed57c-be53-49f4-8a71-ded9328d1e51.png)

15. Add a new forest > Masukkan nama domain > Next

 ![image](https://user-images.githubusercontent.com/92876637/143674411-2d2dbaa1-4952-4c6a-a04c-6703043dfafe.png)

16. Buat pasword untuk (DSRM)

    ![image](https://user-images.githubusercontent.com/92876637/143674415-fa91b3c9-a43c-44ee-b975-b87554b41458.png)

17. Next

   ![image](https://user-images.githubusercontent.com/92876637/143674421-00ee6aec-b24d-4522-9164-53b8c94a9c3a.png)

18. Pastikan nama sudah benar > Next
![image](https://user-images.githubusercontent.com/92876637/143674425-f147c46e-c4f6-421a-bfb0-5a9c3c21b50c.png)

19. Jika tidak ada yang dirubah Next

  ![image](https://user-images.githubusercontent.com/92876637/143674427-697ce9e1-c791-4cf1-8bcc-3071f70f6730.png)

20. Ada tanda centang hijau diatas menandakan bahwa ADDS sudah bisa diinstall > Install

    ![image](https://user-images.githubusercontent.com/92876637/143674431-95231c56-470c-4f14-9946-11235f87794a.png)
![image](https://user-images.githubusercontent.com/92876637/143674432-f9f63854-b182-4e42-940d-979fcec63558.png)

21. Tunggu proses restart

    ![image](https://user-images.githubusercontent.com/92876637/143674436-7a583009-9f51-4dee-b80b-23a41f3daed9.png)

22. Setelah reboot masuk lagi ke Server Manager > Tools > Cek Active Directory sudah terinstal

   ![image](https://user-images.githubusercontent.com/92876637/143674439-1649b5b6-ce0d-42e6-a362-b82836df0a38.png)

23. Masuk ke cmd untuk mengecek ping apakah berhasil

![image](https://user-images.githubusercontent.com/92876637/143674442-5413a6ab-da0c-4c60-b556-c4bdae10d0b1.png)

24. Berhasil ping ke sas.local



### INSTALASI DNS SERVER

![image](https://user-images.githubusercontent.com/92876637/143674452-cb89e11b-d9b0-41b5-b71e-3dd3f0b53806.png)

1. Masuk ke Server Manager > Add Roles and Features Wizard
![image](https://user-images.githubusercontent.com/92876637/143674456-8948df28-70c5-4062-9d3c-3fe87e6c6a33.png)

2. Klik Next
![image](https://user-images.githubusercontent.com/92876637/143674460-fb9d87b4-7932-4191-8436-8b095f9c5f5a.png)

3. Next 

4. Next

5. Setelah melakukan instalasi Active Domain Services

6. Akan diarahkan ke Menu Domain Controller

7. Centang DNS server

![image](https://user-images.githubusercontent.com/92876637/143674475-dbdba821-cd7c-4f9b-9434-c65284741643.png)

8. Pastikan DNS Server : Yes

9. Klik Next dan tunggu proses instalasi

10. Cek pada menu Add Roles and Features

    ![image](https://user-images.githubusercontent.com/92876637/143674489-35fc0e18-b8ac-4979-a617-2c4f54115454.png)
![image](https://user-images.githubusercontent.com/92876637/143674495-6c30dd81-c5e0-4ebf-a23e-94771913c363.png)

11. DNS Server (Installed)





### INSTALASI NET FRAMEWORK 3.5

![image](https://user-images.githubusercontent.com/92876637/143674507-4383f278-484a-4f0d-af36-efd7f511ef0b.png)

1. Masuk ke Add Role and Features 

   ![image](https://user-images.githubusercontent.com/92876637/143674513-8fbb3d4f-efc5-48be-9609-af7bf9f7aa60.png)

2. Next sampai ke menu Features

3. Pilih Net Framework 3.5 Features

  ![image](https://user-images.githubusercontent.com/92876637/143674518-eec67ce1-49d6-4a0c-ab2a-a5969b8238eb.png)

4. Klik Specify an alternate source path

![image](https://user-images.githubusercontent.com/92876637/143674521-286ddf20-c115-4c0d-97e6-75afb26b89e4.png)

5. Masukan alamat D:\sources\sxs > OK

  ![image](https://user-images.githubusercontent.com/92876637/143674530-42213f22-fc87-461e-9e60-83e1d37789aa.png)

6. Tunggu proses instalasi

![image](https://user-images.githubusercontent.com/92876637/143674531-f97df513-2159-477d-b7a9-d288f8fc5b38.png)

7. Instalasi berhasil > Close



### PROMOTE SERVER TO DOMAIN CONTROLLER

![image](https://user-images.githubusercontent.com/92876637/143674538-022c5d0a-1b09-4859-ae07-4a52d1527753.png)

1. Setelah melakukan proses installasi ADS maka ada tulisan **promote this server to a domain controller** > maka dengan mengklik menu tersebut prosesya sudah selesai

