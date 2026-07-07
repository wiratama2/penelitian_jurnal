# KLASIFIKASI PERGERAKAN HARGA SAHAM PT BUMI RESOURCES TBK MENGGUNAKAN DECISION TREE (J48) UNTUK MENDUKUNG INVESTASI
## Deskripsi
Repositori ini berisi dataset dan hasil analisis menggunakan WEKA.
## Perangkat Lunak
-WEKA 3.8
## Dataset
- dataset_BUMI.arff

## Hasil
- Hasil_Weka.txt
  
## Tahapan Penggunaan WEKA
1. Membuka aplikasi WEKA Explorer.
2. Memilih menu Preprocess, kemudian mengklik tombol Open File untuk membuka dataset `dataset_BUMI.arff`.
3. Menghapus atribut Tanggal (Date) karena tidak digunakan sebagai atribut prediksi dalam proses klasifikasi.
4. Memastikan atribut yang digunakan hanya atribut yang diperlukan, seperti Open, High, Low, Close, Volume, dan Label.
5. Memilih tab Classify.
6. Mengklik tombol Choose, kemudian memilih algoritma TREE (J48) .
7. Pada bagian Test Options, memilih metode Percentage Split sebesar 80%, sehingga 80% data digunakan sebagai data pelatihan (training) dan 20% sebagai data pengujian (testing).
8. Mengklik tombol More options, lalu pada bagian Output predictions memilih PlainText agar hasil prediksi setiap instance data uji ditampilkan pada Classifier Output.
9. Mengklik tombol Start untuk menjalankan proses klasifikasi.
10. Menunggu hingga proses klasifikasi selesai dan hasil ditampilkan pada bagian Classifier Output.
11. Menganalisis hasil evaluasi yang dihasilkan WEKA, seperti:
    - Correctly Classified Instances
    - Incorrectly Classified Instances
    - Kappa Statistic
    - Mean Absolute Error (MAE)
    - Root Mean Squared Error (RMSE)
    - Precision
    - Recall
    - F-Measure
    - ROC Area
    - Confusion Matrix

## Artikel Jurnal
Artikel lengkap dapat diakses pada:
**🔗 Link Jurnal:**  
[KLASIFIKASI PERGERAKAN HARGA SAHAM PT BUMI RESOURCES TBK MENGGUNAKAN DECISION TREE (J48) UNTUK MENDUKUNG INVESTASI](https://jurnal.mediaakademik.com/index.php/jma/article/view/7466)
https://jurnal.mediaakademik.com/index.php/jma/article/view/7466



