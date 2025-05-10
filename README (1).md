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

4. Dashboard Visualisasi (Tableau)


### Persiapan

Sumber data: https://github.com/dicodingacademy/dicoding_dataset/blob/main/employee/employee_data.csv

Setup environment: 
Clone repository ini ke komputer lokal yang anda miliki : ``` Git clone https://github.com/DhavaAdePratama/AttritionRateAnalysis ```

Set Up PYTHON sesuai requirements yang ada  : ``` pip install -r requirements.txt ```

## Business Dashboard

Link Dashboard : https://public.tableau.com/app/profile/dhava.ade.pratama/viz/DASHBOARD_17468711608590/Dashboard1?publish=yes

PENJELASAN:

berdasarkan analisis pada dashboard yang telah dibuat, sebagian besar faktor seperti kepuasaan kerja, lingkungan, keterlibatan, serta work-life balance menunjukkan distribusi yang relatif mirip antara karyawan yang bertahan dan yang keluar.
Namun, terdapat perbedaan yang sangat mencolok pada aspek penghasilan. karyawan yang keluar cenderung memiliki penghasilan yang jauh lebih rendah di bandingkan dengan karyawan yang bertahan.
Hal ini mengindikasikan bahwa kompensasi menjadi faktor utama dan signifikan dalam keputusan karyawan untuk meninggalkan perusahaan, bahkan lebih dominan dibandingkan faktor faktor lain.

## Conclusion

Berdasarkan hasil analisis data, terlihat bahwa work-life balance antara karyawan yang keluar dan yang tetap bekerja cenderung serupa. Namun, terdapat perbedaan yang lebih jelas terkait jarak rumah ke kantor. Karyawan yang keluar lebih banyak berasal dari kelompok yang memiliki jarak tempuh lebih jauh dibandingkan mereka yang bertahan. Hal ini mengindikasikan bahwa jarak tempat tinggal ke kantor bisa menjadi salah satu faktor penting yang memengaruhi keputusan karyawan untuk meninggalkan perusahaan.

Dari segi kenyamanan lingkungan kerja dan peran pekerjaan, baik karyawan yang keluar maupun yang bertahan menunjukkan nilai yang hampir serupa. Artinya, faktor lingkungan kerja dan keterlibatan dalam pekerjaan tidak menunjukkan pengaruh signifikan terhadap keputusan untuk keluar dari perusahaan.

Perbedaan antara karyawan yang keluar dan yang bertahan berdasarkan status lembur (OverTime) juga tidak terlalu mencolok. Jumlah karyawan yang keluar meskipun sering lembur hampir sebanding dengan mereka yang keluar meskipun tidak lembur. Ini menunjukkan bahwa OverTime bukanlah satu-satunya faktor utama yang memengaruhi tingkat attrition.

Ketika dilihat berdasarkan status pernikahan, mayoritas karyawan yang keluar berasal dari kelompok yang belum menikah. Karyawan single tampaknya lebih cenderung untuk berpindah kerja dibandingkan mereka yang sudah menikah, yang mungkin memiliki pertimbangan lebih kompleks terkait stabilitas pekerjaan.

Temuan menarik lainnya adalah bahwa banyak dari karyawan yang keluar justru merupakan individu yang mengalami promosi lebih cepat. Namun, mereka memiliki tingkat gaji yang relatif lebih rendah dibandingkan dengan karyawan yang bertahan. Hal ini menunjukkan adanya ketidakseimbangan antara peningkatan tanggung jawab dan kompensasi yang diberikan, yang bisa menjadi alasan utama di balik keputusan untuk keluar dari perusahaan.

Secara keseluruhan, meskipun terdapat beberapa faktor yang memengaruhi keputusan karyawan untuk keluar, faktor-faktor seperti jarak tempuh ke kantor, serta kompensasi yang tidak sebanding dengan promosi menjadi elemen yang paling jelas berperan dalam menentukan tingkat attrition di perusahaan ini.

### Rekomendasi Action Items (Optional)

- Menyeimbangkan kompensasi antara beban yang diberikan kepada karyawan dengan gaji yang diterima oleh karyawan
- Memberikan uang kompensasi lebih kepada karyawan yang overtime / lembur
- Memberikan Keringanan bagi karyawan yang memiliki jarak yang jauh dari rumah ke kantor, seperti tambahan ongkos transportasi, dll.
