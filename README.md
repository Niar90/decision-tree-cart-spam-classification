# Email Spam Classification using Decision Tree (CART)

## Deskripsi Proyek
Proyek ini bertujuan untuk membangun model klasifikasi email spam dan non-spam
menggunakan algoritma Decision Tree dengan metode CART (Classification and Regression Trees).
Model dikembangkan untuk memahami pola email spam secara interpretable dan transparan.

## Dataset
Dataset yang digunakan adalah Spambase Dataset dari UCI Machine Learning Repository.
Dataset ini terdiri dari:
- 4.601 data email
- 57 fitur numerik
- 1 label target (spam / non-spam)

Fitur mencakup frekuensi kata, karakter khusus, dan pola huruf kapital.

## Metodologi
Tahapan yang dilakukan dalam proyek ini meliputi:
1. Pemuatan dan eksplorasi dataset
2. Pembagian data menjadi data latih dan data uji
3. Pembangunan model Decision Tree CART (criterion: Gini)
4. Hyperparameter tuning menggunakan GridSearchCV
5. Pruning pohon keputusan menggunakan parameter `ccp_alpha`
6. Evaluasi model menggunakan accuracy, confusion matrix, precision, recall, dan F1-score
7. Visualisasi pohon keputusan dan analisis feature importance

## Evaluasi Model
Model dievaluasi menggunakan beberapa metrik untuk memastikan performa klasifikasi,
khususnya dalam mendeteksi email spam:
- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score

## Hasil Singkat
Model menunjukkan performa yang baik dengan akurasi di atas 90%.
Penerapan pruning dengan alfa 0,01 meningkatkan interpretabilitas pohon keputusan,
namun terdapat trade-off berupa penurunan akurasi.

## Tools & Library
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

## Catatan
Proyek ini dikembangkan sebagai bagian dari laporan progres akademik pada mata kuliah Kecerdasan Artifisial di program studi Sains Data (Universitas Negeri Surabaya)
dan dapat dikembangkan lebih lanjut untuk sistem filter spam otomatis.

