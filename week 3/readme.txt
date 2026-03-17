Machine Learning Project – Week 3
Data Exploration & Feature Engineering

Project ini isinya tentang proses eksplorasi data dan feature engineering sebelum masuk ke tahap Machine Learning Modeling.
Fokusnya di sini lebih ke bersihin dan nyiapin data dulu, biar nanti pas dipakai buat model hasilnya lebih bagus dan gak berantakan.

Overview Project
Di Week 3 ini ada beberapa hal yang dikerjain, di antaranya:
-Mengecek isi dataset (exploration)
-Visualisasi data (biar lebih gampang dipahami)
-Nyari outlier
-Handle missing value
-Encoding data kategorikal
-Nyiapin dataset sebelum modeling
Semua proses ini dikerjain pakai Python di Google Colab

Dataset yang Dipakai
- Project ini pakai beberapa dataset buat latihan preprocessing.

1. California Housing Dataset

Dipakai buat analisis distribusi data dan nyari outlier.

File:
california_dataset.csv

Kolom yang dianalisis:

MedInc
HouseAge
AveRooms
AveBedrms
AveOccup


Yang dilakukan:

Visualisasi pakai histogram
Deteksi outlier pakai boxplot
Ngeliat pola dan karakteristik data

2. Company Dataset

Dataset ini fokus ke missing value.
File:
company.csv

Yang dilakukan:

Hitung jumlah data kosong
Hitung persentasenya
Nentuin perlu dihapus atau enggak
Isi missing value pakai metode yang sesuai

3. Telco Customer Churn Dataset

Dipakai buat encoding data kategorikal jadi numerik.

File:
TelcoCustomerChurn.csv
TelcoCustomerChurn.xlsx

Yang dilakukan:

Ubah data kategori jadi angka
Bersihin kategori yang gak konsisten
Terapin beberapa teknik encoding

Contoh:
Yes → 1
No → 0

Kolom yang diproses:

StreamingMovies
StreamingTV
TechSupport
DeviceProtection
OnlineBackup
OnlineSecurity
MultipleLines
Data Preparation

Beberapa step penting yang dilakukan:

1. Data Splitting
Dataset dibagi jadi:
Training Data (80%)
Testing Data (20%)

Tujuannya biar model bisa dites pakai data baru yang belum pernah dilihat.

2. Data Cleaning

Yang dilakukan di tahap ini:

Benerin data kategori yang gak konsisten
Contoh:
"No internet service" → "No"
Hapus atau perbaiki data yang aneh / gak valid

3. Feature Encoding

Teknik yang dipakai:

One Hot Encoding
Buat data kategori yang gak punya urutan.
Label Encoding

Buat data simpel kayak:
Yes / No

Jadi:
Yes = 1
No = 0

Tools yang Dipakai

Python

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Struktur Repository

Machine-Learning/
│
└── WEEK3
├── Assignment_Week 3.ipynb
├── Hands On_Week_3_Feature_Engineering.ipynb
├── california_dataset.csv
├── company.csv
├── TelcoCustomerChurn.csv
├── TelcoCustomerChurn.xlsx
└── titanic.xlsx

Hasil Project

Dari project ini, dataset udah berhasil diproses jadi lebih siap dipakai:

Data jadi lebih rapi
Data kategori udah jadi numerik
Outlier udah bisa ke-detect
Missing value udah ditangani

Jadi tinggal lanjut ke tahap Machine Learning Modeling.
