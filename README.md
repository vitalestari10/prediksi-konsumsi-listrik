# Prediksi Konsumsi Listrik Rumah Tangga dengan LSTM

Proyek ini menggunakan model LSTM (Long Short-Term Memory) untuk memprediksi konsumsi listrik rumah tangga harian berdasarkan fitur seperti suhu, kelembapan, dan jam penggunaan alat elektronik.

## Dataset
Dataset disimpan dalam file `listrik_rumah.csv` dan berisi data simulasi 100 hari konsumsi listrik.

## Arsitektur Model
Model menggunakan:
- LSTM dengan 64 unit
- Dense 32 unit (ReLU)
- Output Dense 1 unit (regresi)

## Cara Menjalankan

1. Install dependensi:
```bash
pip install pandas numpy matplotlib scikit-learn tensorflow
