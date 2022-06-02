# DevOps Engineer - DumbWays.id
DumbWays merupakan bootcamp DevOps gratis dan disalurkan kerja!

## Minggu ke 1
- instal ubuntu server menggunakan VMware  
- VMware Environment 
1. Disk : 10GB 
2. Memory : 2GB
3. Processors : 2 Cores
4. Network : NAT 
- Ubuntu Setting 
1. Bahasa : English
2. Network : Static
3. Storge : Custom Storge Layout
4. Username : gamaliel 
5. Password : ********
6. Server Name : gama
7. Open SSH : True
- instal aplikasi VMware kemudian pilih Create A New Virtual Machine
 ![Gambar](assets/Screenshot%20(212).png)
- setelah itu maka akan muncul gambar seperti dibawah ini, kita bisa memilih Use ISO Image. kemudian pilih browse, maka kita akan diarahkan ke folder penyimpanan file ubuntu server yang kita download. 
  ![Gambar](assets/Screenshot%20(214).png)
- setelah klik next, maka kalian bisa mengisi UserName dan Password yang kita inginkan. 
![Gambar](assets/Screenshot%20(215).png)
- langkah selanjutnya kita diminta untuk memilih lokasi penyimpanan mesin virtual kita
![Gambar](assets/Screenshot%20(216).png)
- pada tahap ini kita akan mengatur ukuran Disk yang aka digunakan. STORE DISK AS A SINGLE FILE artinya penyimpanan Disk akan dibuat menjadi satu file ( tidak disarankan untuk kapasitas kecil), SPLIT VIRTUAL DISK INTO MULTIPLE FILES penyimpanan Disk akan dibagi menjadi beberapa bagian. karena saya menggunakan Device berkapasitas kecil maka saya memilih SPLIT VIRTUAL DISK INTO MULTIPLE FILES
![Gambar](/assets/Screenshot%20(217).png)
- karena kita akan merubah setingan hardware untuk server, maka kita bisa memilih customize hardware, setelah muncul jendela baru kita akan mengcustom server sesuai yang kita inginkan. 
1. Memory bekerja untuk menyimpan data Virtual Machine
2. Processors bekerja untuk memproses data dan mengontrol system yang ada pada Virtual Machine
3. NetWork Adapter bekerja untuk menghubungkan komputer ke jaringan
4. NAT server mendapatkan IP dari Virtual Machine
5. Bridge mendapatkan IP dari internet yang kita pakai
![Gambar](assets/Screenshot%20(243).png)
- setelah selesai menseting bisa pilih close dan finish
- selanjutkan kita akan dibawa ke jendela instalsi, kita tunggu saja proses instalsi sampai selesai, setelah instalasi selesai maka akan ada tampilan pemilihan bahasa, pilih salah satu bahasa yang kita bisa 
![Gambar](assets/Screenshot%20(249).png)
- untuk kedua halaman dibawah ini kita bisa skip dengan pilih DONE
![Gambar](assets/Screenshot%20(250).png)
![Gambar](assets/Screenshot%20(251).png)
- selanjutnya kita merubah konfigurasi DHCP menjadi Static, caranya pilih bagian ens33 pada bagian IPV4 Method ubah dari otomatis ke manual
1. Subnet = istilah untuk membedakan host ID dan network ID
2. Alamat = IP yang digunakan untuk virtual Machine kita
3. Gateway = perangkan untuk mengkoneksikan komputer satu dengan yang lainnya
4. Name Server = cukup masukkan DNS dari google 
![Gambar](assets/Screenshot%20(288).png)
- setelah konfigurasi selesai maka DHCP akan berubah menjadi Static
![Gambar](assets/Screenshot%20(289).png)
- untuk tahap ini kita bisa memilih Custom storage layout, karena kita akan membuat 2 partisi baru, Done 
![Gambar](assets/Screenshot%20(254).png)
- selanjutnya kita akan membuat 2 partisi baru yaitu root dan swap. ROOT adalah tempat dimana sistem kita instal, sedangkan SWAP adalah cadangan memori yang digunakan untuk server kita. 
caranya adalah pilih bagian /dev/sda lalu pilih Add GPT Partition. 
![Gambar](assets/Screenshot%20(255).png)
![Gambar](assets/Screenshot%20(256).png)
- jika sudah selesai maka klik done 
![Gambar](assets/Screenshot%20(257).png)
- jika muncul popup seperti gambar dibawah ini kita bisa pilih continue saja 
![Gambar](assets/Screenshot%20(258).png)
- oke setelah semua sudah terseting maka kita akan dibawa ke halaman informasi untuk penamaan server kita 
![Gambar](assets/Screenshot%20(259).png)
- setelah itu kita pilih Install OpenSSH server yang bertujuan untuk meremote server kita.
![Gambar](assets/Screenshot%20(262).png)
- tahap ini bisa skip atau klik done
![Gambar](assets/Screenshot%20(263).png)
- selanjutnya kita sudah sampai tahap penginstalan, kita tunggu saja proses penginstalan sampai seleai hingga muncul pilihan rebot now.
![Gambar](assets/Screenshot%20(264).png)
![Gambar](assets/Screenshot%20(265).png)
- tahap instalasi sudah selesai, maka akan ada perintah untuk memasukkan ID dan Password yang sudah kita seting sebelumnya.
![Gambar](assets/Screenshot%20(267).png)
- untuk memastikan apakah server kita terhubung dengan internet, maka kita bisa ketik perintah ping google.com atau ping google.com
![Gambar](assets/Screenshot%20(292).png)


## Minggu ke 2
- Setup git & Ssh key
- Setup database & Deploy aplikasi backend
- [Baca lebih lanjut](week-2/README.md)

## Minggu ke 3
- Setup docker & Membuat custom docker image
- Setup CI/CD & Notifikasi]
- [Baca lebih lanjut](week-3/README.md)

## Minggu ke 4
- Setup monitoring
- Setup ansible & Membuat ansible playbook untuk konfigurasi server
- [Baca lebih lanjut](week-4/README.md)

## Additional
- Setup container orchestration
- Setup microservices application
- [Baca lebih lanjut](week-1/README.md)

## Final
- Final examination
- [Baca lebih lanjut](final/README.md)