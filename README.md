# Klasifikasi-Teks-PyTorch-ML-2023
## Projek Akhir Matakuliah Machine Learning 2023

## Library
### Pandas
#### pip install pandas
### scikit-learn
#### pip install scikit-learn
### PyTorch
#### https://pytorch.org
### matplotlib
#### pip install matplotlib

Proyek ini mengimplementasikan model Neural Network untuk melakukan klasifikasi teks menggunakan dataset "tweets.csv". Tujuan utama dari proyek ini adalah untuk mendeteksi sentimen atau kategori dari teks yang diberikan. Dalam proyek ini, kami menggunakan teknik ekstraksi fitur TF-IDF (Term Frequency-Inverse Document Frequency) untuk mengukur pentingnya sebuah kata dalam dokumen atau korpus teks. Fitur teks diekstraksi menggunakan library TfidfVectorizer dari scikit-learn. Kemudian, data dibagi menjadi data latih dan data uji menggunakan fungsi train_test_split. Selanjutnya, kami mendefinisikan model Neural Network dengan arsitektur MLP (Multi-Layer Perceptron) menggunakan PyTorch. Model ini memiliki dua lapisan linear dengan fungsi aktivasi ReLU dan sigmoid. Model dilatih menggunakan fungsi loss BCELoss dan optimizer Adam. Setelah melatih model, dilakukan evaluasi dengan menghitung akurasi pada data uji. Hasil akurasi yang diperoleh sebesar 85.88% menunjukkan bahwa model memiliki kemampuan yang baik dalam mengklasifikasikan teks dengan benar. Meskipun hasil akurasi tersebut cukup tinggi, perlu diingat bahwa performa model dapat bervariasi tergantung pada dataset yang digunakan. Terdapat juga potensi untuk meningkatkan performa model dengan melakukan penyesuaian arsitektur, parameter, atau menggunakan teknik lainnya.

Kesimpulan ini menekankan pentingnya penggunaan teknik enkripsi pada Platform as a Service (PaaS) dan Software as a Service (SaaS) untuk menjaga keamanan data. Pilihan enkripsi bergantung pada jenis platform dan opsi yang didukung oleh penyedia layanan. Penggunaan enkripsi pada aplikasi juga dapat dilakukan dengan mengelola enkripsi di dalam kode atau menggunakan server atau layanan enkripsi eksternal.

Namun, perlu diperhatikan bahwa penggunaan proxy enkripsi untuk SaaS dapat memperkenalkan masalah keamanan baru dan dapat mempengaruhi fungsionalitas aplikasi. Oleh karena itu, penggunaan proxy enkripsi perlu dipertimbangkan dengan hati-hati dan terbatas pada kasus penggunaan yang valid.

## Referensi Pustaka:
Scikit-learn Documentation. [Online]. Available: https://scikit-learn.org/stable/documentation.html.
PyTorch Documentation. [Online]. Available: https://pytorch.org/docs/stable/index.html.
Géron, A. (2019). Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems. O'Reilly Media.
