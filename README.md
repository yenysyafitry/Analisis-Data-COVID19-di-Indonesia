<p align="justify"><b>Data wrangling</b> adalah proses membaca data dari berbagai sumber dan merubah isi dan struktur sehingga dapat digunakan untuk analisa. Data preparation atau data wrangling adalah proses yang memakan waktu dan tenaga paling besar bagi seorang data scientist, yaitu sampai 80 persen. Detilnya, pembacaan sumber data memakan waktu sampai 20 persen, dan mengorganisasikan dan membersihkan data memakan waktu sampai 60 persen.</p>


<ol>Kenapa data wrangling sangat penting dilakukan?
  <li>Data dapat dimanfaatkan lebih jauh oleh bisnis</li>
  <li>Mengurangi kesempatan bisnis yang hilang (opportunity lost)</li>
  <li>Antar sistem lebih mudah "berbicara" karena dapat diintegrasikan dengan lebih baik</li></ol>
  
<ol>Apa saja aktivitas-aktivitas yang termasuk di dalam data wrangling?
  <li>Membersihkan data</li>
  <li>Menambah kolom data</li>
  <li>Menyatukan dua dataset</li>
  <li>Menyatukan dua dataset</li>
  <li>Memisahkan kolom data</li></ol>
  
  <ol>Mana aktivitas berikut yang tidak termasuk di dalam data wrangling?
<li>Menjaga keamanan data</li>
<li>Menganalisa 10 nilai penjualan tertinggi</li></ol>

<ol>Kenapa kita memerlukan representasi Missing Value? 
  <li>Agar kita bisa membuang data yang tidak relevan</li>
  <li>Agar data tersebut bisa diisi dengan nilai lain</li>
  <li>Agar kita dapat membedakan antara data yang hilang dan hasil operasi matematika yang tidak mungkin dilakukan</li></ol>


<p align="justify"><b>NA (Not Available)</b></br><b>NA</b> adalah representasi utama dari missing value di R, dan merupakan suatu nilai atomik. Artinya posisi NA sama dengan contoh nilai-nilai atomik bilangan seperti 1, 2 atau 100. Juga sama dengan contoh nilai karakter seperti "a", "b",  atau "g". Karena angka dan karakter seperti contoh di atas sering disebut sebagai konstanta, maka NA adalah konstanta untuk missing value. </br></p>
  <ui>Dengan demikian, secara singkat NA adalah:
<li>Representasi missing value</li><li>Merupakan konstanta atau nilai atomik </li>
NA tidak bisa digunakan sebagai variable karena merupakan keyword, dan perhatikan penulisan NA dimana kedua karakter adalah huruf besar.<ui></br>

<p align="justify"><b>NULL dan Vector</b></br>Berikut adalah contoh variabel vector yang mengandung 7 elemen termasuk NA dan NULL.
<details>
  <summary>isi.vector </br><- c(1, 2, 3, NA, 5, NULL, 7)</br>length(isi.vector)</summary>
  <table border="0"><tr><td><i>Output :</i></td><td>> isi.vector <- c(1, 2, 3, NA, 5, NULL, 7)</br>> length(isi.vector)</br>[1] 6</td></tr></table>
</details>
Hasilnya adalah 6, padahal kita memasukkan 7 elemen. Dengan demikian terlihat bahwa NULL memang mewakili undefined object dan tidak dianggap oleh vector. Dengan demikian tidak menjadi bagian dari vector.</p>

