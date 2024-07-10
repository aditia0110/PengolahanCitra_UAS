# Klusterisasi Gambar menggunakan KMeans
#### Nama  : Aditia Seftiawan
#### Nim   : 312210094
#### Kelas : TI.22.B1

Kali ini kita akan klusterisasi sebuah foto atau gambar dengan algoritma KMeans.

sebelumnya kita berkenalan terlebih dahulu dengan KMeans

K-Means adalah salah satu algoritma clustering yang paling populer dalam analisis data. Tujuannya adalah untuk mengelompokkan data ke dalam k kelompok berdasarkan atribut yang mirip. Algoritma ini bekerja dengan cara mengiterasi antara dua langkah utama:

Assign: Mengatribusikan setiap titik data ke kelompok yang paling dekat dengannya berdasarkan nilai rata-rata (centroid) kelompok tersebut.

Update: Memperbarui posisi centroid untuk setiap kelompok dengan menghitung nilai rata-rata dari semua titik data yang telah diatribusikan ke kelompok tersebut.

Iterasi ini terus berlanjut hingga tidak ada perubahan signifikan dalam atribusi titik data ke kelompok atau posisi centroid. K-Means biasanya digunakan untuk analisis cluster di mana jumlah kelompok (k) telah ditentukan sebelumnya.


Pada script `kmean.py` akan menjalankan klusterisasi dalam beberapa kali tergantung
apa yang kita masukan pada bagian
`k = 7`

Untuk menjalankan program pastikan anda sudah menginstall library yang dibutuhkan sebagai berikut :
`pip install opencv-python numpy matplotlip scikit-learn`

setelah itu untuk merunning silahkan ketik `python kmean.py`

nanti akan muncul gambar original lalu anda bisa close untuk menampilkan iterasi gambar yang sudah terclusterisasi waktu tunggu sekitar 1 menit untuk proses cluterisasi setelah anda close gambar yang pertama

Berikut Foto original sebelum diklusterisasi


![labuan](https://github.com/aditia0110/PengolahanCitra_UAS/assets/115475348/f5d98c6b-abcb-466e-8d9a-06e654eb49be)



Berikut hasil foto yang sudah mengalami perubahan sebanyak 7 kali ini bergantung pada script ` k =`

### Segmented image

![segmented](https://github.com/aditia0110/PengolahanCitra_UAS/assets/115475348/7925d1d2-6c27-4b2e-8d4e-c3bc05f47493)


### Cluster1 image

![cluster1](https://github.com/aditia0110/PengolahanCitra_UAS/assets/115475348/7fa0cd87-8512-44b3-969e-ae332af5f655)


### Cluster_2 image

![cluster2](https://github.com/aditia0110/PengolahanCitra_UAS/assets/115475348/0a84ff8f-18a6-4285-94ff-0c331fd41012)


### Cluster_3 image

![cluster3](https://github.com/aditia0110/PengolahanCitra_UAS/assets/115475348/76a14fd8-9a97-47cc-b3c2-1d0af6e704a2)


### Cluster_4 image

![cluster4](https://github.com/aditia0110/PengolahanCitra_UAS/assets/115475348/5e34c70d-e152-4e56-baa4-5213203dc4dd)


### Cluster_5 image

![cluster5](https://github.com/aditia0110/PengolahanCitra_UAS/assets/115475348/4aa53448-abda-4190-a842-7d6450220065)


### Cluster_6 image

![cluster6](https://github.com/aditia0110/PengolahanCitra_UAS/assets/115475348/20584dc6-4c5a-42a8-8d8b-f51fded7d381)


### Cluster_7 image

![cluster7](https://github.com/aditia0110/PengolahanCitra_UAS/assets/115475348/97f0b3ff-5e1c-4989-833f-1163e2df353f)


Untuk melakukan clusterisasi membutuhkan waktu untuk prosesnya jadi untuk memunculkan hasilnya butuh waktu sekitar 1 menit atau lebih ini bergantung kepada kapasitas device kita. semaking tinggi spesifikasi device semakin cepat dia dalam memprosesnya.


Selesai untuk nilai K  anda bisa memasukan sesuai keinginan anda.

Selamat mencoba, semoga bermanfaat

#### Link Tugas UTS pengolahan Citra

Hasil Streamlit :
[https://adamwebdev.streamlit.app/tugas](https://adamwebdev.streamlit.app/tugas)




