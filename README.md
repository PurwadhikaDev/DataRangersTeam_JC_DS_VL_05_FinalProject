# Machine Learning Model for Predicting Used Car Price in UK
![alt text](https://github.com/PurwadhikaDev/DataRangersTeam_JC_DS_VL_05_FinalProject/blob/main/Picture/jpeg%20awal.jpg?raw=true)
## CONTEXT

Di tengah menurunnya pasokan mobil baru di Inggris Raya dikarenakan minimnya pasokan semikonduktor, banyak pelanggan mobil yang mulai beralih ke mobil bekas. Hal ini ditunjukkan dari data Society of Motor Manufacturers and Traders (SMMT) pertumbuhan penjualan mobil baru yang hanya 1% pada tahun 2021 dibandingkan dengan mobil bekas yang sebesar 11.5% (SMMT. https://www.smmt.co.uk/category/vehicle-data/used-car-sales-data/).
PT ABC adalah salah satu lembaga showroom mobil bekas yang berperan sebagai pihak yang membeli mobil bekas dari penjual mobil bekas, baik itu perorangan maupun lembaga dan menjual mobil bekas tersebut kepada calon pembeli. PT ABC akan melakukan penilaian harga mobil bekas yang akan dijual dan juga melakukan inspeksi dan kurasi untuk memeriksa keadaan mobil. PT ABC mengambil keuntungan 5% dari selisih harga beli dan harga jual mobil bekas.
Di tengah aktivitas pasar mobil bekas yang terus meningkat, PT ABC ingin dapat mendapat gambaran harga pasar mobil bekas yang akurat. Tim Data Analyst Rangers PT ABC bertugas untuk memprediksi harga mobil bekas sesuai dengan kebutuhan PT ABC.

## PROBLEM STATEMENT

Di tengah aktivitas pasar mobil bekas yang terus meningkat, kepercayaan konsumen menjadi sangat penting. Bila harga yang dinilai oleh PT ABC tidak akurat, maka konsumen mobil bekas akan beralih ke pesaing lainnya, sehingga PT ABC akan menderita kerugian.

## GOALS

Berdasarkan permasalahan tersebut, perusahaan ingin menilai harga mobil bekas dengan sebaik mungkin agar kepercayaan konsumen meningkat dan akhirnya PT ABC menjadi top of mind tempat jual beli mobil bekas.

## METRIC EVALUATION

Evaluasi metrik yang akan digunakan adalah MAPE, dimana MAPE adalah rataan persentase error yang dihasilkan oleh model regresi. Semakin kecil nilai MAPE yang dihasilkan, berarti model semakin akurat dalam memprediksi harga mobil bekas.

Selain itu, kita juga bisa menggunakan nilai R-squared (R2). Nilai R-squared digunakan untuk mengetahui seberapa baik model dapat merepresentasikan varians keseluruhan data. Semakin mendekati 1, maka semakin fit pula modelnya terhadap data observasi.

## Data Understanding

![alt text](https://github.com/PurwadhikaDev/DataRangersTeam_JC_DS_VL_05_FinalProject/blob/main/Picture/Data%20understanding.png?raw=true)

## EDA Overview

![alt text](https://github.com/PurwadhikaDev/DataRangersTeam_JC_DS_VL_05_FinalProject/blob/main/Picture/Merk%20mobil.png?raw=true)
Terlihat dari grafik di atas, mobil bekas yang paling banyak terjual di Inggris adalah merk **Ford** diikuti oleh merk **VW**.

![alt text](https://github.com/PurwadhikaDev/DataRangersTeam_JC_DS_VL_05_FinalProject/blob/main/Picture/Model%20mobil.png?raw=true)
Berdasarkan grafik diatas, terlihat model **Ford Fiesta** menjadi model yang paling banyak terjual. Selain itu, hampir semua model yang paling banyak terjual masuk ke kategori mobil kecil dan juga city car, kecuali **Mercedes C-Class** yang termasuk ke dalam kategori mobil mewah.

