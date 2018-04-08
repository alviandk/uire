# Applikasi Uire
> Aplikasi peng-clusteran hasil input sirvey uire dengan algoritma [art] 

[art]: https://en.wikipedia.org/wiki/Algorithmic_art

## Instalasi
- clone repo ini ke komputer anda `git clone https://github.com/alviandk/uire.git`.
- masuk ke direktori projek dan install requirement yang diperlukan `pip install -r requirements.txt`.
- jalankan server dengan perintah `python manage.py runserver`
- buka pada browser http://localhost:8000/

## Petunjuk pemakaian untuk pengguna

Terdapat 3 fitur utama pada aplikasi ini:
- Isi Uire
- Generate Cluster
- Download Aplikasi XUL

![](img/main_menu.png)

- Isi Uire

Menu isi Uire untuk input data survey oleh pengguna. 
User memilih pilihan jawaban dari setiap pertanyaan, setelah 15 pertanyaan terisi pengguna melakukan submit.
Pengisian survey dapat dilakukan oleh banyak pengguna.
![](img/isi_uire.png)

- Generate Cluster

Setelah jumlah survey yang dilakukan pengguna cukup, bisa dilakukan penggenerasian cluster untuk mengetahui ada berapa 
kategori pengguna berdasarkan jawaban surveynya. Masukkan nilai limit koefisien tanimoto dengan range nilai antara 0 sampai 1.
Setelah itu tekan tombol `Generate` untuk menghasilkan cluster.
![](img/generate_cluster.png)

- Download Aplikasi XUL

Cluster yang sudah digenerate dapat di download file xul nya dan dijalankan dengan xulrunner untuk menghasilkan user interface
uire sesuai dengan kategori cluster tersebut.
![](img/download_xul.png)





