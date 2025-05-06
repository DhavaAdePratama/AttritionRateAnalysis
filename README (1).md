# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding

Jaya Jaya Maju adalah perusahaan Multinasional yang memiliki lebih dari 1000 karyawan yang tersebar di seluruh indonesia. perusahaan ini telah beroperasi sejak tahun 2000 dan menjadi perusahaan yang cukup besar.
meskipun entitas perusahaan cukup besar namun perusahaan masih harus menghadapi tantangan yang cukup besar dalam mengelola sumber daya manusiannya. salah satu dampaknya yaitu tingginya attrition rate yang dialami perusahaan yaitu lebih dari 10% 

### Permasalahan Bisnis

Tingginya tingkat attrition ini memicu kekhawatiran karena dapat mempengaruhi stabilitas operasional dan meningkatkan biaya rekrutmen serta pelatihan karyawan baru. Dalam upaya untuk memahami akar permasalahan tersebut, dilakukanlah analisis data karyawan dengan pendekatan visual menggunakan Tableau. Dashboard yang dibuat bertujuan untuk mengidentifikasi faktor-faktor utama yang berkorelasi dengan keputusan karyawan untuk keluar dari perusahaan.

Beberapa variabel penting yang dianalisis meliputi kepuasan kerja (Job Satisfaction), keseimbangan hidup dan pekerjaan (Work-Life Balance), jarak rumah ke tempat kerja (Distance From Home), keterlibatan kerja (Job Involvement), kapan terakhir kalo karyawan di promosikan (Year Since Last Promotion), berapa lama karyawan telah bekerja di perusahaan ini (Years At Company) hingga kompensasi yang diterima karyawan (Monthly Income).

Melalui visualisasi ini, perusahaan diharapkan dapat lebih mudah mengenali pola dan membuat strategi retensi karyawan yang lebih efektif dan tepat sasaran.

### Cakupan Proyek

Proyek ini bertujuan untuk menganalisis data karyawan perusahaan Jaya Jaya Maju dalam rangka memahami faktor-faktor yang memengaruhi attrition (keluarnya karyawan dari perusahaan). Analisis dilakukan melalui pendekatan statistik dan visualisasi interaktif menggunakan Python dan Tableau.
Tuliskan cakupan proyek yang akan dikerjakan.

Cakupan Proyek meliputi:

1. Data Understanding
    - Memahami struktur data karyawan yang mencakup informasi demografis, performa kerja, kepuasan, dan kompensasi.
    

2. Data Preprocessing
   
    - Mengevaluasi kualitas data serta menangani missing value.
    - Perhitungan variabel untuk analisis, seperti Recency, Frequency, dan Monetary.

3. Exploratory Data Analysis (EDA)

    - Visualisasi distribusi data dan outlier.

    - Analisis korelasi antara fitur-fitur penting dan status attrition.

    - RFM Analysis Adaptasi untuk Karyawan

      - Recency: Menggunakan YearsSinceLastPromotion, Frequency: Menggunakan YearsAtCompany, Monetary: Menggunakan MonthlyIncome.

      - Penilaian skor dan segmentasi karyawan berdasarkan tingkat risiko keluar.

4. Dashboard Visualisasi (Tableau)


### Persiapan

Sumber data: https://github.com/dicodingacademy/dicoding_dataset/blob/main/employee/employee_data.csv

Setup environment: 

```

```

## Business Dashboard

Jelaskan tentang business dashboard yang telah dibuat. Jika ada, sertakan juga link untuk mengakses dashboard tersebut.

## Conclusion

Berdasarkan analisis menggunakan metode RFM (Recency, Frequency, Monetary), ditemukan bahwa tingkat attrition tertinggi berasal dari divisi Research and Development serta Sales. Menariknya, dari segi recency category attrition risk tidak jauh beda dengan yg lain. jika dilihat dari segi frequency sudah mulai nampak suatu perbedaan yg terlihat dimana attrition risk memiliki tingkat paling rendah dalam seberapa lama kerja pada perusahaan ini.kemudian dari segi pendapatan perbulannya category atterition risk juga mendapatkan income paling kecil perbulannya. Hal ini membuka peluang untuk analisis lebih dalam mengenai promosi terakhir serta keloyalan kepada perusahaan.

Dari sisi recency, karyawan yang masuk dalam kategori Attrition Risk cenderung merupakan karyawan yang belum lama bergabung di perusahaan. Selain itu, mereka juga memiliki tingkat penghasilan bulanan yang relatif rendah dibandingkan dengan kategori lainnya.

Meskipun dari sisi frequency (dilihat dari YearsAtCompany), kelompok Attrition Risk sempat menunjukkan kemajuan karier melalui promosi jabatan dalam waktu yang relatif singkat, hal ini tidak diikuti oleh peningkatan pendapatan yang sepadan. Ketidakseimbangan antara promosi jabatan dan kompensasi ini kemungkinan besar menjadi salah satu pemicu utama dari keputusan mereka untuk keluar dari perusahaan.

Dengan demikian, dapat disimpulkan bahwa faktor kompensasi, masa kerja yang masih singkat, serta divisi kerja tertentu memiliki pengaruh besar terhadap kemungkinan karyawan untuk keluar. Ini menjadi masukan penting bagi manajemen SDM untuk merancang strategi retensi karyawan yang lebih efektif.

### Rekomendasi Action Items (Optional)

Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.

- action item 1
- action item 2
