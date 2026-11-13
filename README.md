# Klasifikasi dengan Naive Bayes - UTS Penambangan Data

**Nama:** Helmi Ulinnuha

**NIM:** F12.2025.00230

## Deskripsi
Tugas klasifikasi menggunakan algoritma Gaussian Naive Bayes pada dataset Iris
(150 data, 3 kelas: setosa, versicolor, virginica).

## Langkah
1. Memuat dataset Iris dari scikit-learn
2. Memisahkan fitur (X) dan target (y)
3. Membagi data latih dan uji 80:20 (stratifikasi, random_state = 42)
4. Standardisasi fitur dengan StandardScaler
5. Melatih model GaussianNB
6. Evaluasi: confusion matrix, akurasi, dan classification report

## Hasil
- Akurasi: 96,67%
- Kelas setosa diprediksi sempurna; satu data versicolor tertukar dengan virginica.

## Berkas
- `.ipynb`: notebook Google Colab (kode dan hasil)
- `.pdf`: cetakan notebook
