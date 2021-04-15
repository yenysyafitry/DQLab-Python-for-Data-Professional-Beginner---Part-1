<p align="justify"><b>Python</b> adalah bahasa pemrograman yang ditujukan untuk general-purpose programming dan termasuk dalam kategori high-level programming language.</br>
Sebagai general-purpose programming language, Python digunakan untuk berbagai macam permasalahan seperti: pengembangan aplikasi web ataupun mobile, data science, dll.</br>
Python masuk ke dalam kategori high-level programming language dikarenakan bahasa pemrograman Python yang mudah untuk dibaca dan dituliskan oleh manusia.</br>
Bahasa  pemrograman  Python  diciptakan  oleh Guido van Rossum dan pertama kali diperkenalkan pada tahun 1991 sebagai sebuah proyek open-source.
Sifat open-source dari Python mengartikan bahwa setiap orang dapat mengembangkan program komputer dengan menggunakan bahasa pemrograman Python baik untuk tujuan komersil/non-komersil.</p>
<p align="justify"> Bahasa pemrograman Python bersifat dynamically typed (Python akan secara otomatis mengubah masukan dari pengguna) dan mendukung berbagai paradigma pemrograman baik pemrograman secara prosedural, berbasis objek (Object-Oriented), atau pun fungsional.
</br>Selain alasan di atas terdapat beberapa alasan lain untuk menggunakan bahasa pemrograman Python: </p>
<ol><li>Python dikembangkan untuk bersifat extendible yang mengartikan bahwa Python dapat dikembangkan untuk berbagai macam tugas baik untuk pembuatan aplikasi web atau pun desktop, proses analisis data, dll.</li>
<li>Python memiliki komunitas yang besar yang secara aktif berkontribusi untuk menyediakan berbagai macam fungsionalitas (third-party libraries). Third-party libraries yang tersedia dalam bahasa pemrograman Python memungkinkan para pengembang untuk dapat fokus menyelesaikan permasalahan yang ada. Per Januari 2020, terdapat 214,922 modul third-party yang dapat kita gunakan secara cuma-cuma.</li>
<li>Python terintegrasi dengan baik dengan berbagai macam bahasa pemrograman dan layanan enterprise. Untuk bagian-bagian yang melibatkan sumber daya komputasi yang besar, pengembang dapat menggunakan fungsionalitas dalam bahasa pemrograman lainnya yang bersifat low-level yang telah dikemas ke dalam fungsionalitas Python.</li></ol>
<p align="justify">
Fungsi Python yang akan pertama kali aku pelajari adalah fungsi print().
Dengan fungsi print(), aku dapat menampilkan pesan ke layar pengguna.</p>

<details align="justify"> <summary>print("Hello World!")</br></br>
</summary><table align="justify"><i>Output : </br>Hello World!</i></table></details>
<p align="justify">
Keren! Aku baru tahu kalau Python memiliki fungsi print() yang berguna untuk menampilkan pesan ke layar pengguna. Ayo kita menampilkan kalimat “Halo Dunia” dan “Riset Bahasa Python” menggunakan fungsi Print ().</p>

<details align="justify"> <summary>print("Halo Dunia")</br>
print("Riset Bahasa Python")</br></br>
</summary><table align="justify"><i>Output : </br>Halo Dunia</br>
Riset Bahasa Python</i></table></details>

<details align="justify"> <summary><b>Struktur Program Python - Part 1</b></br>#Statement</br>
print("Belajar Python menyenangkan") </br>
print("Halo Dunia")</br>
print("Hello World!")</br>
#Variables & Literals</br>
bilangan1 = 5</br>
bilangan2 = 10</br>
kalimat1 = "Belajar Bahasa Python"</br>
#Operators</br>
print(bilangan1 + bilangan2)</br></br>
</summary><table align="justify"><i>Output : </br>Belajar Python menyenangkan</br>
Halo Dunia</br>
Hello World!</br>
15</i></table></details>

<details align="justify"> <summary><b>Tugas Praktek</b></br> <i>bilangan1 = 20</br>
bilangan2 = 10</br>
print(bilangan1 - bilangan2)</i></br></br>
</summary><table align="justify"><i>Output : </br>10</i></table></details>

<details align="justify"> <summary><b>Tugas Praktek</b></br>Tugas:</br>
Aku diminta menghitung harga_setelah_potongan dan harga_final dengan mengalikan harga_setelah_potongan dengan angka 1.1 karena jumlah PPN sebesar 10% (100% + 10% = 110% atau 1.1)</br>
Aku menggunakan variabel harga_asli dengan nilai 20000 dan variabel potongan dengan nilai 2000.</br></br>harga_asli = 20000</br>
potongan = 2000</br>
harga_setelah_potongan = harga_asli - potongan</br>
harga_final = harga_setelah_potongan * 1.1</br>
print(harga_final)</br></br>
</summary><table align="justify"><i>Output : </br>19800.0</i></table></details>

<details align="justify"> <summary><b>Sequence Type – Part 1</b></br>Tipe data ini digunakan untuk menampung sekumpulan data secara terorganisir.</br>
List dan tuple merupakan bentuk dari tipe data sequence.</br>
Pada part 1 ini, aku akan mempelajari tipe data list terlebih dahulu.</br>
Tipe data list diawali dengan tanda kurung siku buka ( [ ), memisahkan setiap elemen di dalamnya dengan tanda koma ( , ) dan ditutup dengan kurung siku tutup ( ] ). Sebagai contoh:</br></br>contoh_list = [1, 'dua', 3, 4.0,5]</br>
print(contoh_list[0])</br>
print(contoh_list[3])</br>
contoh_list = [1, 'dua', 3, 4.0,5]</br>
contoh_list[3] = 'empat'</br>
print(contoh_list[3])</br>
</summary><table align="justify"><i>Output : </br>1</br>
4.0</br>
empat</i></table></details>

<p align="justify"> <b>Sequence Type – Part 2</b></br>Setelah mempelajari tipe data list. Aku mempelajari tipe data tuple. Tipe data tuple juga berfungsi untuk menampung sekumpulan data. Tipe data tuple diawali dengan tanda kurung buka ( ( ), memisahkan setiap elemen di dalamnya dengan tanda koma ( , ) dan ditutup dengan tanda kurung tutup ( ) )</br> </br> contoh_tuple = ('januari', 'februari', 'maret', 'april')</br> 
print(contoh_tuple[0])</br> 
contoh_tuple = ('januari', 'februari', 'maret', 'april')</br> 
contoh_tuple[0] = 'Desember'</p>


<details align="justify"> <summary><b>Set Type</b></br>Serupa dengan tipe data sequence, tipe data set digunakan untuk menampung sekumpulan data dengan tipe lainnya. Terdapat dua jenis dari tipe data set yaitu, set dan frozenset.</br>
Tipe data set diawali dengan tanda kurung buka kurawal ( { ), memisahkan setiap elemen di dalamnya dengan tanda koma ( , ) dan ditutup dengan tanda kurung tutup ( } ). Namun, berbeda dengan tipe data sequence, seperti list, tipe data objek tidak mengizinkan adanya elemen dengan nilai yang sama dan tidak memperdulikan urutan dari elemen.
Sebagai contoh:</br></br><i> contoh_list = ['Dewi', 'Budi', 'Cici', 'Linda', 'Cici']</br>
print(contoh_list)</br>
contoh_set = {'Dewi', 'Budi', 'Cici', 'Linda', 'Cici'}</br>
print(contoh_set)</br>
contoh_frozen_set = ({'Dewi', 'Budi', 'Cici', 'Linda', 'Cici'})</br>
print(contoh_frozen_set)</i> </br>
</summary><table align="justify"><i>Output : </br> ['Dewi', 'Budi', 'Cici', 'Linda', 'Cici'] </br>
{'Dewi', 'Cici', 'Linda', 'Budi'} </br>
{'Dewi', 'Cici', 'Linda', 'Budi'}</i></table></details>

<details align="justify"> <summary><b>Mapping Type</b></br>Tipe data mapping dapat digunakan untuk memetakan sebuah nilai ke nilai lainnya. Dalam Python, tipe data mapping disebut dengan istilah dictionary. Tipe data dictionary dapat dideklarasikan dengan diawali oleh tanda kurung buka kurawal ( { ), memisahkan setiap elemen di dalamnya dengan tanda koma ( , ) dan ditutup dengan tanda kurung tutup ( } ). Setiap elemen pada tipe data dictionary dideklarasikan dengan format:</br></br>person = {'nama': 'John Doe', 'pekerjaan': 'Programmer'}</br>
print(person['nama'])</br>
print(person['pekerjaan'])</br>
</summary><table align="justify"><i>Output : </br>John Doe</br>
Programmer </i></table></details>

<details align="justify"> <summary><b>Tugas Praktek</b></br></br><i>sepatu = {"nama": "Sepatu Niko", "Harga": 150000, "diskon": 30000 }
baju = {"nama": "Baju Unikloh", "Harga": 80000, "diskon": 8000 }
Celana = {"nama": "Celana Lepis", "Harga": 200000, "diskon": 60000 }</i></br>
</summary><table align="justify"><i>Output : </br></i>
<tr><td>Nama Barang</td><td>Harga</td><td>Diskon</td></tr>
<tr><td>Sepatu Niko</td><td>150000</td><td>30000</td></tr>
<tr><td>Baju Unikloh</td><td>80000</td><td>8000</td></tr>
<tr><td>Celana Lepis</td><td>200000</td><td>60000</td></tr>
</table></details>

<p align="justify"> <b>Tugas Praktek</b></br>Setelah berhasil merepresentasikan setiap barang ke dalam tipe data dictionary dengan variabel nama, harga, dan diskon, langkahku selanjutnya adalah: mendeklarasikan list dengan nama daftar_belanja yang berisi data sepatu, baju, dan celana</br></br>sepatu = {"nama": "Sepatu Niko", "harga": 150000, "diskon": 30000} </br>
baju = {"nama": "Baju Unikloh", "harga": 80000, "diskon": 8000} </br>
celana = {"nama": "Celana Lepis", "harga": 200000, "diskon": 60000} </br>
daftar_belanja = [sepatu,baju,celana]
<p>

<details align="justify"> <summary><b>Tugas Praktek</b>Dengan data yang aku miliki, aku bisa menghitung total harga jual dengan potongan harga dengan pajak sebesar 10% dari nilai jual.</br></br># Data yang dinyatakan ke dalam dictionary</br>
sepatu = {"nama": "Sepatu Niko", "harga": 150000, "diskon": 30000} </br>
baju = {"nama": "Baju Unikloh", "harga": 80000, "diskon": 8000} </br>
celana = {"nama": "Celana Lepis", "harga": 200000, "diskon": 60000}</br>
# Hitunglah harga masing-masing data setelah dikurangi diskon</br>
harga_sepatu = sepatu["harga"] - sepatu["diskon"] </br>
harga_baju = baju["harga"] - baju["diskon"]</br>
harga_celana = celana["harga"] - celana["diskon"]</br>
# Hitung harga total</br>
total_harga = harga_sepatu + harga_baju + harga_celana</br>
# Hitung harga kena pajak</br>
total_pajak = total_harga * 0.1</br>
# Cetak total_harga + total_pajak</br>
print(total_harga + total_pajak)</br>
</summary><table align="justify"><i>Output : </br>365200.0</i></table></details>

<details align="justify"> <summary><b>Nilai Prioritas Operator dalam Python – Part 1</b></br>Sebagai contoh, untuk menuliskan sebuah program menghitung diskon dan pajak pembelian, berdasarkan ilmu yang telah aku pelajari, aku dapat menuliskannya dengan potongan kode berikut</br></br>#Kode awal</br>
total_harga = 150000</br>
potongan_harga = 0.3</br>
pajak = 0.1 # pajak dalam persen ~ 10%</br>
harga_bayar = 1 - 0.3 # baris pertama</br>
harga_bayar *= total_harga # baris kedua</br>
pajak_bayar = pajak * harga_bayar # baris ketiga</br>
harga_bayar += pajak_bayar # baris ke-4</br>
print("Kode awal - harga_bayar=", harga_bayar)</br>
#Penyederhanaan baris kode dengan menerapkan prioritas operator</br>
total_harga = 150000</br>
potongan_harga = 0.3</br>
pajak = 0.1 # pajak dalam persen ~ 10%</br>
harga_bayar = (1-0.3) * total_harga #baris pertama </br>
harga_bayar += harga_bayar * pajak # baris kedua</br>
print("Penyederhanaan kode - harga_bayar=", harga_bayar)</br>
</summary><table align="justify"><i>Output : </br></br>Kode awal - harga_bayar= 115500.0</br>
Penyederhanaan kode - harga_bayar= 115500.0</i></table></details>

<details align="justify"> <summary><b>Menampilkan suatu data dari baris dan kolom tertentu</b></br>
</summary><table align="justify"><i>Output : </br></i></table></details>
<details align="justify"> <summary><b>Menampilkan suatu data dari baris dan kolom tertentu</b></br>
</summary><table align="justify"><i>Output : </br></i></table></details>

<details align="justify"> <summary><b>Menampilkan suatu data dari baris dan kolom tertentu</b></br>
</summary><table align="justify"><i>Output : </br></i></table></details>

<details align="justify"> <summary><b>Menampilkan suatu data dari baris dan kolom tertentu</b></br>
</summary><table align="justify"><i>Output : </br></i></table></details>

<details align="justify"> <summary><b>Menampilkan suatu data dari baris dan kolom tertentu</b></br>
</summary><table align="justify"><i>Output : </br></i></table></details>

<details align="justify"> <summary><b>Menampilkan suatu data dari baris dan kolom tertentu</b></br>
</summary><table align="justify"><i>Output : </br></i></table></details>

<details align="justify"> <summary><b>Menampilkan suatu data dari baris dan kolom tertentu</b></br>
</summary><table align="justify"><i>Output : </br></i></table></details>

<details align="justify"> <summary><b>Menampilkan suatu data dari baris dan kolom tertentu</b></br>
</summary><table align="justify"><i>Output : </br></i></table></details>

<details align="justify"> <summary><b>Menampilkan suatu data dari baris dan kolom tertentu</b></br>
</summary><table align="justify"><i>Output : </br></i></table></details>
