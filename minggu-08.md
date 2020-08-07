# Teknologi Cloud Computing 
### Minggu08


## Docker Compose
Docker-compose adalah sebuah alat dari docker yang digunakan untuk mendefinisikan dan menjalankan aplikasi multi kontainer. Dengan docker-compose kita bisa menjalankan kontainer 1 dengan yang lainya dengan 1 perintah . Docker-compose juga menggunakan yaml file untuk menyimpan konfigurasi dari service yang dibuat.

Dengan docker compose kita bisa menyimpan konfigurasi dalam file, berarti semua perubahan dependency service, seperti versi database dan service lain dapat dimasukkan dalam VCS (Version Control System). Dengan VCS kita dapat lebih mudah men-debug jika terjadi error pada software.


## Docker Network
Untuk dapat terhubung dengan Docker Container lainnya Docker mengunakan Network untuk dapat terhubung, sama halnya dengan komputer agar bisa terhubung satu dengan komputer lainnya komputer memerlukan network begitu pula Docker konsepnya sama dengan network pada komputer tetapi network pada docker berbeda layernya :D

Seperti penjelesan diatas Docker container masing2 mempunyai IP, IP ini adalah alamat untuk menghubungi kontainer yang lain agar dapat berkomunikasi

Network pada Docker antara lain

Bridge
Host
Overlay
Macvlan