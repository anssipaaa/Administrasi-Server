#Remote Instance with SSH putty

1. pastikan sudah install putty (putty.org/index.html) 
![Alt text](image-14.png)

2. Konversi file public key dari .pem menjadi .ppk di putty
- buka puttyGen
- load file.pem
- save as .ppk
![Alt text](image-15.png)

3. SetUp putty untuk remote SSH
- buka apps putty
- isi IP publik sesuai instance masing-masing
- isi form untuk SSH sesuai Security Group di Instance
- isi nama session agar saat konek lagi tinggal load saja
- load file .ppk (klik SSH -> pilih auth -> credentials -> load file .ppk)
- kembali ke session klik save
- masukkan username ubuntu
![Alt text](image-16.png)

![Alt text](image-17.png)

4. sudo apt-get Update (Update OS) sudo apt-det upgrade
![Alt text](image-18.png)

5. Pembuktian remote SSH secara visual -copy publik IP address instance paste ke browser
- isntall web server apache/nginx
- sudo apt install apache2 -y
![Alt text](image-19.png)

![Alt text](image-20.png)

6. matikan instance agar tidak kena tagihan
![Alt text](image-21.png)