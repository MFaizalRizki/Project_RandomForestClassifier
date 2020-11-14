# Random-Forest-Classifier

Pengklasifikasi Random Forest Classifier yang sangat sederhana diimplementasikan dengan python. 
Library sklearn.ensemble digunakan untuk mengimpor kelas Random Forest Classifier. Objek kelas telah dibuat. 
Argumen berikut diteruskan secara inisial ke objek :

 - n_estimators = 10
 - criterion = 'entropy'

Model awal hanya diberikan 10 pohon keputusan, sehingga totalnya 10 salah prediksi. 
Setelah model dilengkapi dengan lebih banyak pohon keputusan, jumlah prediksi yang salah semakin sedikit.
Ditemukan bahwa jumlah pohon keputusan yang optimal untuk model ini untuk memprediksi jawaban adalah 200 pohon keputusan. 
Oleh karena itu, argumen n_estimator diberi nilai akhir 200. Jika lebih dari 200 akan menyebabkan over-fitting dan akan menyebabkan 
prediksi yang salah lebih lanjut.