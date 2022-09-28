### Nama : ALFIKA NURFADIA
### NIM : 2110131220016
---
# Tiga Metode Algoritma Mengubah Nilai R G B Menjadi Grayscale

Berdasarkan catatan dokumentasi GIMP, dapat kita telusuri bahwa terdapat tiga macam metode algoritma untuk mengubah nilai R G B menjadi Grayscale.

1. Lightness <br>
    Algoritmanya adalah mencari nilai tertinggi dan terendah dari nilai R G B, kemudian nilai tertinggi dan terendah tersebut dijumlahkan lantas dikalikan dengan 0.5. Secara matematis dapat dirumuskan : <br>
    **Grayscale = (max(R,G,B)) + (min(R,G,B)) * 0.5**


2. Average <br>
    Algoritmanya adalah dengan menjumlahkan seluruh nilai R G B, kemudian dibagi 3, sehingga diperoleh nilai rata-rata dari R G B, nilai rata-rata itulah yang dapat dikatakan sebagai grayclase. Rumus matematisnya adalah : <br>
    **Grayscale = (R + G + B) / 3**


3. Luminosity <br>
    Algoritmanya adalah dengan mengalikan setiap nilai R G B dengan konstanta tertentu yang sudah ditetapkan nilainya, kemudian hasil perkalian seluruh nilai R G B dijumlahkan satu sama lain. Rumus matematisnya adalah : <br>
    **Grayscale = (0.21 * R) + (0.72 * G) + (0.07 * B)**



## Berikut Cara Implementasinya Menggunakan MATLAB
<p align="center"><img src="img/grayscale.JPG" width="200px">

1. Lightness Method
    <p align="center"><img src="img/lightness.JPG" width="200px">
1. Average Method
    <p align="center"><img src="img/average.JPG" width="200px">
1. Luminosity Method
    <p align="center"><img src="img/luminosity.JPG" width="200px">


