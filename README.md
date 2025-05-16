# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan *Jaya jaya institut*

## ***Business Understanding***

Jaya Jaya Institut merupakan salah satu institusi pendidikan perguruan berciri khas *EduTech* yang telah berdiri sejak tahun 2000. Hingga saat ini ia telah mencetak banyak lulusan dengan reputasi yang sangat baik. 


## **Permasalahan Bisnis**

Akan tetapi, terdapat banyak juga siswa yang tidak menyelesaikan pendidikannya alias *dropout*.

Jumlah *dropout* yang tinggi ini tentunya menjadi salah satu masalah yang besar untuk sebuah institusi pendidikan. Oleh karena itu, Jaya Jaya Institut ingin mendeteksi secepat mungkin siswa yang mungkin akan *dropout* sehingga dapat diberi bimbingan khusus.


## **Cakupan Proyek**

Untuk mengatasi permasalahan *dropout* siswa dalam pendidikannya, kita akan melakukan Analisa menggunakan python seperti Data Understanding, EDA, Data Preparation, serta modeling. dan membuat dashboard untuk menganalisa deskriptif dengan beberapa pertanyaan berikut:
1. Siapa saja mahasiswa yang paling sering dropout?
2. Apakah nilai akademik punya korelasi dengan dropout?
3. Apakah faktor keuangan atau latar belakang keluarga memengaruhi dropout?
4. Apakah jadwal belajar (pagi/malam) mempengaruhi dropout?
5. Apakah cara dan urutan pendaftaran berkaitan dengan dropout?


## **Persiapan**

Sumber data pelatihan: 
https://drive.google.com/file/d/1_qoM_pf4oG83codHrgxSfiVbeuWek1Hc/view?usp=drive_link

## Setup environment:
Agar proyek ini terisolasi dengan dependensinya, buat virtual environment.

Membuat virtual environment:
```
bash
Salin
Edit
python -m venv venv
```

Mengaktifkan virtual environment:
Di Windows:
```
bash
Salin
Edit
.\venv\Scripts\activate
```

Di macOS/Linux:
```
bash
Salin
Edit
source venv/bin/activate
```

*Setup environment - Shell/Terminal*:
```
mkdir stud-perfom
cd stud-perfom
pipenv install
pipenv shell
pip install -r requirements.txt
```

*Setup environment - Anaconda*:
```
conda create --name stud-perfom python=3.11.12
conda activate stud-perfom
pip install -r requirements.txt
```


## ***Business Dashboard***

Dashboard ini dibuat untuk membantu tim HR memahami faktor-faktor yang mempengaruhi tingginya dropout di Jaya Jaya institut, serta memberikan insight berbasis data agar keputusan yang diambil lebih tepat sasaran.

```
https://lookerstudio.google.com/u/0/reporting/9eb5a74b-e590-47c9-93d8-dac228982b06
```

## ***Menjalankan Sistem Machine Learning***
Prototype Sistem Machine Learning ini dibuat dengan Streamlit yang dapat diakses pada link berikut ini:

```
https://studentperformance-ckksz9gnanpqhfyhwva7dc.streamlit.app
```

## ***Conclusion***

- Komposisi siswa terdiri dari 66% Laki-laki dan 34% Perempuan.
- Dari 3.630 siswa yang berhasil lulus (*Graduation Rate*) sebesar 60.9% sedangkan yang tidak lulus (*Dropout Rate*) sebesar 39,1% 
- tingkat ketidaklulusan siswa laki laki 56,1% dan siswa perempuan 30,2%.
- Dari 969 penerima beasiswa terdapat 134 siswa yang *dropout* (13,8%) dan 835 siswa yang berhasil lulus (86.2%)
- Dari 1993 siswa yg mengungsi, 1.324 siswa lulus (66,4%) dan 669 siswa *dropout* (33,6%)
- Dari 1.421 siswa yang *dropout* terdapat 1.214 siswa (85.4%) yang mengikuti kelas pagi dan 207 siswa (14.57%) yang mengikuti kelas malam
- faktor *curricular units* dan *tuition fees* juga cukup berpengaruh pada tingkat kelulusan siswa.


### **Rekomendasi *Action Items***

Beberapa rekomendasi *action items* yang harus dilakukan institusi guna menyelesaikan permasalahan atau mencapai target mereka.
1. Identifikasi Dini Mahasiswa Berisiko Tinggi. Buat sistem “Early Alert” untuk menghubungi mahasiswa berisiko.
2. Intervensi Keuangan. Tawarkan cicilan ringan, subsidi, atau pengingat otomatis.
3. Bimbingan Akademik Personal. Wajibkan sesi bimbingan rutin untuk mahasiswa semester 1 & 2 dengan nilai rendah.
