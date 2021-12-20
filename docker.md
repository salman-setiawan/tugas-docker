1. Jelaskan apa yang dimaksud dengan container pada docker!
```
Container merupakan suatu wadah untuk mengemas dan menjalankan aplikasi. Wadah ini mencakup 
kode, runtime, system tools, dan pengaturan. Container hanya bisa mengakses resource yang telah
ditentukan dalam Docker image.
```
2. Jelaskan apa perbedaan antara konsep container dengan virtual machine!
``` 
VM memakan banyak resource dan waktu utk booting karena melakukan virtualisasi pada host hardware-nya.
Sedangkan container kebalikannya dari vm, container melakukan virtualisasi pada host OS-nya
```
3. Apa yang dimaksud dengan docker file ?
```
docker file merupakan suatu blueprint untuk membuat image
```
4. Apa yang dimaksud dengan docker registery ?
```
docker registry merupakan suatu tempat untuk mengupload/download image
```
5. Jelaskan bagaimana cara untuk menjalankan lebih dari 1 container secara bersamaan dan saling terhubung !
```
dengan menggunakan docker compose, caranya :
    - Buat file NAMA_FILE.yaml di dalam project yang kamu buat
    - Tulis beberapa perintah ke dalam sana
    - Jalankan menggunakan perintah docker-compose NAMA_FILE.yaml up
```

