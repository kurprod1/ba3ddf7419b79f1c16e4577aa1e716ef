# Project : Spark, HDFS, & Airflow Integration

Saat ini, Anda adalah salah seorang data engineer freelance yang sedang mendapatkan pekerjaan dari salah satu agensi yang sedang menganalisa data video yang sempat trending di YouTube di beberapa negara. Anda diminta membuat suatu arsitektur big data dari dataset yang dimiliki, sehingga tim data analyst lebih mudah untuk mendapatkan data yang akurat.



Untuk mengerjakan project berikut, kalian akan diberikan beberapa requirement sebagai berikut:

- File dataset yang di provide dapat di akses di link berikut [Trending YouTube Video Statistics | Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new?select=CA_category_id.json)

- Pada data set tersebut, terdapat banyak tabel dan database. Disinilah tugas kalian untuk melakukan proses ETL dari dataset yang ada menggunakan Python dan Apache Spark.

- Transformasi yang dilakukan diantaranya:
  
  - Sorting
  
  - Remove duplicate data (if any)
  
  - Create aggregate data with category table

- Karena akan banyak proses yang dilakukan, untuk memperingan kinerja server, kalian diminta untuk menjadwalkan proses ETL diatas menggunakan Airflow, yang mana dilakukan setting setiap 15 menit sekali akan melakukan 1 task.

- Hasil dari proses diatas disimpan di HDFS. 
