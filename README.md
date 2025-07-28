# ANALISIS PREDIKSI SAHAM MENGGUNAKAN ALGORITMA TCN STRATEGI TRADING
#### Proyek ini bertujuan untuk mengevaluasi algoritma TCN dalam memprediksi dan menghasilkan sinyal trading saham PT ANTM. Model TCN dibandingkan secara terbatas dengan algoritma deep learning lain menggunakan metrik akurasi dan kinerja trading melalui simulasi backtesting studi dibatasi pada data historis harian ANTM dengan fokus utama pada analisis TCN.
## FITUR UTAMA
1. Prediksi harga saham PT ANTM menggunakan algoritma TCN 
2. Evaluasi akurasi Model menggunakan metrik RMSE, MAE dan R2
3. Pengelompokan sinyal trading (Buy/Hold/Sell) berdasarkan hasil produksi
4. Simulasi strategi trading melalui backtesting dengan metrik total return, sharpe ratio, dan max drawdown
5. Perbandingan awal dengan algoritma deeplearning lain (LSTM, GRU, dsb)
## STRUKTUR PROYEK
Time-Series-Analysis/

├── README.md

├── requirements.txt

├── data/

│ └── ANTM.csv

├── Prediksi_Harga_Saham.ipynb

├── results/

│ └── hasil_visualisasi.png
## DATASET
1. Sumber Data : Yahoo Finance (diunduh dari yfinance)
2. Kode Saham : ANTM.JK (PT Aneka Tambang Tbk
3. Periode Data : Februari 2005 - Oktober 2024
4. Fitur Utama : Open-High-Low-Close-Volume
5. Target Prediksi :Harga close untuk prediksi numerik dan sinyal trading (Buy, Hold, Sell) untuk strategi investasi
## LISENSI
Proyek ini dilisensikan di bawah MIT License — silakan digunakan, dimodifikasi, atau dikembangkan secara bebas dengan mencantumkan atribusi.
