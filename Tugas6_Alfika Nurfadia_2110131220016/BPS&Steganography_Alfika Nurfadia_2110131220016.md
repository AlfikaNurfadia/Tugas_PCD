### Nama : ALFIKA NURFADIA
### NIM : 2110131220016
---
# Bit-Plane Slicing & Steganography
## Bit-Plane Slicing
Bit-Plane Slicing merupakan metode yang digunakan untuk melihat kontribusi atau pengaruh dari setiap bit penyusun citra. Untuk citra 8 bit, pada dasarnya tiap intesitas yang nilainya dalam format desimal, bisa dipecah menjadi bit-bit dalam format biner.

Misalnya, senuah piksel dengan intensitas 245 (desimal) dan dijadikan biner adalah 11110101. Denganb nilai LSB ( Least Significant Bit) berada di paling kanan, dan sebaliknya untuk MSB (Most Significant Bit). Pada gambar dibawah yang merupakan ilustrasi dari bit slicing pada piksel citra.

<p align="center"><img src="MSB-LSB.JPG"></p><br>
<p align="center"><img src="MSB-LSB1.JPG"></p><br>

### Cara Implementasi Bit-Plane Slicing Menggunakan OCTAVE

- Code pada octave untuk Bit-Plane Slicing
<p align="center"><img src="codeBPS.JPG"></p><br> 

- Foto awal dan dibuat gray Scale
<p align="center"><img src="paprikaa.JPG"></p>
<p align="center"><img src="gray.png"></p><br>

- Hasil Bit-Plane Slicing
<p align="center"><img src="hasilBPS.JPG"></p><br>

### Menggabungkan 2 Gambar lalu di Bit-Plane Slicing 
- Code pada octave untuk menggabungkan gambar
<p align="center"><img src="codegabunggambar.JPG"></p><br>

- Gambar yang digabungkan
<p align="center"><img src="gray.png"><br>Gambar 1</p>
<p align="center"><img src="lenagray.JPG"><br>Gambar 2</p><br>

- Hasil gambar yang digabungkan
<p align="center"><img src="GabunganGambar.JPG"></p><br>

- Code pada octave untuk Bit-Plane Slicing foto yang telah digabungkan
<p align="center"><img src="codegabungBPS.JPG"></p><br>

- Hasil Bit-Plane Slicing dari gambar yang digabung
<p align="center"><img src="BPSgabungan.JPG"></p><br>

---

## Steganography

Steganografi adalah seni dan ilmu menulis pesan tersembunyi atau menyembunyikan pesan dengan suatu cara sehingga selain si pengirim dan si penerima, tidak ada seorang pun yang mengetahui atau menyadari bahwa ada suatu pesan rahasia.

Tujuan dari steganografi adalah merahasiakan atau menyembunyikan keberadaan dari sebuah pesan atau sebuah informasi penting. Dalam praktiknya, kebanyakan pesan disembunyikan dengan membuat perubahan tipis terhadap data digital lain yang isinya tidak akan menarik perhatian dari penyerang potensial, sebagai contoh sebuah gambar yang terlihat tidak berbahaya. Perubahan ini bergantung pada kunci (sama pada kriptografi) dan pesan untuk disembunyikan. Orang yang menerima gambar kemudian dapat menyimpulkan informasi terselubung dengan cara mengganti kunci yang benar ke dalam algoritma yang digunakan.


### Cara Implementasi Steganography Menggunakan OCTAVE

- Code pada octave untuk membuat steganography
<p align="center"><img src="codestega1.JPG"></p>
<p align="center"><img src="codestega2.JPG"></p><br>

- Gambar awal
<p align="center"><img src="gray.png"></p><br>

- Setelah di Steganography
<p align="center"><img src="Stego.png"><br></p>
Setelah di steganorafi, gambar tidak ada terjadi  perubahan karena text diletakkan di lapisan paling bawah atau Least Significant Bit(LSB) sehingga tidak terlalu signifikan atau berpengaruh.
Untuk melihat gambarnya telah ada text, bisa di cek lagi, apabila ada text maka pixelnya akan berubah warna menjadi putih, seperti dibawah ini
<p align="center"><img src="hasil.png"><br></p>






