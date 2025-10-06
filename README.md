# KecerdasanBuatan-25
## Posttest 2
### Kesimpulan Analisis
- Dataset memiliki 1303 record dengan 13 atribut, di mana 3 atribut bertipe numerik dan sisanya bertipe kategorikal/objek.
- Distribusi harga laptop menunjukkan mayoritas laptop berada pada kisaran harga **500–1500 Euro**, dengan beberapa outlier laptop premium di atas 3000 Euro.
- <img width="1187" height="548" alt="image" src="https://github.com/user-attachments/assets/4ba5546f-6cfb-487e-8c77-da3ea1b5bd29" />
- <img width="695" height="548" alt="image" src="https://github.com/user-attachments/assets/fe23c2a6-bc35-4460-99b7-95d4b2f01b34" />
- Heatmap korelasi memperlihatkan bahwa atribut `Inches` tidak berkorelasi kuat dengan `Price_euros`, sehingga ukuran layar bukan faktor utama dalam menentukan harga. Dan attribute numeriik tidak saling terhubung atau berkorelasi.
- <img width="486" height="374" alt="image" src="https://github.com/user-attachments/assets/cfff9833-e9e2-4fcb-b360-cb870fd6a100" />
- Variasi harga laptop lebih banyak dipengaruhi oleh spesifikasi lain seperti CPU, GPU, RAM, dan tipe penyimpanan.
## Posttest 3
- Handling missing values, handling duplicate value tidak dilakukan karena tidak adanya record yang kosong dan duplikat
- Handling outliers saya lakukan 3 kali menggunakan metode IQR untuk mendapatkan data paling bersih tanpa outliers seperti yang ditampilkan
- Melakukan encoding pada kolom kategorikal seperti Company, TypeName, Opsys menjadi format numerik agar bisa diproses model ML
- Normalisasi numerik agar memiliki rentang yang seragam
- Feature engineering berupa kategorisasi agar lebih mudah diinterpretasikan
- Melakukan split dan menghasilkan 1042 untuk data training dan 261 untuk data test
