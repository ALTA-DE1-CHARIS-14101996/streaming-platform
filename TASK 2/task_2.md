# TASK 2
Create new table with name `cdc_table ` then doing insert, update, and delete operation.

# ANS

Pertama kita jalankan postgres di terminal untuk memastikan wal level agar wal level nya logical

Jika `Replica` lakukan convert agar berubah menjadi logical

![Alt text](image.png)

`Logical`

![Alt text](image-1.png)

Jalankan Konektor postgres

![Alt text](image-2.png)

Buat table db postgres dengan nama sesuai dengan perintah soal dan lakukan input data, delete, dan update. Kemudian buka redpanda dan lihat pada topic postgres.public.cdc_table untuk melihat history perubahan yang terjadi

`Input`

![Alt text](image-3.png)

![Alt text](image-6.png)

`Update`

![Alt text](image-4.png)

![Alt text](image-7.png)

`Delete`

![Alt text](image-5.png)

![Alt text](image-8.png)

# END







