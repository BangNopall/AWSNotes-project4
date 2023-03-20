<!-- Project Logo -->
<br/>
<div align="center">
    <img src="https://logos-world.net/wp-content/uploads/2021/08/Amazon-Web-Services-AWS-Logo.png" alt="Logo" width="100">
    <h3 align="center">School Project - AWS Project 4</h3>
     <p align="center">
        Rangkuman dan catatan ini dikhususkan untuk tugas AWS Project 4
    </p>
    <br />
</div>

# Tentang Project
<p align="center">
    Github repositori ini merupakan catatan, rangkuman, dan dokumen pada video tutorial berjudul <a href="https://www.youtube.com/watch?v=JmUMBKs3Y0c">Konfigurasi Load Balancing, Auto Scaling , Rsync EFS Di EC2 Amazon Web Services - AWS eps-4</a> dikembangkan oleh <a href="https://github.com/OmTegar/">OmTegar</a> yang dikhususkan untuk tugas sekolah AWS-Project 4. Kalian bisa simpan catatan ini untuk dijadikan referensi dan perkembangan ilmu di dunia Cloud Computing (AWS).
</p>

# Topologi Project
<div align="center">
<img src="images/topologi.png" alt="Logo" width="500">
</div>

Ini merupakan contoh topologi yang akan kita gunakan untuk praktek di dalam AWS Management Console.
Berikut beberapa service AWS yang kita butuhkan untuk praktek :

* **VPC**
* **AWS EC2**
* **EFS**
* **RDS**
* **AWS Auto Scaling**
* **Auto Balancing**

# Membuat VPC

Silahkan buka service VPC lali pilih `Create VPC`. Setelah itu silahkan buat VPC dengan contoh konfigurasi seperti dibawah ini :

* **Name**          : Project4
* **IP CIDR**       : 192.168.1.0/24
* **AZs**           : 2 (US-1a and US-1b)
* **Subnets**       : 2 (2 public and 2 private) 
* **NAT Gateways**  : 1 per AZ
* **VPC endpoints** : None

<div align="center">
<img src="images/vpc.png" alt="Logo">
</div>