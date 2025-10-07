# UTS-DATAMINING

# Used Cars Price Prediction – Linear Regression
  ## Deskripsi Proyek
  Proyek ini merupakan bagian dari Ujian Tengah Semester (UTS) mata kuliah Data Mining .Tujuannya adalah memprediksi harga mobil bekas      menggunakan algoritma **Linear Regression** dengan dataset dari Kaggle. Dataset berisi berbagai informasi mengenai kendaraan seperti      tahun, kilometer tempuh, kapasitas mesin, tenaga, jenis bahan bakar, dan sebagainya.

  ## Dataset
  Sumber Dataset:
    * Kaggle: [Used Cars Price Prediction](https://www.kaggle.com/datasets)
    * GitHub Mirror: [FarrelllAdityaaa/dataset-uts-datamining](https://github.com/FarrelllAdityaaa/dataset-uts-datamining)
  Informasi Dataset:
    * Jumlah data: 6019 baris
    * Jumlah kolom: 25
    * Target: `Price`
  Beberapa fitur penting:
    * `Year`, `Kilometers_Driven`, `Mileage`, `Engine`, `Power`, `Seats`
    * `Location`, `Fuel_Type`, `Transmission`, `Owner_Type`

  ## Tahapan Pengerjaan

  1. Data Preprocessing
  Langkah-langkah yang dilakukan:
    * Profiling Data: Memeriksa tipe data dan nilai yang hilang (missing values).
    * EDA (Exploratory Data Analysis): Menganalisis distribusi dan korelasi antar fitur.
    * Data Cleaning: Menghapus nilai kosong dan outlier.
    * Transformasi Data: Mengubah data kategorikal menjadi numerik dengan *One-Hot Encoding*.
    * Hasil Akhir: Dataset bersih dan siap digunakan untuk pemodelan.
  2. Modelling
  Model yang digunakan: Linear Regression
  3. Evaluasi Model
  Metrik evaluasi yang digunakan:
    * R² (R-squared): 0.6930
    * MAE (Mean Absolute Error): 3.7981
    * MSE (Mean Squared Error): 37.7749
    * RMSE (Root Mean Squared Error): 6.1461
  4. Visualisasi hasil prediksi:

  ## Hasil dan Analisis
  * Nilai R² = 0.69 menunjukkan bahwa model mampu menjelaskan sekitar 69% variasi harga mobil bekas.
  * Sebagian besar titik prediksi berada di sekitar garis ideal, menandakan model cukup akurat.
  * Penyimpangan kecil masih terjadi karena kemungkinan:
    * Adanya hubungan non-linear antar fitur yang tidak tertangkap oleh model linear.
    * Adanya variabel penting yang belum disertakan, seperti kondisi fisik mobil atau faktor lokasi spesifik.

  ## Kesimpulan
  * Model Linear Regression cukup efektif untuk memprediksi harga mobil bekas.
  * Fitur yang paling berpengaruh antara lain Year, Engine, Power, dan Kilometers_Driven.
  * Nilai R² sebesar 0.69 menunjukkan performa model yang baik namun masih dapat ditingkatkan.
  * Untuk hasil yang lebih akurat, dapat dilakukan pengembangan dengan model lain seperti:
    * Random Forest Regressor
    * Gradient Boosting Regressor

## Tools dan Library

* Python 3.x
* pandas
* numpy
* matplotlib
* scikit-learn


## Pembuat

| Nama                       | NPM           | Peran                                   |
| -------------------------- | ------------- | --------------------------------------- |
| Salsa Anderia Putri Nabila | 2310631170151 | Data Preprocessing, Modelling, Evaluasi |
