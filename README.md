# Nama : Roswanda Nuraini

# NIM : 312210328

# Kelas : TI.22.A.3

![lowongan](https://user-images.githubusercontent.com/115516632/213033199-aa73068e-3069-474c-831c-5eca930ddea7.png)

# Penjelasan 

!pip install pandas digunakan untuk menginstall package pandas di python. Package pandas digunakan untuk memanipulasi data dalam bentuk tabel (dataframe) dan digunakan untuk data analysis. Fungsi dari package pandas sangat luas, seperti melakukan operasi pada data, mengimport dan mengeksport data dari berbagai format, dan lainnya. !pip install requests digunakan untuk menginstall package requests di python. Package requests digunakan untuk melakukan HTTP request dari python.

!pip install BeautifulSoup4 digunakan untuk menginstall package BeautifulSoup4 di python. Package BeautifulSoup4 digunakan untuk parsing dan mengelola data dari HTML atau XML.

import pandas as pd digunakan untuk mengimport library pandas dan menyebutnya sebagai pd. Library pandas digunakan untuk memanipulasi data dalam bentuk tabel (dataframe) dan digunakan untuk data analysis.

from bs4 import BeautifulSoup digunakan untuk mengimport class BeautifulSoup dari package BeautifulSoup4. Class BeautifulSoup digunakan untuk mengelola dan mengolah data dari HTML atau XML. 

![lowongan 2](https://user-images.githubusercontent.com/115516632/213033347-d9744c26-8b84-43e3-8a87-cd09427de5bb.png)

# Penjelasan 

mengambil data lowongan kerja dari situs web Glints. Dengan menggunakan library Python 'requests', kodingan mengirim permintaan GET ke URL "https://glints.com/id/lowongan-kerja" yang merupakan halaman web yang berisi informasi lowongan kerja. Kemudian, dengan menggunakan library 'BeautifulSoup', kodingan menganalisis konten halaman web yang didapat dari permintaan GET tersebut dengan menggunakan parser HTML.

Selanjutnya, kodingan mencari semua elemen HTML dengan atribut 'div' dan 'id' yang sesuai, yaitu '__next'. Kemudian, dari elemen-elemen tersebut, kodingan mengekstrak informasi pekerjaan, lokasi, dan nama perusahaan dengan mencari elemen yang memiliki atribut 'class' yang sesuai. Informasi yang diambil kemudian disimpan dalam sebuah list yang sesuai.

Setelah itu, kodingan menggunakan library pandas untuk membuat dataframe dari list yang didapat dan menyimpannya dalam variabel 'df'. Kemudian kodingan mencetak dataframe tersebut, sehingga kita dapat melihat informasi lowongan kerja yang diambil dari situs web Glints.

# Output

![lowongan 2](https://user-images.githubusercontent.com/115516632/213033538-995c62e8-fa2f-4c54-a9a3-e559d436e33b.png)
