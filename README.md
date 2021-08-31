# Metrik Evaluasi pada Klasifikasi Multikelas  

Klasifikasi multikelas memiliki sedikit perbedaan dengan klasifikasi binari, terutama dalam cara intepretasi _Confusion Matrix_ dan metrik evaluasi lainnya.  
Di _repository_ ini, saya akan mencoba menjelaskan tentang cara membaca _Confusion Matrix_ dan bagaimana membuat metrik evaluasi custom menggunakan `make_scorer` dari *library* sklean.  

Dataset yang digunakan dalam project ini adalah dataset _Mobil Price Classification_ yang diambil dari [kaggle](https://www.kaggle.com/iabhishekofficial/mobile-price-classification), dengan `price_range` sebagai variabel target yang memiliki 4 kelas di dalamnya.
