# Submission-Klasifikasi-Gambar
Proyek ini merupakan implementasi model klasifikasi gambar sampah menggunakan arsitektur MobileNetV2. Model ini dilatih untuk mengenali berbagai jenis sampah seperti paper, glass, cardboard, metal, plastic, trash, dan lainnya. Dataset berasal dari folder Google Drive yang telah diklasifikasikan berdasarkan label folder.

Dataset dapat diakses pada link berikut ini: https://www.kaggle.com/datasets/mostafaabla/garbage-classification

## 1. File Structures
```
.
├── saved_model
│   └── garbage_classifier
│       ├── assets
│       ├── variables
│       │   ├── variables.data-00000-of-00001
│       │   └── variables.index
│       ├── fingerprint.pb
│       └── saved_model.pb
    └── garbage_classifier.keras
├── tfjs_model
│   ├── model.json
│   ├── group1-shard1of3.bin
│   ├── group1-shard2of3.bin
│   ├── group1-shard3of3.bin
└── tflite
│       ├── model.tflite
│       └── label.txt
├── klasifikasi_gambar_garbage_final.py
├── klasifikasi_gambar_garbage_final.ipnyb
├── README.md
└── requirements.txt
```
