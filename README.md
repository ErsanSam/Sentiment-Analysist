# Sentiment-Analysist
Mempelajari analisis sentimen media sosial menggunakan data teks dalam Bahasa Indonesia, yaitu dataset IndoNLU.
Mengetahui pendapat orang mengenai suatu produk, layanan, atau masalah di masyarakat dan menghasilkan sentimen dalam tiga kategori, yaitu positif, negatif, dan netral.
## Rangkuman Materi 
NLP merupakan subbidang dari Artificial Intelligence (AI) untuk menganalisis, memodelkan, dan memahami bahasa manusia. NLP mencakup berbagai algoritma, metode, dan permasalahan yang menggunakan teks sebagai input. Ia menghasilkan beberapa informasi seperti label, representasi semantik, dan sebagainya, sebagai output. 

Teknik NLP digunakan di setiap aplikasi cerdas yang melibatkan bahasa alami. Ia merupakan komponen penting dalam berbagai aplikasi perangkat lunak yang kita gunakan dalam kehidupan sehari-hari

Analisis sentimen merupakan salah satu topik dalam Natural Language Processing (Pemrosesan Bahasa Alami). Ia bertujuan untuk mengetahui pendapat orang mengenai suatu produk, layanan, atau masalah di masyarakat. 

Sebuah aplikasi NLP menerapkan berbagai teknik untuk menyelesaikan permasalahan yang berbeda. Berikut adalah beberapa teknik NLP yang sering digunakan:

* Pembuatan Teks (Text generation)
Pembuatan teks, disebut juga Natural Language Generation (NLG) adalah proses menghasilkan keluaran teks bahasa alami dari bahasa lain. Teknik ini juga sering disebut sebagai text-to-text generation. Contoh aplikasinya adalah mesin penerjemah.

* Pencarian Informasi (Information Retrieval)
Information retrieval (IR) adalah proses menemukan informasi (biasanya berupa dokumen atau teks) yang relevan dengan kebutuhan. Informasi ini diambil dari kumpulan sumber informasi yang tersedia (biasanya di komputer atau internet).

* Pemodelan Bahasa
Dalam pemodelan bahasa, kita memprediksi kata berikutnya dalam kalimat berdasarkan histori kata-kata sebelumnya. Tujuannya untuk mempelajari kemungkinan urutan kata yang muncul.

* Klasifikasi Teks
Merupakan proses membagi teks ke dalam kumpulan kategori tertentu berdasarkan isinya. Klasifikasi teks merupakan teknik paling populer di NLP dan digunakan dalam berbagai aplikasi, misalnya identifikasi spam email dan analisis sentimen.

Secara umum, komponen utama alur proyek pengembangan sistem NLP adalah sebagai berikut:

* Data Acquisition.
* Text Cleaning.
* Pre-Processing.
* Feature Engineering.
* Modeling.
* Evaluation.
* Deployment.
* Monitoring and Model Update.
Terdapat beberapa cara untuk melakukan akuisisi data, antara lain:

* Menggunakan data publik.
* Mengumpulkan data dari internet (web scraping).
* Data (text) augmentation.

Text cleaning dan pre-processing terdiri dari tiga tahap utama, antara lain: 

* Menghilangkan gangguan (noise) pada teks.
* Proses tokenisasi.
* Proses normalisasi.
Teknik rekayasa fitur untuk representasi teks mengubah teks pada data masukan ke dalam bentuk numerik sehingga dapat digunakan untuk pemodelan. Terdapat beberapa metode rekayasa fitur untuk representasi teks. Metode ini diklasifikasikan ke dalam empat kategori, antara lain:

* Basic vectorization approaches (contoh: One-Hot Encoding, Bag of Words, Bag of N-Grams, dan TF-IDF).
* Distributed representations (contoh: Words Embeddings).
* Universal text representation (menggunakan pre-trained embedding).
* Handcrafted features (mengandalkan domain-specific knowledge).


Pada project ini, Saya telah melakukan proses analisis sentimen menggunakan data IndoNLU dengan teknik Deep Learning dan Support Vector Machine. SVM merupakan algoritma machine learning yang dapat digunakan untuk menyelesaikan permasalahan klasifikasi, regresi, dan pendeteksian outlier. Tujuan algoritma SVM adalah menemukan hyperplane terbaik dalam ruang berdimensi-N (ruang dengan N-jumlah fitur) yang memisahkan titik-titik data input dengan jelas.

Dengan uraian tersebut, diharapkan Anda dapat memahami bagaimana melakukan analisis sentimen terhadap data teks serta mampu membuat modelnya dengan teknik Deep Learning dan algoritma Support Vector Machine (SVM). 



### Daftar Referensi
Jika tertarik untuk mengeksplorasi lebih lanjut mengenai materi Sentiment Analysis atau Natural Language Processing, Anda dapat mempelajarinya melalui daftar referensi berikut:

[29] Kemp, Simon. "Digital 2021: Global Overview Report". Published in Datareportal. 2021. Tersedia: tautan. Diakses pada Juni 2021. 

[30] Hagiwara, Masato. "Introduction to Natural Language Processing". Manning Publishing. 2020. Tersedia: tautan. Diakses pada: Juni 2021.

[31] Vajjala, Sowrnya, et al. "Practical Natural Language Processing". O'Reilly Media. 2020. Tersedia: tautan.

[32] Gu, Xinxing. "Google Translate's instant camera translation gets an upgrade". 2019. Tersedia: tautan. Diakses pada 26 Juni 2021.

[33] Manning, Christoper D, et al. "Introduction to Information Retrieval". Cambridge University Press 2008. Tersedia: tautan.

[34] Lovesque, Hecter J. "The Winograd Schema Challenge". 13th International Conference on Principles of Knowledge Representation and Reasoning. Tersedia: tautan.

[35] Kemendikbud. "Badan Bahasa Petakan 652 Bahasa Daerah di Indonesia". Tersedia: tautan. Diakses pada 29 Juni 2021.

[36] Chaudhary, Amit. “Data Augmentation for NLP”. Tersedia: tautan. Diakses pada 30 Juni 2021.

[37] Wilie, Bryan, et al. "IndoNLU: Benchmark and Resources for Evaluating Indonesian Natural Language Understanding".  AACL-IJNLP. 2020. Tersedia: tautan.

[38] Purwarianti, Ayu dan Crisdayanti, Ida Ayu Putri Ari. "Improving Bi-LSTM Performance for Indonesian Sentiment Analysis Using Paragraph Vector". Tersedia: tautan.

[39] Indobenchmark. "Pre-Trained Models for NLP Tasks Using PyTorch". Tersedia: tautan. Diakses pada Juli 2021.

[40] Scikit-learn Documentation. "TfidfVectorizer". Tersedia: tautan. Diakses pada 9 Juli 2021. 
