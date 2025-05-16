# Pendahuluan
Project ini bertujuan untuk membangun model machine learning yang mengklasifikasikan gambar jenis kucing. Klasifikasinya terhadap 2 label yaitu kucing Belang tiga dan Hitam. Model ini dilatih menggunakan dataset yang sudah tersedia di kaggle

# Dataset
dataset diambil dari kaggle, berikut link datasetnya:
https://www.kaggle.com/datasets/mibrahimhanif/jenis-kucing

# Model
Model yang digunakan yaitu CNN yang dibangun menggunakan library Tensorflow dan Keras.

# Hasil
Model yang telah dilatih mencapai akurasi 96.53% pada dataset testing. Hasil ini menunjukkan bahwa model bisa mengklasifikasi gambar jenis kucing dengan baik.

klasifikasi-gambar/
├── modeltfjs/
│   └── group1-shard1of37.bin dst
│   └── model.json
├── saved_model/
│   └── saved_model.pb
│   └── variables
├── tflite/
│   └── labels.txt
│   └── model.tflite
├── [Final] Submission Akhir Klasifikasi Gambar.ipynb
├── README.md
└── requirements.txt
