# Data Science Portfolio
#  **HR Analytic**
## Instructions for Running Python Notebooks Locally
1. Install dependencies using requirements.txt.<br>
2. Run notebooks as usual by using a anaconda navigator or jupyter notebook server, Vscode etc.<br>
3. The data used is hr-analytics.csv

### **Business Understanding**
Company R adalah Agen penempatan kerja yang menyediakan program pelatihan data science gratis ke berbagai industri company client di seluruh Indonesia. Adapun persyaratan yang diberlakukan adalah sebagai berikut :
- Terbatas untuk 100 pelamar.
- Diselenggarakan secara triwulanan (dimulai pada minggu pertama bulan Januari, April, Juli, Okt).
- Durasi pelatihan 3 bulan. <br>
- Agensi menawarkan kontrak penempatan kerja selama satu tahun.
- Company R mendapatkan keuntungan sebesar 0,25% dari gaji bulanan.
- Pekerjaan akan berakhir setelah periode satu tahun selesai, kecuali jika ditawarkan kontrak/perpanjangan baru.
### **`Problem`**
Bagaimana cara meningkatkan keuntungan yang diperoleh dari penempatan kerja tidak maksimal.
### **`Goals`**
Membantu Company R dalam meningkatkan keuntungan yang diperoleh dari program penempatan kerja dan memastikan biaya digunakan untuk keuntungan yang lebih besar.
### **`Objective`**
Membangun model Machine Learning yang dapat membantu mengidentifikasi apakah kandidat yang mendaftar pelatihan  sedang mencari perubahan pekerjaan atau tidak berdasarkan dari data baru yang diberikan. <br>
Kemampuan untuk menyaring kandidat yang mendaftar pelatihan untuk mencari perubahan pekerjaan dengan cara yang lebih tepat. <br>
Porsi yang lebih besar dari peserta pelatihan yang mencari perubahan pekerjaan = Lebih banyak kandidat untuk program penempatan kerja.
### **`Business Metrics`**
Revenue (pendapatan) dari program penempatan kerja.

###  **Solution Strategy**
Solusi untuk mengatasi masalah ini adalah pengembangan proyek ilmu data. Proyek ini akan memiliki model pembelajaran mesin yang dapat memprediksi apakah kandidat looking for job atau not looking for job.<br>
**Step 01. Data Description :** Pada bagian pertama ini data akan dikumpulkan dan dipelajari. Nilai yang hilang akan terancam di dihapus. <br>
**Step 02. Exploratory Data Analysis :** Proses analisis untuk memahami karakteristik data, dan hal-hal yang perlu dilakukan agar data tersebut dapat digunakan untuk proses pembelajaran model. <br>
**Step 03. Handling Missing Value :** Mengisi data-data yang kosong dengan nilai konstan, mean, dan modus.<br>
**Step 04. Handling Duplicated Data :** Melakukan pengecekan apakah terdapat data duplikat atau tidak, jika terdapat data duplikat maka dilakukan drop.<br>
**Step 05. Handling Invalid Values :** Melakukan pengecekan apakah ada data yang tidak lengkap atau tidak benar, jika ditemukan data invalid maka dilakukan drop.<br>
**Step 06. Feature Extraction :** Melakukan extrac beberapa feature dengan membuat kolom baru untuk mempermudah analisis.<br>
**Step 07. Feature Selection :** Melakukan seleksi feature yang akan digunakan dan drop feature yang tidak diperlukan, dalam kasus ini feature yang di drop adalah enrollee_id <br>
**Step 08. Handling Outliers :** Melakukan drop terhadap data outliers karena nilainya terlalu ekstrim/jauh berbeda dari data-data lain pada umumnya<br>
**Step 9. Feature Transformation :** Melakukan normalisasi pada data dengan skala berbeda dengan data lainnya agar menjadi data dengan skala yang sama untuk mempermudah interpretasi beberapa model ML<br>
**Step 10 Feature Encoding :** Merubah feature categorical menjadi feature numeric untuk mempermudah pembelajaran dengan machine learning.<br>
**Step 11. Handling Class Imbalance :** Melakukan handle imbalance pada data target yang terjadi sangat timpang menggunakan oversampling dan undersampling.<br>
**Step 12. Machine Learning Modeling :** Melatih algoritma pembelajaran mesin dan bagaimana mesin dapat memprediksi data, dalam kasus data ini menggunakan pengukuran **precision** karena tujuan yang ingin dicapai adalah untuk meningkatkan profit <br>
**Step 13. Hyperparameter Tuning :** Melakukan hyperparameter tuning untuk mengoptimalkan kinerja model agar memperoleh hasil yang lebih baik<br>
**Step 14. Feature Importance :** Menggunakan feature importance dengan melihat feature mana yang baik digunakan selanjutnya untuk dijadikan business insight dan juga sebagai tambahan eksperimen pada model (untuk mengurangi kompleksitas dan menghindari curse of dimensionality).

### **Exploratory Data Analysis**
![Img 1](screenshot/1.PNG)