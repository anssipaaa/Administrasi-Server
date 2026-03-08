# Membuat EC2/ Instance / VM

1. Pilih menu all services -> Pilih EC@
![Alt text](image.png)

2. Di dalamn EC2 kita pilih Instance
![Alt text](image-5.png)

![Alt text](image-6.png)

3. Beri nama Instance kita dengan NIM_Server
![Alt text](image-8.png)

4. Kita pilih OS server untuk instance kita
![Alt text](image-9.png)

5. Pilih resource instance T3.Micro (2VCPU, 1GB Memory)
![Alt text](image-10.png)

6. Membuat Key Pair, pilih new key pair, isi nama key, pilih RSA untuk enkripsi, format file.pem, create key pair
![Alt text](image-11.png)

7. setting kebijakan keamanan atau security group
- allow SSH = membolehkan remote SSH dari luar
- allow HTTPS = instance bisa diakses dari protokol HTTPS
- allow HTTP = instance bisa diakses dari protokol HTTP
![Alt text](image-12.png)

8. Pastikan launch instance kita sukses
![Alt text](image-13.png)