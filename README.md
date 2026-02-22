# Used-Motorcycle-Price-Analysis
Data-driven pricing analysis on used motorcycle sales to estimate fair market prices based on year, mileage, and ownership. Evaluated profit vs loss distribution and identified key price drivers through statistical analysis, delivering insights and interactive Tableau dashboards to support optimal pricing decisions.
Used Motorcycle Price Analysis

# Repository Outline

1. README.md – Penjelasan gambaran umum project

2. P0M1_Kevin_Hibatul.ipynb – Notebook berisi data cleaning, eksplorasi data, statistika deskriptif & inferensial, serta visualisasi

3. BikeDetails.csv – Dataset mentah (raw data)

4. BikeDetails_data_clean.csv – Dataset yang telah dibersihkan dan diproses

# Problem Background

Sebagai Data Analyst pada bisnis dealer motor bekas, saya ingin menganalisis faktor-faktor yang memengaruhi harga jual motor serta mengevaluasi potensi keuntungan atau kerugian dari setiap unit.
Penentuan harga yang tidak berbasis data berisiko menyebabkan kerugian atau hilangnya potensi profit. Oleh karena itu, analisis ini dilakukan untuk membantu menentukan harga jual yang lebih optimal dan konsisten.

# Project Output

Output dari proyek ini adalah:

Notebook analisis lengkap dengan eksplorasi dan visualisasi data

Dataset yang sudah dibersihkan

Perhitungan harga wajar berdasarkan data historis (median per tahun & kepemilikan)

Analisis distribusi profit (Untung, Rugi, Netral)

Dashboard interaktif Tableau untuk mendukung pengambilan keputusan harga

# Data

Dataset berisi informasi penjualan motor bekas, termasuk:

Tahun produksi

Harga jual (selling_price)

Jarak tempuh (km_driven)

Status kepemilikan (owner)

Dan atribut lainnya

Dataset terdiri dari beberapa kolom numerik dan kategorikal yang digunakan untuk menganalisis pola harga dan potensi profit.

# Method
1. Data Cleaning

Menghapus missing values dan duplikasi

Menyesuaikan tipe data

Feature engineering (motor_age, harga_wajar, profit_margin, profit_status)

2. Statistika Deskriptif

Analisis distribusi harga

Perbandingan harga berdasarkan tahun & kepemilikan

Distribusi potensi keuntungan dan kerugian

3. Statistika Inferensial

Uji korelasi Spearman untuk melihat hubungan antara:

Tahun motor dan harga jual

Jarak tempuh dan harga jual

Usia motor dan harga jual

4. Visualisasi Data

Scatter plot (Harga Jual vs Harga Wajar)

Bar chart distribusi profit

Line chart tren harga per tahun

Heatmap korelasi

Key Findings

Tahun kendaraan memiliki korelasi positif kuat terhadap harga jual.

Jarak tempuh dan usia motor memiliki korelasi negatif terhadap harga.

Sekitar 44% unit berpotensi dijual rugi, menunjukkan perlunya optimasi strategi pricing.

Harga wajar berbasis median historis membantu meningkatkan konsistensi harga.

# Stacks

Bahasa Pemrograman:
Python

Library:

pandas & numpy → manipulasi dan pengolahan data

matplotlib & seaborn → visualisasi data

scipy → uji korelasi statistik

Visualization Tool:

Tableau Public

# Reference

Dataset: Bike Details (Used Motorcycle Dataset) From Kaggle
