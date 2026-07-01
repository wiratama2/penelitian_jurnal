# Penelitian-jurnal-prediksi-pergerakan-saham-bumi-menggunakan-naive-bayes
# Prediksi Pergerakan Saham BUMI Menggunakan Naive Bayes

## Deskripsi
Repositori ini berisi dataset dan hasil analisis menggunakan WEKA.

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
6. Mengklik tombol Choose, kemudian memilih algoritma Bayes → NaiveBayes.
7. Pada bagian Test Options, memilih metode Percentage Split sebesar 80%, sehingga 80% data digunakan sebagai data pelatihan (training) dan 20% sebagai data pengujian (testing).
8. Mengklik tombol Start untuk menjalankan proses klasifikasi.
9. Menunggu hingga proses klasifikasi selesai dan hasil ditampilkan pada bagian Classifier Output.
10. Menganalisis hasil evaluasi yang dihasilkan WEKA, seperti:
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
[Prediksi Pergerakan Harga Saham PT Bumi Resources Tbk Menggunakan Naive Bayes untuk Meminimalisir Risiko](https://journal.cib.institute/index.php/kohesi/article/view/651)

