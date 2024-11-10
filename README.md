# Chapter-2: Machine Learning and Deep Learning <br>
-   02_Kelompok H_01 <br>
    *Tujuan*: Menerapkan dan membandingkan akurasi berbagai model *supervised learning* untuk klasifikasi menggunakan *Scikit-learn*, serta menyusun hasil sebagai bagian dari *portfolio* peserta.
        **Langkah-Langkah Tugas**:
    1. **Prapemrosesan Data**:
       - Menghapus kolom yang tidak relevan untuk pemodelan.
    - Melakukan *One-Hot Encoding* untuk data kategorikal menggunakan `pd.get_dummies`.
    - Memisahkan fitur (X) dengan target (Y), di mana Y mengacu pada kolom "Exited".
    - Melakukan *scaling* atau *normalisasi* data.
    2. **Pemilihan dan Evaluasi Model**:
    - Menggunakan tiga model *supervised learning* berbeda dari *Scikit-learn*.
            Untuk masing-masing model, peserta harus:
         - Menjelaskan secara singkat mengenai model tersebut.
         - Melakukan evaluasi untuk mengukur akurasi klasifikasinya.<br>
    *Checklist Tugas*: Seluruh proses diberi tanda dengan #TODO yang harus diselesaikan untuk memastikan semua modul, termasuk versi yang sesuai, telah terinstal dengan benar.

-   02_Kelompok h_02<br>
    *Tujuan*: Menerapkan teknik segmentasi data dengan KMeans Clustering dan menyusun hasilnya sebagai bagian dari portfolio peserta.
        **Langkah-Langkah Tugas**:
        -   Prapemrosesan Data dan Penentuan Jumlah Cluster:
            Menentukan jumlah cluster terbaik untuk dataset menggunakan metode yang relevan, seperti elbow method atau silhouette score.
        -   Pemodelan dengan KMeans:
            Melakukan klasterisasi menggunakan algoritma KMeans dari Scikit-learn.
            Memasukkan label hasil klasterisasi ke dalam DataFrame untuk analisis lebih lanjut.
        -   Visualisasi Hasil Clustering:
            Menggunakan Seaborn untuk membuat plot visual yang menampilkan hasil klasterisasi.<br>
    *Checklist Tugas*: Setiap proses ditandai dengan #TODO untuk memastikan bahwa semua langkah dikerjakan, dengan total 4 bagian kode yang harus diselesaikan.

-   02_Kelompok H_03<br>
    *Tujuan*: Memprediksi harga rumah dengan pengaturan input ganda menggunakan *Neural Network* berbasis *Multilayer Perceptron* (MLP), serta menyusun hasilnya:
        **Tahapan Tugas**:
    1. **Membangun Model**:
        - Menentukan parameter *weights* dan *biases*.
        - Menetapkan *hyperparameters*, seperti jumlah neuron pada lapisan input, lapisan tersembunyi, dan lapisan output.
        - Menetapkan fungsi aktivasi dan konfigurasi layer.
    2. **Kompilasi Model**:
        - Menentukan *loss function*, *optimizer* (termasuk *learning rate* dan *momentum*), dan metrik opsional untuk evaluasi.
    3. **Pelatihan Model**:
        - Menetapkan *hyperparameters* pelatihan, yaitu jumlah *epochs* dan ukuran *batch*.
        - Menginisiasi *validation data* (opsional).<br>
    *Checklist Tugas*:<br>
        Peserta perlu menyelesaikan 10 #TODO dalam proses, yang meliputi:<br>
    - Mengubah *features* dan *target* dari Numpy Array ke Pandas DataFrame.
    - Membagi data menjadi *train*, *validation*, dan *test*.
    - Melakukan *standarisasi* dan *normalisasi* pada data.
    - Membuat lapisan tersembunyi dengan neuron dan fungsi aktivasi ReLU.
    - Menentukan jumlah *epoch*, ukuran *batch*, nama file model, dan melakukan *model reload* untuk prediksi data baru.<br>

-      02_Kelompok H_04 <br>
    *Tujuan*: Mengklasifikasi transaksi yang terindikasi fraud menggunakan *Multilayer Perceptron (MLP)* dengan bantuan *GPU* untuk meningkatkan efisiensi, serta menyusun hasil sebagai bagian dari *portfolio* peserta. <br>
        **Langkah-Langkah Tugas**:<br>
    1. **Prapemrosesan Data**:<br>
        - Mengimpor dataset menggunakan *Pandas* dengan fungsi "read_by_CPU".
        - Menghapus kolom ID, menentukan X (fitur) dan Y (target) dengan "data_gpu".
        - Membagi dataset menjadi *train set* (80%) dan *test set* (20%) menggunakan fungsi "splitCPU" dan "splitGPU".
    2. **Pengaturan Model dan GPU**:
        - Mengaktifkan GPU (CUDA) sebagai perangkat untuk pelatihan.
        - Menentukan ukuran *batch* dan menetapkan *hyperparameters* dan *input size* model.
        - Menjawab pertanyaan terkait perbedaan antara *hyperparameters* dan *parameters*, serta alasan mengapa total *trainable parameters* sama dengan total keseluruhan parameter.
    3. **Fine-Tuning dan Evaluasi**:
        - Jika akurasi model kurang dari 95%, lakukan *fine-tuning* terhadap *hyperparameters* untuk mencapai akurasi yang lebih tinggi.<br>
        *Checklist Tugas*: Peserta harus menyelesaikan setiap #TODO yang mencakup prapemrosesan, pembagian data, pengaturan model dan perangkat GPU, serta menjawab pertanyaan terkait *parameters* dan *hyperparameters*.<br>
