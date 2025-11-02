# Capstone-Hacktiv8
JUDUL: Analisis & Prediksi Harga Saham BBCA (BBCA.JK) dengan Indikator Sederhana
RAW DATASET: https://finance.yahoo.com/quote/BBCA.JK
PROJECT OVERVIEW: Proyek ini menganalisis harga harian BBCA.JK dari Yahoo Finance untuk mengevaluasi apakah indikator teknikal sederhana—SMA5, SMA20, RSI14—dapat meningkatkan prediksi arah harga besok dibanding baseline. Data diambil langsung via yfinance, dibersihkan, lalu dieksplorasi (tren, volatilitas rolling 21 hari) dan dimodelkan dengan Logistic Regression memakai TimeSeriesSplit. Kami mengukur akurasi serta peluang naik bersyarat (mis. saat SMA5>SMA20 & RSI14∈[40,60]) dengan/ tanpa filter volatilitas ≤ P80. Hasilnya dirangkum sebagai insight praktis dan rekomendasi sederhana (bukan nasihat investasi).
