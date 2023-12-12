# TASK 1
Create a new topic name `stock_topic_test`, then publish the stock streaming data to the newly created topic. In producer.py, line 20 change data with this : 

![Alt text](image.png) 


# ANS
Pertama Jalankan docker compose, pastikan semua container berjalan dengan baik

![Alt text](image-2.png)

![Alt text](image-1.png)

Ubah codingan python sesuai yang diminta

![Alt text](image-3.png)

Ubah juga file config.py agar sesuai dengan nama topic yang diminta

![Alt text](image-4.png)

Jalankan file task1.py dan lihat hasilnya melalui UI redpanda

![Alt text](image-6.png)

![Alt text](image-5.png)

![Alt text](image-7.png)

Sekarang publish data dengan menjalankan file python task1_consume.py

![Alt text](image-8.png)

# END

