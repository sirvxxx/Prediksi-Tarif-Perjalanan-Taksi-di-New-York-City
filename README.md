# Prediksi Tarif Perjalanan Taksi di New York City

Praktikum Machine Learning: memprediksi tarif perjalanan taksi (`fare`)
di New York City menggunakan model regresi.

## Dataset
NYC Taxi Trips (sampel Maret 2019), 6.433 baris dan 14 kolom.
File: `dataset_nyc_taxi_2019.csv`

## Tahapan
1. Data Collecting
2. Data Loading
3. Data Cleaning dan Transformation
4. EDA dan ExDA
5. Data Splitting (80% train, 20% test)
6. Modelling (Linear Regression, Decision Tree, Random Forest)

## Hasil
Linear Regression adalah model terbaik dengan R² data uji 0,9281.

## Cara Menjalankan
pip install pandas numpy matplotlib seaborn scikit-learn requests
Lalu buka `praktikum_ml_nyc_taxi.ipynb` dan jalankan semua cell.
