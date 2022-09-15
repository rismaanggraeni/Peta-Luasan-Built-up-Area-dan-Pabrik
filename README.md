# Peta-Luasan-Built-up-Area-dan-Pabrik

Pembuatan peta penutup lahan diawali dengan klasifikasi penutup lahan menggunakan Citra Landsat 8 yang ter-filter dengan algoritma cloud masking. Cloud masking dilakukan karena tidak sepanjang tahun Pulau Jawa memiliki tutupan awan yang sedikit. Pengolahan algoritma cloud masking menggunakan dataset Citra Landsat 8 dengan perekaman sepanjang tahun 2019 hingga 2020 dengan bantuan Google Earth Engine (GEE). Skema klasifikasi penutup lahan terdiri atas 5 kelas penutup lahan yaitu vegetasi tegakan RTH, vegetasi non tegakan RTH, lahan terbangun, lahan terbuka dan tubuh air. Klasifikasi penutup lahan menggunakan SVM (Support Vector Machine) dengan komposit warna true color standard RGB 432 pada Citra Landsat 8. 

![sampel](https://user-images.githubusercontent.com/78722448/190323167-184e1d24-a138-4be2-9ae3-713f3e03ca5b.png)
Gambar 1 : Sebaran titik sampel untuk SVM di Kota Semarang

Penentuan titik sampel dilakukan secara random sampling, dimana jumlah sampel di setiap kelas penutup lahan memiliki jumlah yang seimbang. Titik sampel nantinya akan dibagi dua ke dalam training data dan testing data, dengan porsi 70% untuk training data dan 30% untuk testing data. Intepretasi setiap penutup lahan dilakukan saat pemilihan titik sampel untuk klasifikasi

![semarang](https://user-images.githubusercontent.com/78722448/190323419-64f65b1d-f954-41c0-9a63-6184a9f8f21f.jpg)
                    Gambar 2 : Peta Luasan Built-up Area dan Pabrik, Kota Semarang
