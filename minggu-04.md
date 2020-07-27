# Infrastructure as a Service dan SDN
### Minggu04 

Iaas adalah layanan infrastruktur memberikan kendali penuh bagi pengguna untuk melakukan penambahan atau pengurangan resources. Selain itu, pengguna dapat dengan bebas menginstall aplikasi-aplikasi dalam VM yang dibuat.

Secara topologi pun IaaS dapat dibuat sesuai dengan kebutuhan seperti topologi network atau juga penggunaan VPN,layanan cloud yang sudah berupa bundling perangkat hardware yang berupa virtualisasi, jaringan internet, bandwitch, network dan ip publik, termasuk storage.

Cloud provider menyediakan berbagai spesifikasi seperti CPU, RAM, dan Storage dalam bentuk virtualisasi. Karena dari sisi cloud provider memiliki high-end server yang mereka bagi-bagi menjadi beberapa virtualisasi, ketika cloud provider memiliki storage 2TB dengan teknologi virtualisasi yang mereka gunakan dapat membagi menjadi 40GBx50 unit komputer virtualisasi yang bisa di gunakan oleh pengguna jadi provider cloud dapat memanfaatkan virtual virtualisasi untuk membagi storage yang besar menjadi lebih kecil dan banyak.

Elemen terpenting pada sistem cloud (sistem virtual) dimana hardware di kelola secara virtual (Virtual Machine) seperti CPU, Memory, Network, dan Storage. Masing-masing penyedia IaaS memiliki cara yang berbeda dalam menyajikan layanan tersebut ke pelanggan. Berikut elemen yang secara umum di gunakan:

* User authentication
* Hypervisor
* Virtual Network
* Storage Imaging
* Block Storage
* Swift
* Dashboard

Pelanggan dapat memesan perangkat yang dibutuhkan sesuai kapasitas melalui menu login dashboard, kemudian permintaan tersebut diteruskan oleh sistem “messaging broker” untuk berkomunikasi pada sistem virtual penyedia IaaS.

Ketika pelanggan mengeluarkan permintaan atas sebuah Virtual Machine, Hypervisor melaksanakan perintah tersebut sesuai spesifikasi CPU dan Ram yang diminta oleh pelanggan dan permintaan ruang penyimpanan dihandle oleh Block Storage. Seluruh perintah tersebut akan di cluster sebagai reserved oleh pelanggan pada sistem infrastruktur di data center.

## Fitur dan kelebihan IaaS

##### Test and Development
kita dapat melakukan testting aplikasi sebelum di upload ke production server , dengan Iaas kita  dapat melakukan testing dengan cepat untuk dappat di uji dengan fitur scale up dev-test semua bisa di lakukan dengan cepat dan mudah.
##### Webiste Hossting
Sebagai layanan Iaas tentunya kita dapat menjadikanya sebagai server webhosting yang lebih fleksibel dan hemat biaya.