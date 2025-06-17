# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Jaya Jaya Maju

## Business Understanding

Jaya Jaya Maju merupakan perusahaan multinasional yang telah berdiri sejak tahun 2000 dan saat ini mempekerjakan lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri. Sebagai perusahaan besar dengan cakupan nasional, keberhasilan Jaya Jaya Maju sangat bergantung pada stabilitas dan produktivitas tenaga kerjanya. Meskipun demikian, perusahaan kini menghadapi tantangan signifikan dalam mengelola karyawan, terutama berkaitan dengan tingginya tingkat pergantian karyawan (attrition rate). Saat ini attrition rate tercatat mencapai 16.9%. Kondisi ini dapat berdampak negatif terhadap kinerja operasional, efektivitas tim, dan biaya rekrutmen yang semakin meningkat.

Untuk mengatasi hal ini, departemen Human Resources (HR) berinisiatif memanfaatkan pendekatan berbasis data untuk memahami faktor-faktor yang menyebabkan tingginya attrition rate. Dengan mengidentifikasi akar penyebabnya, diharapkan perusahaan dapat merumuskan strategi intervensi yang lebih tepat demi mempertahankan dan meningkatkan kepuasan kerja karyawan.

### Permasalahan Bisnis

Tingkat Attritionnya karyawan di perusahaan Jaya Jaya Maju menimbulkan berbagai tantangan serius yang berdampak pada kinerja dan stabilitas perusahaan. Beberapa masalah utama yang dihadapi perusahaan antara lain:

1. **Penurunan Produktivitas**
   Kehilangan karyawan menyebabkan penurunan produktivitas tim dan perusahaan secara keseluruhan. Pengalaman dan pengetahuan yang dimiliki oleh karyawan lama sulit untuk digantikan dengan cepat, menghambat alur kerja dan tujuan perusahaan.

2. **Gangguan dalam Operasional**
   Pergantian karyawan yang tinggi dapat mengganggu kelancaran operasional, menyebabkan keterlambatan dalam penyelesaian proyek atau tugas, serta menurunkan kualitas layanan yang diberikan kepada klien.

3. **Penurunan Kepuasan Karyawan**
   Tingginya tingkat attrition berisiko menurunkan moral dan kepuasan karyawan yang masih bertahan, berpotensi menyebabkan lebih banyak karyawan lainnya mempertimbangkan untuk Attrition.

4. **Ancaman pada Reputasi Perusahaan**
   Jika tingkat Attrition karyawan terus meningkat, reputasi perusahaan sebagai tempat kerja yang stabil dan mendukung dapat terancam, yang berpotensi menyulitkan perusahaan untuk menarik kandidat berkualitas di masa depan.

5. **Kurangnya Alat Analitik untuk HR**
   Perusahaan juga menghadapi kesulitan dalam mengidentifikasi faktor-faktor utama yang menyebabkan tingginya tingkat attrition dan tidak memiliki dashboard analitik yang memadai untuk manajer HR dalam memantau kondisi tenaga kerja dan faktor-faktor terkait.


### Cakupan Proyek
Proyek ini meliputi beberapa tahap utama sebagai berikut:

1. **Pemahaman Data dan Preprocessing**: Mengkaji struktur dan kualitas data terkait attrition di perusahaan Jaya Jaya Maju. Setelah mengidentifikasi masalah dalam data, dilakukan proses pembersihan, transformasi fitur, penyeimbangan data, dan penanganan nilai yang hilang.

2. **Modeling**: Membangun model prediktif yang bertujuan untuk mengidentifikasi faktor-faktor kunci yang mempengaruhi keputusan karyawan untuk mengundurkan diri.

3. **Pembuatan Dashboard Bisnis**: Merancang dan mengembangkan dashboard interaktif yang mampu menampilkan indikator attrition secara visual, serta mendukung pengambilan keputusan yang berbasis data untuk departemen HR.

4. **Insight dan Rekomendasi**: Menggali wawasan dari data yang ada dan memberikan rekomendasi tindakan yang konkret untuk membantu menurunkan tingkat attrition di perusahaan.



### Persiapan

Dataset yang digunakan dalam proyek ini adalah data karyawan perusahaan Jaya Jaya Maju yang dapat diakses melalui [Data Employee Jaya Jaya Maju](https://raw.githubusercontent.com/dicodingacademy/dicoding_dataset/refs/heads/main/employee/employee_data.csv).

Dataset ini berisi data mengenai karyawan perusahaan Jaya Jaya Maju, dengan 35 fitur dan 1470 entri data. Berikut adalah daftar fitur yang terdapat dalam dataset:

1. **EmployeeId**: ID unik untuk setiap karyawan.
2. **Age**: Usia karyawan.
3. **Attrition**: Menunjukkan apakah karyawan Attrition dari perusahaan (Attrition = 1) atau tetap bekerja (Attrition = 0).
4. **BusinessTravel**: Frekuensi perjalanan bisnis yang dilakukan oleh karyawan.
5. **DailyRate**: Gaji harian karyawan.
6. **Department**: Nama departemen tempat karyawan bekerja.
7. **DistanceFromHome**: Jarak dari rumah karyawan ke kantor (dalam kilometer).
8. **Education**: Tingkat pendidikan terakhir karyawan.
9. **EducationField**: Jurusan pendidikan karyawan.
10. **EmployeeCount**: Jumlah karyawan di perusahaan.
11. **EnvironmentSatisfaction**: Kepuasan karyawan terhadap lingkungan kerja.
12. **Gender**: Jenis kelamin karyawan.
13. **HourlyRate**: Gaji per jam karyawan.
14. **JobInvolvement**: Tingkat keterlibatan atau komitmen karyawan terhadap pekerjaan.
15. **JobLevel**: Level jabatan karyawan dalam perusahaan.
16. **JobRole**: Posisi pekerjaan yang dipegang karyawan.
17. **JobSatisfaction**: Kepuasan karyawan terhadap pekerjaannya.
18. **MaritalStatus**: Status pernikahan karyawan.
19. **MonthlyIncome**: Penghasilan bulanan karyawan termasuk tunjangan dan bonus.
20. **MonthlyRate**: Gaji per bulan karyawan.
21. **NumCompaniesWorked**: Jumlah perusahaan tempat karyawan pernah bekerja.
22. **Over18**: Menunjukkan apakah karyawan berusia lebih dari 18 tahun.
23. **OverTime**: Menunjukkan apakah karyawan sering bekerja lembur.
24. **PercentSalaryHike**: Persentase kenaikan gaji dibandingkan tahun sebelumnya.
25. **PerformanceRating**: Penilaian kinerja karyawan.
26. **RelationshipSatisfaction**: Kepuasan karyawan terhadap hubungan dengan rekan kerja.
27. **StandardHours**: Jumlah jam kerja standar bulanan.
28. **StockOptionLevel**: Tingkat opsi saham yang diberikan perusahaan kepada karyawan.
29. **TotalWorkingYears**: Total pengalaman kerja karyawan dalam tahun.
30. **TrainingTimesLastYear**: Jumlah pelatihan yang diikuti oleh karyawan pada tahun sebelumnya.
31. **WorkLifeBalance**: Tingkat keseimbangan antara pekerjaan dan kehidupan pribadi.
32. **YearsAtCompany**: Jumlah tahun karyawan telah bekerja di perusahaan Jaya Jaya Maju.
33. **YearsInCurrentRole**: Jumlah tahun karyawan telah bekerja di posisi/jabatan saat ini.
34. **YearsSinceLastPromotion**: Jumlah tahun sejak karyawan terakhir kali mendapatkan promosi.
35. **YearsWithCurrManager**: Jumlah tahun karyawan telah bekerja di bawah manajer saat ini.


#### **Setup Environment**

Berikut adalah langkah-langkah untuk menyiapkan environment:

1. **Menjalankan Notebook**

* Jika menggunakan **Anaconda**, jalankan perintah berikut:

  ```bash
  conda create --name main-ds python=3.9
  conda activate main-ds
  pip install -r requirements.txt
  ```

* Jika menggunakan **Shell/Terminal**, jalankan perintah berikut:

  ```bash
  pip install pipenv
  pipenv install
  pipenv shell
  pip install -r requirements.txt
  ```

* Jalankan file **`notebook.ipynb`** untuk melihat hasil analisis data beserta wawasan yang diperoleh. bisa menggunakan **Jupyter Notebook** atau **IDE lokal** lainnya, atau bisa menggunakan **Google Colab** untuk menjalankan proyek secara online.

---
2. **Akses Dashboard Metabase**

**Menjalankan Docker di Windows**:

**Langkah 1: Instal Docker**

Pastikan **Docker** terinstal pada mesin target tempat container Metabase akan dijalankan. dapat mengunduh Docker dari [sini](https://www.docker.com/products/docker-desktop).


1. **Unduh dan Instal Docker Desktop**:

   * Kunjungi [Docker Desktop for Windows](https://www.docker.com/products/docker-desktop) dan unduh installer.
   * Ikuti petunjuk instalasi dan pastikan **Hyper-V** dan **Windows Subsystem for Linux** diaktifkan.

2. **Verifikasi Instalasi Docker**:
   Setelah instalasi selesai, buka **Command Prompt** atau **PowerShell** dan jalankan perintah berikut untuk memastikan Docker terinstal dengan benar:

   ```bash
   docker --version
   ```

Jika perintah ini mengembalikan versi Docker, berarti Docker sudah siap digunakan.

**Langkah 2: Menjalankan Dashboard Metabase**

Setelah Docker terinstal, bisa menjalankan **Metabase** dengan cara berikut:

1. **Tarik (Pull) Docker Image Metabase** jika belum memiliki image Metabase:

   ```bash
   docker pull metabase/metabase:v0.46.4
   ```

2. **Jalankan Docker container untuk Metabase**:

   ```bash
   docker run -p 3000:3000 --name metabase metabase/metabase
   ```

   Dengan perintah ini, Metabase akan berjalan di `http://localhost:3000` di browser Anda.

**Langkah 3: Menyambungkan Database Kustom**

Jika ingin menggunakan **file database kustom** yang sudah ada, harus memetakan folder lokal ke dalam container Docker yang menjalankan Metabase.

1. **Jalankan Metabase dengan volume untuk file database**:

   Gunakan perintah berikut untuk menyambungkan folder lokal yang berisi file database **`metabase.db.mv.db`** ke dalam container Metabase:

   ```bash
   docker run -d -p 3000:3000 --name metabase \
   -v /path/to/local/folder:/metabase.db \
   metabase/metabase
   ```

   Gantilah `/path/to/local/folder` dengan **path lokal** di mana **`metabase.db.mv.db`** disimpan.

2. **Salin file `metabase.db.mv.db` ke dalam folder lokal yang ditentukan**:
   Pastikan file **`metabase.db.mv.db`** berada di folder lokal yang telah tentukan (`/path/to/local/folder`).

**Langkah 4: Mulai Container Metabase**

Setelah memastikan file database sudah di tempat yang benar, dapat memulai container Metabase dengan perintah:

```bash
docker start metabase
```

**Langkah 5: Akses Metabase**

Setelah container berjalan, dapat mengakses **Metabase** melalui URL berikut di browser:

```
http://localhost:3000
```

### **Informasi Login**

Setelah akses Metabase, untuk login, gunakan informasi berikut:

* **Email**: `labibaadinda11@gmail.com`
* **Password**: `root123`

Dengan informasi login ini, pengguna dapat mengakses Metabase dan melihat dashboard serta data dari file **`metabase.db.mv.db`**.

**Langkah 6: Pemecahan Masalah**

Jika file database tidak digunakan dengan benar atau jika mengalami masalah, periksa langkah-langkah berikut:

1. **Periksa Log**:
   Dapat memeriksa log container untuk melihat kesalahan atau peringatan yang mungkin menunjukkan masalah dengan pemulihan database:

   ```bash
   docker logs metabase
   ```

2. **Izin Akses**:
   Pastikan izin untuk file **`metabase.db.mv.db`** sudah benar dan bahwa pengguna yang menjalankan container Docker memiliki akses baca dan tulis ke file tersebut.

3. **Direktori Container**:
   Pastikan file **`metabase.db.mv.db`** berada di folder yang benar di dalam container. Container harus diarahkan ke folder `/metabase.db` tempat file database berada.

---
**Menggunakan linux os**

**Langkah 1: Instal Docker**

Pastikan **Docker** terinstal pada mesin target tempat container Metabase akan dibangun. Dapat mengunduh Docker dari [sini](https://www.docker.com/products/docker-desktop) atau menggunakan langkah berikut untuk **Linux**.

**Menjalankan Docker di Linux**:

1. **Instal Docker di Linux**:

   * Di **Ubuntu** atau distribusi berbasis Debian, jalankan perintah berikut:

     ```bash
     sudo apt update
     sudo apt install docker.io
     ```

   * Untuk distribusi lain, silakan ikuti petunjuk [instalasi Docker di Linux](https://docs.docker.com/engine/install/).

2. **Verifikasi Instalasi Docker**:
   Setelah instalasi selesai, buka terminal dan jalankan perintah berikut untuk memastikan Docker terinstal dengan benar:

   ```bash
   docker --version
   ```

Jika perintah ini mengembalikan versi Docker, berarti Docker sudah siap digunakan.

**Langkah 2: Menjalankan Dashboard Metabase**

Setelah Docker terinstal, bisa menjalankan **Metabase** menggunakan Docker dengan langkah-langkah berikut:

1. **Jalankan perintah berikut pada Terminal** untuk menarik (pull) Docker image guna menjalankan **Metabase**:

   ```bash
   docker pull metabase/metabase:v0.46.4
   ```

2. **Setelah proses pembuatan Docker image selesai**, jalankan image tersebut dengan perintah berikut:

   ```bash
   docker run -p 3000:3000 --name metabase metabase/metabase
   ```

3. **Setelah container berjalan**, login ke **Metabase** menggunakan **email** dan **password** berikut:

   ```text
   email: labibaadinda11@gmail.com
   password: root123
   ```

**Langkah 3: Buat Container Metabase Baru**

Setelah menarik gambar Metabase, dapat membuat container baru untuk Metabase dan memetakannya ke direktori lokal untuk menyimpan file **`metabase.db.mv.db`**.

1. **Buat Docker container**:
   dapat membuat dan menjalankan container Metabase baru dengan menjalankan perintah berikut:

   ```bash
   docker run -d -p 3000:3000 --name metabase \
   -v /path/to/local/folder:/metabase.db \
   metabase/metabase
   ```

   * `/path/to/local/folder`: Ini adalah path lokal tempat file **`metabase.db.mv.db`** akan ditempatkan.
   * `/metabase.db`: Ini adalah direktori di dalam container tempat Metabase mengharapkan file database berada.

2. **Salin file `metabase.db.mv.db` ke container**:
   Sebelum menjalankan container, pastikan untuk menyalin file **`metabase.db.mv.db`** ke folder lokal yang telah ditentukan (`/path/to/local/folder`).

   * Pastikan file **`metabase.db.mv.db`** berada di folder yang benar, lalu lanjutkan untuk menjalankan container.

**Langkah 4: Mulai Container Metabase**

Setelah file disalin ke lokasi yang benar, dapat memulai container (jika belum dimulai):

```bash
docker start metabase
```

Ini akan memulai container Metabase dan mengarahkannya ke file **`metabase.db.mv.db`** yang terletak di folder lokal.

**Langkah 5: Akses Metabase**

Setelah container berjalan, dapat mengakses **Metabase** melalui URL berikut di browser:

```
http://localhost:3000
```

**Informasi Login**

Setelah akses Metabase, untuk login, gunakan informasi berikut:

* **Email**: `labibaadinda11@gmail.com`
* **Password**: `root123`

Dengan informasi login ini, pengguna dapat mengakses Metabase dan melihat dashboard serta data dari file **`metabase.db.mv.db`**.

**Langkah 6: Pemecahan Masalah**

Jika file database tidak digunakan dengan benar, periksa hal-hal berikut:

1. **Periksa Log**: dapat memeriksa log untuk melihat kesalahan atau peringatan yang mungkin menunjukkan masalah dengan pemulihan database:

   ```bash
   docker logs metabase
   ```

2. **Izin**: Pastikan izin untuk file **`metabase.db.mv.db`** sudah benar dan bahwa pengguna yang menjalankan container Docker memiliki akses baca dan tulis ke file tersebut.

3. **Direktori Container**: Pastikan file **`metabase.db.mv.db`** berada di folder yang benar di dalam container. Container harus diarahkan ke folder `/metabase.db` tempat file database berada.



## Business Dashboard

Employee Attrition Risk Dashboard dirancang untuk membantu departemen HR dalam melakukan analisis dan monitoring attrition karyawan di perusahaan Jaya Jaya Maju. Dashboard tersebut menampilkan:

### Komponen Visualisasi

| Komponen Visualisasi                     | Deskripsi                                                                 |
| ---------------------------------------- | ------------------------------------------------------------------------- |
| Pie Chart – Distribusi Karyawan          | Menunjukkan proporsi karyawan yang bertahan dan yang Attrition.              |
| Bar Chart – Faktor Penyebab Attrition    | Rata-rata nilai fitur penting seperti usia, pendapatan, jarak rumah, dll. |
| Line Chart – Marital Status  | Jumlah karyawan berdasarkan status pernikahan dan status attrition.       |
| Bar Chart – Gender Distribution          | Jumlah karyawan pria dan wanita berdasarkan status attrition.             |
| Bar Chart – Distribusi Overtime     | Dampak kerja lembur terhadap risiko attrition.                            |
| Bar Chart – Distribusi Job Role          |  Jumlah total bertahan dan attrition karyawan berdasarkan  jenis pekerjaan.          |
| Bar Chart – Employee per Department      | Jumlah total bertahan dan attrition karyawan berdasarkan departemen.               |
| Bar Chart – Attrition by Education Field | Persentase attrition berdasarkan bidang pendidikan terakhir.              |

#### 1. Distribusi Karyawan (Pie Chart)

* Total karyawan: 1.058
* Bertahan: 83.1%
* Attrition: 16.9%

**Insight:** Mayoritas karyawan masih bertahan, namun tingkat attrition sebesar 16.9% menunjukkan adanya potensi risiko yang perlu dipantau secara aktif.

#### 2. Faktor yang Mempengaruhi Attrition

Menampilkan rata-rata dari beberapa fitur penting yang berkorelasi dengan attrition:

* Bertahan : faktor tertinggi employee bertahan karna rata-rata montly income.
* Attrition : faktor tertinggi employee yang keluar karena rata-rata jarak dari rumah.

#### 3. Marital Status 

 Status "Married" memiliki jumlah karyawan terbanyak, namun juga tingkat Attrition yang tinggi.


#### 4. Gender Distribution

* Female: 367 bertahan, 71 Attrition
* Male: 512 bertahan, 108 Attrition

**Insight:** Proporsi pria yang Attrition lebih tinggi dibanding wanita.

#### 5. Distribusi Overtime 
Karyawan dengan lembur memiliki kecenderungan lebih tinggi untuk Attrition. Lembur menjadi salah satu faktor risiko signifikan.

#### 6. Distribusi Job Role
Grafik menunjukkan bahwa **Laboratory Technician** memiliki jumlah karyawan dengan attrition tertinggi (49). **Sales Executive** dan **Sales Representative** memiliki attrition relatif tinggi. Sementara itu, **Research Director** attrition yang terendah.


#### 7. Employee per Department

* Research & Development merupakan departemen dengan jumlah karyawan terbanyak danjumlah attrition yang tinggi.


#### 8. Attrition by Education Field

* Bidang Life Sciences dan Medical mendominasi jumlah karyawan dan attrition tertinggi.

---

#### Akses dan Deployment

Dashboard ini dapat dijalankan menggunakan Docker dan diakses melalui Metabase.

* **Login Metabase:**

  * Username: `labibaadinda11@gmail.com`
  * Password: `root123`

Selain visualisasi, dashboard juga menyediakan tabel prediksi risiko attrition untuk masing-masing karyawan aktif.

Conclusion

Dalam proyek ini, analisis tingkat attrition karyawan pada perusahaan Jaya Jaya Maju dilakukan dengan tujuan untuk memahami faktor-faktor yang mempengaruhi keputusan karyawan untuk mengundurkan diri. Berdasarkan analisis data dan hasil visualisasi yang ditampilkan dalam dashboard, dapat disimpulkan beberapa hal berikut:

#### 1. Analisis dashboard

1. **Tingkat Attrition yang Signifikan**
   >Dari total karyawan yang ada, sebesar 16.9% mengalami attrition, yang menandakan adanya risiko besar terhadap stabilitas dan keberlangsungan operasional perusahaan. Angka ini cukup tinggi dan memerlukan perhatian serius dari pihak HR.

2. **Faktor Penyebab Attrition**
   > Beberapa faktor yang berkontribusi terhadap tingkat attrition antara lain:
      * **Jarak dari rumah karyawan ke kantor** yang lebih jauh berhubungan dengan kecenderungan untuk keluar dari perusahaan.
      * **Karyawan yang sering lembur** memiliki kecenderungan lebih tinggi untuk attrition. Hal ini menunjukkan adanya masalah terkait keseimbangan antara pekerjaan dan kehidupan pribadi.
      * **Tingkat kepuasan kerja** yang rendah, seperti kepuasan terhadap hubungan dengan rekan kerja atau lingkungan kerja, turut mempengaruhi keputusan untuk keluar dari perusahaan.

3. **Departemen dan Posisi Job role yang Paling Terkena Dampak**
    > Departemen **Sales** dan posisi Job Role **Laboratory Technician** mencatatkan tingkat persentase attrition tertinggi, yang menunjukkan bahwa kedua area ini membutuhkan perhatian khusus dalam upaya mempertahankan karyawan.

4. **Keterkaitan dengan Bidang Pendidikan**
    > Bidang Life Sciences dan Medical mendominasi jumlah karyawan dan attrition tertinggi.dibandingkan dengan bidang lainnya, yang mengindikasikan bahwa bidang ini perlu mendapat perhatian lebih dalam mempertahankan karyawan.


#### 2. Pelatihan Model Prediksi
Model terbaik yang digunakan dalam proyek ini adalah LightGBM, dengan hasil evaluasi berikut:

- Accuracy : 0.806604 
- Precision : 0.407407 
- Recall : 0.305556 Recall 
- F1-Score : 0.349206 

Model LightGBM menunjukkan hasil yang baik dengan akurasi tertinggi di antara ketiga model, yaitu 80.66%. Precision-nya juga paling tinggi (40.74%), yang berarti lebih banyak prediksi positif yang benar. Namun, recall-nya sedikit lebih rendah (30.56%) dibandingkan dengan model lainnya, menunjukkan bahwa model ini kurang efektif dalam menangkap kasus positif. F1-Score LightGBM juga lebih baik dari kedua model lainnya (0.349), meskipun masih menunjukkan potensi perbaikan, terutama pada recall. Secara keseluruhan, LightGBM unggul dalam hal akurasi dan precision, tetapi masih perlu penyempurnaan dalam recall dan F1-Score untuk meningkatkan keseimbangan performa model.


### Rekomendasi Action Items (Optional)

Berikut adalah beberapa rekomendasi tindakan yang dapat dilakukan oleh perusahaan guna mengurangi tingkat attrition dan meningkatkan retensi karyawan:

1. **Meningkatkan Program Keseimbangan Kerja dan Kehidupan Pribadi**
    >Karyawan yang sering lembur menunjukkan risiko attrition yang lebih tinggi. Oleh karena itu, perusahaan harus mengevaluasi dan meningkatkan kebijakan terkait waktu kerja dan keseimbangan kerja-kehidupan. Salah satunya dengan menawarkan fleksibilitas jam kerja, atau memperkenalkan program kesejahteraan yang lebih baik.

2. **Penguatan Komunikasi dan Kepuasan Karyawan**
    >Perusahaan perlu memperkuat komunikasi antara manajer dan karyawan, serta mendengarkan masukan terkait kepuasan kerja. Pembinaan yang lebih intensif dan program peningkatan hubungan kerja dapat menurunkan tingkat ketidakpuasan yang dapat mendorong keputusan untuk keluar dari perusahaan.

3. **Perbaikan di Departemen yang Terdampak**
    >Menyasar departemen **Sales** yang memiliki tingkat attrition tinggi dapat membantu mengurangi churn. Ini bisa dilakukan dengan mengevaluasi beban kerja, kompensasi, dan pengembangan karir yang lebih baik bagi karyawan di departemen tersebut.

4. **Fokus pada Karyawan dengan Jarak Tempuh Jauh**
    >Untuk karyawan yang memiliki jarak jauh dari rumah ke kantor, perusahaan bisa mempertimbangkan untuk menyediakan opsi kerja jarak jauh atau memberikan tunjangan transportasi yang lebih baik.

5. **Pengembangan Program Retensi untuk Posisi Tertentu**
    >Karyawan di posisi **Laboratory Technician** perlu mendapatkan perhatian lebih terkait kebijakan retensi dan pengembangan karir. Menawarkan pelatihan dan kesempatan promosi dapat membantu mereka merasa lebih dihargai dan memiliki prospek jangka panjang di perusahaan.


