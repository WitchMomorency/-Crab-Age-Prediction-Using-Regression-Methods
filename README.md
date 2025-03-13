# -Crab-Age-Prediction-Using-Regression-Methods
# Budidaya Kepiting: Peluang Bisnis yang Menjanjikan

**Kepiting** merupakan salah satu komoditas makanan laut yang digemari di berbagai negara di dunia. Permintaan yang tinggi terhadap kepiting menjadikannya sebagai peluang bisnis yang menjanjikan, terutama bagi masyarakat di wilayah pesisir. **Bisnis budidaya kepiting** memiliki sejumlah keunggulan, seperti:
- **Biaya tenaga kerja yang rendah**
- **Biaya produksi yang relatif murah**
- **Tingkat pertumbuhan kepiting yang cepat**

Dengan pengelolaan dan perawatan yang baik, **budidaya kepiting** dapat memberikan keuntungan yang lebih besar dibandingkan budidaya udang. Sistem budidaya kepiting dapat dilakukan melalui dua metode utama, yaitu:
1. **Grow-out farming**
2. **Sistem penggemukan (fattening system)**

## Pentingnya Mengetahui Usia Kepiting

Mengetahui usia kepiting yang tepat menjadi hal yang penting bagi petani komersial untuk menentukan waktu panen. Setelah mencapai usia tertentu, **pertumbuhan fisik kepiting** cenderung tidak signifikan. Oleh karena itu, pengambilan keputusan waktu panen yang tepat dapat:
- Menekan biaya
- Meningkatkan keuntungan

**Analisis data** terkait usia dan karakteristik fisik kepiting menjadi salah satu langkah penting untuk mendukung hal tersebut.

## Pemaparan Data

Dataset yang digunakan dalam analisis ini bertujuan untuk **memperkirakan usia kepiting** berdasarkan atribut fisiknya. Dataset ini menyediakan landasan awal untuk:
1. **Analisis Data Eksploratif**  
   Memahami bagaimana berbagai karakteristik fisik kepiting berubah seiring dengan bertambahnya usia.
2. **Rekayasa Fitur**  
   Mendefinisikan fitur baru dengan mengombinasikan data yang ada untuk meningkatkan akurasi model.
3. **Model Regresi**  
   Membuat model regresi yang dapat memprediksi usia kepiting berdasarkan atribut fisiknya.

**Dataset ini memberikan peluang besar** untuk mendalami penerapan analisis regresi dan rekayasa fitur, terutama untuk meningkatkan efisiensi dan produktivitas dalam budidaya kepiting secara komersial.

## Temuan Eksperimen

- Algoritma yang paling sesuai untuk model ini adalah **Linear Regression**.  
  Walaupun pada tahap testing performanya relatif buruk dibanding algoritma lainnya, algoritma ini memiliki performa terbaik saat testing.
- **Random Forest Regression** menunjukkan performa terbaik pada tahap training. Namun, pada tahap testing, algoritma ini mengalami penurunan performa yang mengindikasikan potensi overfitting.

## Evaluasi dan Peningkatan Model

- **MAE** dan **MSE** tidak dapat dijadikan matriks yang konkrit karena hasil model merupakan normalisasi, bukan tipe data integer.
- **R² Score** dipilih sebagai acuan evaluasi performa model.
- Model ini dapat ditingkatkan dengan menerapkan **Feature Engineering** dan **Hyperparameter Tuning** untuk prediksi yang lebih akurat.  
  Namun, secara dasar, model ini sudah cukup handal dalam melakukan prediksi usia kepiting.
