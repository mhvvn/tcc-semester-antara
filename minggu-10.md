Kubernetes adalah aplikasi cluster management open source. Aplikasi ini berasal dari aplikasi internal yang digunakan Google (Borg) untuk mengelola cluster mereka sendiri, platform open-source ini berbasis Linux yang dirancang untuk mengotomatisasi penempatan, penskalaan, dan manajemen aplikasi yang berada dalam kontainer. Dengan Kubernetes, kita dapat dengan cepat dan efisien menanggapi permintaan user

## Fitur Kubernetes

* Automatic Binpacking
otomatis menempatkan kontainer berdasarkan kebutuhan sumber daya yang dibutuhkan dan tidak mengobarkan ketersedian resource. mengabungkan kritikal dan beban kerja terbaik untuk meningkatkan pemanfaatan dan menghemat lebih banyak sumber daya.

* Horizontal Scaling
melakukan scale up dan down aplikasi mengunakan perintah sederhana, dengan UI, atau dengan otomatis berdasarkan pengunaan cpu.

* Self-healing
merestart container yang gagal, menggantikan dan menjadwalkan ulang container saat node worker mati. mematikan container yang tidak merespon pemeriksaan kesehatan yang dibuat oleh penguna, dan tidak mengadvertise  container ke klien hingga siap untuk digunakan.

* Service discovery and load balancing
tidak diperlukan memodifikasi aplikasi untuk menggunakan mekanisme service discovery yang tidak dikenal. kubernetes memberikan alamat ip pada container dan memberikan single DNS untuk sekumpulan container dan dapat load balance diantara container.

* Secret and configuration management
Deploy dan update secret dan konfigurasi aplikasi tanpa rebuild image anda tanpa memberitahukan secret dalam stack konfigurasi.

* Storage orchestration
Secara otomatis akan mounting ke sistem penyimpanan yang sudah dipilih, baik penyimpanan local, public cloud storage seperti GCP atau AWS dan network storage seperti NFS, iSCSI, Gluster, Ceph, Cinder atau Flocker.


## Komponen Kubernetes

* Master Components

Komponen Master menyediakan cluster control plane. komponen master berfungsi untuk mengatur penjadwalan, memulai pembuatan pod dengan replicate. berikut komponen master :
1. kube-apiserver
2. etcd
3. kube-scheduler
4. kube-controller-manager
5. cloud-controller-manager
6. Node Componentes

* komponen node jalan pada setiap node / worker, menjaga pod yang berjalan dan menyediakan runtime untuk kubernetes. berikuti komponen node
1. kubelet
2. kube-proxy
3. container runtime
   
* Addons
Addons adalah pod dan layanan yang mengimplementasikan fitur cluster. Pod dapat dikelola oleh Deployment, ReplicationControllers, dan sebagainya. beirkut adalah bagian dari addons.
1. DNS
2. Web UI (Dashboard)
3. Container Resource Monitoring
4. Cluster Level Logging