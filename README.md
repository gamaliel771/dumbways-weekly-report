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
 ![Gambar](week-1/assets/Screenshot%20(212).png)
- setelah itu maka akan muncul gambar seperti dibawah ini, kita bisa memilih Use ISO Image. kemudian pilih browse, maka kita akan diarahkan ke folder penyimpanan file ubuntu server yang kita download. 
  ![Gambar](week-1/assets/Screenshot%20(214).png)
- setelah klik next, maka kalian bisa mengisi UserName dan Password yang kita inginkan. 
![Gambar](week-1/assets/Screenshot%20(215).png)
- langkah selanjutnya kita diminta untuk memilih lokasi penyimpanan mesin virtual kita
![Gambar](week-1/assets/Screenshot%20(216).png)
- pada tahap ini kita akan mengatur ukuran Disk yang aka digunakan. STORE DISK AS A SINGLE FILE artinya penyimpanan Disk akan dibuat menjadi satu file ( tidak disarankan untuk kapasitas kecil), SPLIT VIRTUAL DISK INTO MULTIPLE FILES penyimpanan Disk akan dibagi menjadi beberapa bagian. karena saya menggunakan Device berkapasitas kecil maka saya memilih SPLIT VIRTUAL DISK INTO MULTIPLE FILES
![Gambar](week-1/assets/Screenshot%20(217).png)
- karena kita akan merubah setingan hardware untuk server, maka kita bisa memilih customize hardware, setelah muncul jendela baru kita akan mengcustom server sesuai yang kita inginkan. 
1. Memory bekerja untuk menyimpan data Virtual Machine
2. Processors bekerja untuk memproses data dan mengontrol system yang ada pada Virtual Machine
3. NetWork Adapter bekerja untuk menghubungkan komputer ke jaringan
4. NAT server mendapatkan IP dari Virtual Machine
5. Bridge mendapatkan IP dari internet yang kita pakai
![Gambar](week-1/assets/Screenshot%20(243).png)
- setelah selesai menseting bisa pilih close dan finish
- selanjutkan kita akan dibawa ke jendela instalsi, kita tunggu saja proses instalsi sampai selesai, setelah instalasi selesai maka akan ada tampilan pemilihan bahasa, pilih salah satu bahasa yang kita bisa 
![Gambar](week-1/assets/Screenshot%20(249).png)
- untuk kedua halaman dibawah ini kita bisa skip dengan pilih DONE
![Gambar](week-1/assets/Screenshot%20(250).png)
![Gambar](week-1/assets/Screenshot%20(251).png)
- selanjutnya kita merubah konfigurasi DHCP menjadi Static, caranya pilih bagian ens33 pada bagian IPV4 Method ubah dari otomatis ke manual
1. Subnet = istilah untuk membedakan host ID dan network ID
2. Alamat = IP yang digunakan untuk virtual Machine kita
3. Gateway = perangkan untuk mengkoneksikan komputer satu dengan yang lainnya
4. Name Server = cukup masukkan DNS dari google 
![Gambar](week-1/assets/Screenshot%20(252).png)
- setelah konfigurasi selesai maka DHCP akan berubah menjadi Static
![Gambar](week-1/assets/Screenshot%20(253).png)
- 


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