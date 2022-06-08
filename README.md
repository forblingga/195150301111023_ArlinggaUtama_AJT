**ARLINGGA UTAMA**

**195150301111023**

**TUGAS AKHIR ARSITEKTUR JARINGAN TERKINI**

**TUGAS 1 : Membuat Instances & Instalasi Mininet, Ryu, dan OpenFlow**

Membuat dan menginisialisasi instances pada AWS Academy dengan spesifikasi :

-Nama : Tugas Akhir

-OS Image : Ubuntu Server 22.04 LTS 64-bit

-Instance type : t2.medium

-Keypair : vockey

-Edit network settings : allow SSH, allow HTTP, allow HTTPS, allow TCP port 8080, allow TCP port 8081

-Konfigurasi penyimpanan : 30 GiB, gp3

![Screenshot_1](https://user-images.githubusercontent.com/99638079/172652069-d435a715-f11e-4cba-92a9-26ca1b13136e.png)
![Screenshot_2](https://user-images.githubusercontent.com/99638079/172652341-9c18f54d-a078-4d2b-b435-6485f4b05433.png)
![Screenshot_3](https://user-images.githubusercontent.com/99638079/172652356-c9f539db-55f9-49a5-ac40-66d8654527ab.png)
![Screenshot_4](https://user-images.githubusercontent.com/99638079/172652368-75dde250-c479-44f0-afdd-0479978303a2.png)
![Screenshot_5](https://user-images.githubusercontent.com/99638079/172652378-51892440-1d34-41fc-964a-402799ebb662.png)

Setelah VM dibuat akan ada akses key dengan link connect, lalu dimasukkan key ke vocareum labs dengan command "ssh -i .ssh/labsuser (key VM)". Setelah dijalankan akan ditanyakan untuk menambahkan VM baru dan mengetik "yes". Setelah itu akan memasuki VM tersebut

![Screenshot_6](https://user-images.githubusercontent.com/99638079/172653096-afe8401f-53d5-483f-80fc-d83408dab975.png)

Menginstall mininet, ryu, dan open flow

![Screenshot_7](https://user-images.githubusercontent.com/99638079/172653438-603b52ac-5b1a-4d55-a9da-202e50378b22.png)
![Screenshot_18](https://user-images.githubusercontent.com/99638079/172653465-b708f461-ed90-4c26-bf17-6c6356d61b4f.png)
![Screenshot_8](https://user-images.githubusercontent.com/99638079/172653524-93dac60d-fe17-47ba-b719-7c9afdd55e11.png)

Pada bagian Tugas 1 ini, saya membuat instances dengan nama Tugas Akhir dengan mengikuti ketentuan spesifikasi instances tersebut sesuai dengan yang ditugaskan, kemudian menginstalasi mininet, ryu, dan openflow.

**TUGAS 2 : Mininet Custom Topology**
Pada tugas 2 akan dibuat custom topology mininet dengan contoh 2 switch dan 2 host, tugas yang akan dibuat berupa 3 switch dan 6 host

![Screenshot_9](https://user-images.githubusercontent.com/99638079/172654613-7c6b891d-310e-47d7-b673-59964971e83d.png)

Jika dijalankan "sudo mn --controller=none, --custom test.py" maka akaan dibuat host dan switch yang sesuai di kode dan akan membuka terminal minine, kemduain host akan dihubungkan dari host ke hostmelalui switch tertentuyang kemudian akan dimasukkan ke terminal mininet.

![Screenshot_19](https://user-images.githubusercontent.com/99638079/172654885-c570b4a0-9e80-4d1e-8c77-0565bd3db61c.png)

Menjalankan ping pada host

![Screenshot_20](https://user-images.githubusercontent.com/99638079/172655269-96088338-ddca-4219-8aee-820bf802f616.png)

**TUGAS 3 : Tugas 3 - Ryu Load Balancer**
Pada tugas 3 akan dibuat load balancer. Load balancer dibuat untuk membagi beban traffic dalam suatu server sehingga akan tidak membebankan ke beberapa jalur koneksi, mempercepat respon dari server dan menghindari terjadinya overload. Dari pengamatan tugas akan menghasilkan sebagai berikut:

![Screenshot_13](https://user-images.githubusercontent.com/99638079/172655563-a075b75c-1535-4cca-b626-7d03fdb96598.png)
![Screenshot_10](https://user-images.githubusercontent.com/99638079/172655655-f893b59c-6f89-4722-9468-bb46ce5bd079.png)

Pada tugas 3 ini, sayak membuat sebuah load balancer, yang merupakan proses pembagian beban traffic pada sebuah aplikasi atau server. Dengan adanya load balancer, beban traffic tidak akan dibebankan ke beberapa jalur koneksi, sehingga keseluruhan pemrosesan menjadi lebih cepat dan efisien serta mencegahnya dari overloading.

**TUGAS 4 : Shortest Path Routing**

Pada tugas 4 akan menggunakan SPF Routing, merupakan pengaplikasian untuk menghitung jalur terpendek antara node menggunakan metode Open Shortest Path First.

![Screenshot_14](https://user-images.githubusercontent.com/99638079/172655923-27889403-d77e-430a-a7f2-916c46413127.png)
![Screenshot_17](https://user-images.githubusercontent.com/99638079/172656092-99645e95-b12b-4aec-90b2-706cae045ca8.png)
![Screenshot_19](https://user-images.githubusercontent.com/99638079/172656132-0d5615f3-6dea-4b6b-b04b-ad2ffe3ad292.png)
![Screenshot_20](https://user-images.githubusercontent.com/99638079/172656156-d07edf22-be21-4940-b2d1-39c8484582cb.png)

Pada tugas 4 ini, saya menganalisa cara pengaplikasian SPF Routing yang merupakan algoritma routing di mana router menghitung jalur terpendek antara setiap pasangan node yang terdapat di dalam jaringan. Protokol Open Shortest Path First (OSPF) dibuat berdasarkan algoritma Shortest Path First (SPF)
