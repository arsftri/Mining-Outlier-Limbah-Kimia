# Mining Outlier Limbah Kimia by TRI
Judul: Analisis Outlier Limbah Kimia Berbasis Jenis Bahan Berbahaya dan Metode Pengolahan terhadap Sepuluh Fasilitas Industri terbanyak di Amerika Serikat

## Latar Belakang
Pelepasan limbah bahan kimia oleh fasilitas industri merupakan isu krusial dalam perlindungan lingkungan, terutama di negara industri seperti Amerika Serikat. Melalui Toxics Release Inventory (TRI), pemerintah menyediakan data mengenai jenis, jumlah, dan metode pengolahan bahan kimia berbahaya yang dilepaskan ke lingkungan, termasuk zat karsinogenik, PBT, dan PFAS.

Namun, tidak semua pelepasan limbah mengikuti distribusi normal. Terdapat nilai ekstrem (outlier) yang menunjukkan pelepasan bahan kimia dalam jumlah tinggi, yang berpotensi mencerminkan risiko lingkungan signifikan atau ketidakefisienan pengolahan limbah.

Sehingga analisis outlier menjadi penting untuk mendeteksi outlier dari volume pelepasan bahan kimia berdasarkan data TRI, mengidentifikasi fasilitas dengan kontribusi pelepasan yang tidak biasa dan memberikan rekomendasi pengawasan atau mitigasi berdasarkan hasil analisis.

## Ruang Lingkup
1. Menggunakan data dari Toxics Release Inventory (TRI).
2. Fokus pada 10 fasilitas industri dengan jumlah pelepasan limbah tertinggi di Amerika Serikat.
3. Jenis bahan kimia berbahaya seperti karsionegik, PBT dan PFAS.
4. Jumlah pelepasan on site, offsite, total transfer, total releases hingga production waste.
5. Metode pengolahan limbah off-site treated total, recycling on site dan off site serta treatment on site dan off site.

## Roadmap
### Input Dataset
Dataset yang digunakan yaitu Toxics Releases Inventory (TRI) Basic Data Files Documentation Uodate for RY 2023 Agustus 2024

### Exploratory Data Analysis (EDA)
Eksplorasi data yang lakukan terdiri dari lima kategori yaitu
1. Eksplorasi Jumlah Baris dan Kolom
2. Ekplorasi Tipe Data
3. Eksplorasi Data Null
4. Eksplorasi Statistik Deskriptif
5. Eksplorasi Data Outlier

### Features Selection & Cleaning Data
Menghapus attribute yang tidak relevan terhadap judul penelitian (features selection) dengan pertimbangan attributenya bernilai null atau berupa ID (Tidak Memiliki Nilai Prediktif)

Alasan Nol dalam Data
1. fasilitas melaporkan NA atau tidak berlaku untuk suatu kuantitas pada formulir R (kuantitas pelepasan atau pengelolaan limbah tidak memungkingkan untuk fasilitas tersebut) contoh: fasilitas tidak terletak di dekat badan air, tidak dapat melepaskan bahan kimia apapun ke air
2. karena tidak menjawab pertanyaan kuantitas pada formulir R ketika masih pelaporan bentuk kertas
3. laporan fasilitas tidak melebihi 500 pound

### Visualisasi Data
Menggunakan beberapa chart untuk visualisasi, diantaranya:
1. Bar Plot Chart
2. Coloumn Bar Chart
3. Pie Chart
4. Scatter Plot Chart

## Insight
1. Sherwin-Williams CO merupakan fasilitas dengan jumlah terbanyak di sektor chemicals
2. TX merupkan wilayah terbanyak yang memilliki fasilitas di sektor chemicals
3. Clean Air Act Chemical dan Carcinogen bahan kimia terbanyak yang dimiliki 10 fasilitas chemical teratas
