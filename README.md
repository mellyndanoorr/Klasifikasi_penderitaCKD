# Klasifikasi_penderitaCKD
Tujuan klasifikasi
Memprediksi apakah seseorang memprediksi CKD( penyakit ginjal kronis) atau tidak CKD( tidak mengidap penyakit ginjal kronis atau sehat) berdasarkan data medis.

Membantu dokter atau tenaga medis untuk menemukan pasien yang berisiko tinggi sehingga bisa dilakukan tindakan lebih cepat.

Tujuan utama: mendeteksi CKD sedini mungkin, mengurangi risiko terlewatnya pasien (false negative) dan menjaga akurasi diagnosis.

Metode yang digunakan
Beberapa algoritma machine learning :

Naive Bayes → probabilistik, cocok untuk data tabular dan cepat.

Decision Tree → model berbasis aturan, mudah diinterpretasi.

KNN → berbasis jarak, sensitif pada skala data.

Random Forest → gabungan beberapa decision tree, lebih stabil dan kuat terhadap overfitting.

Temuan utama
Semua model menunjukkan akurasi tinggi (≥ 97%).

Naive Bayes unggul dalam mendeteksi semua kasus CKD (Recall = 1), sehingga tidak ada pasien CKD yang terlewat.

Decision Tree & Random Forest presisi sempurna (tidak salah menandai pasien sehat), tetapi ada sedikit kasus CKD yang terlewat.

KNN juga baik, balance antara recall dan precision, namun ada sedikit false positive.

Kesimpulan
Model ini bisa digunakan sebagai alat bantu skrining CKD.

Pemilihan model tergantung prioritas:

Naive Bayes / KNN → fokus menangkap semua pasien CKD.

Decision Tree / Random Forest → fokus mengurangi salah diagnosis pasien sehat.
