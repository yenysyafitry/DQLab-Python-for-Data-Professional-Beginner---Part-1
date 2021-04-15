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

<details align="justify"> <summary>print("Hello World!")</br>
</summary><table align="justify"><i>Output : </br>Hello World!</i></table></details>
<p align="justify">
Keren! Aku baru tahu kalau Python memiliki fungsi print() yang berguna untuk menampilkan pesan ke layar pengguna. Ayo kita menampilkan kalimat “Halo Dunia” dan “Riset Bahasa Python” menggunakan fungsi Print ().</p>

<details align="justify"> <summary>print("Halo Dunia")</br>
print("Riset Bahasa Python")</br>
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
print(contoh_list[3])</br></br>
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
print(contoh_frozen_set)</i> </br></br>
</summary><table align="justify"><i>Output : </br> ['Dewi', 'Budi', 'Cici', 'Linda', 'Cici'] </br>
{'Dewi', 'Cici', 'Linda', 'Budi'} </br>
{'Dewi', 'Cici', 'Linda', 'Budi'}</i></table></details>

<details align="justify"> <summary><b>Mapping Type</b></br>Tipe data mapping dapat digunakan untuk memetakan sebuah nilai ke nilai lainnya. Dalam Python, tipe data mapping disebut dengan istilah dictionary. Tipe data dictionary dapat dideklarasikan dengan diawali oleh tanda kurung buka kurawal ( { ), memisahkan setiap elemen di dalamnya dengan tanda koma ( , ) dan ditutup dengan tanda kurung tutup ( } ). Setiap elemen pada tipe data dictionary dideklarasikan dengan format:</br></br>person = {'nama': 'John Doe', 'pekerjaan': 'Programmer'}</br>
print(person['nama'])</br>
print(person['pekerjaan'])</br></br>
</summary><table align="justify"><i>Output : </br>John Doe</br>
Programmer </i></table></details>

<details align="justify"> <summary><b>Tugas Praktek</b></br><i>sepatu = {"nama": "Sepatu Niko", "Harga": 150000, "diskon": 30000 }
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

<details align="justify"> <summary><b>Tugas Praktek</b></br>Dengan data yang aku miliki, aku bisa menghitung total harga jual dengan potongan harga dengan pajak sebesar 10% dari nilai jual.</br># Data yang dinyatakan ke dalam dictionary</br>
sepatu = {"nama": "Sepatu Niko", "harga": 150000, "diskon": 30000} </br>
baju = {"nama": "Baju Unikloh", "harga": 80000, "diskon": 8000} </br>
celana = {"nama": "Celana Lepis", "harga": 200000, "diskon": 60000}</br>
#Hitunglah harga masing-masing data setelah dikurangi diskon</br>
harga_sepatu = sepatu["harga"] - sepatu["diskon"] </br>
harga_baju = baju["harga"] - baju["diskon"]</br>
harga_celana = celana["harga"] - celana["diskon"]</br>
#Hitung harga total</br>
total_harga = harga_sepatu + harga_baju + harga_celana</br>
#Hitung harga kena pajak</br>
total_pajak = total_harga * 0.1</br>
#Cetak total_harga + total_pajak</br>
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

<details align="justify"> <summary><b>Tugas Praktek</b></br>Aku baru sadar kalau ternyata dengan struktur penulisan yang tepat, penulisan syntax dapat dipersingkat untuk menjadi lebih simpel. Kenapa tidak terpikirkan olehku ya? Harusnya aku tidak perlu mendeklarasikan variabel total_pajak dan aku bisa langsung menampung hasil perhitungan akhir saat mendeklarasikan variabel total_harga. Jadi, kodeku akan berjalan jika aku menambahkan setiap harga barang yang telah dipotong diskon sebelum menghitung pajak.</br></br>sepatu = { "nama" : "Sepatu Niko", "harga": 150000, "diskon": 30000 }</br>
baju = { "nama" : "Baju Unikloh", "harga": 80000, "diskon": 8000 }</br>
celana = { "nama" : "Celana Lepis", "harga": 200000, "diskon": 60000 }</br>
harga_sepatu = sepatu["harga"] - sepatu["diskon"]</br>
harga_baju = baju["harga"] - baju["diskon"]</br>
harga_celana = celana["harga"] - celana["diskon"]</br>
total_harga = (harga_sepatu + harga_baju + harga_celana) * 1.1</br>
print(total_harga)</br>
</summary><table align="justify"><i>Output : </br>365200.00000000006</i></table></details>


<details align="justify"> <summary><b>Tugas Praktek</b></br></br>tagihan_ke = 'Mr. Yoyo'</br>
warehousing = { 'harga_harian': 1000000, 'total_hari':15 } </br>
cleansing = { 'harga_harian': 1500000, 'total_hari':10 } </br>
integration = { 'harga_harian':2000000, 'total_hari':15 } </br>
transform = { 'harga_harian':2500000, 'total_hari':10 }</br>
sub_warehousing = warehousing['harga_harian']*warehousing['total_hari']</br>
sub_cleansing = cleansing['harga_harian']*cleansing['total_hari']</br>
sub_integration = integration['harga_harian']*integration['total_hari']</br>
sub_transform = transform['harga_harian']*transform['total_hari']</br>
total_harga = sub_warehousing+sub_cleansing+sub_integration+sub_transform</br>
print("Tagihan kepada:") </br>
print(tagihan_ke)</br>
print("Selamat pagi, anda harus membayar tagihan sebesar:") </br>
print(total_harga)</br></br>
</summary><table align="justify"><i>Output : </br>Tagihan kepada:</br>
Mr. Yoyo</br>
Selamat pagi, anda harus membayar tagihan sebesar:</br>
85000000</i></br></br>
<tr><td colspan="4">Tagihan untuk Mr. Yoyo</td></tr>

<tr><td>Nama Jasa</td><td>Harga per hari</td><td>Total hari</td><td>Subtotal</td></tr>
<tr><td>Data Warehousing</td><td>1000000</td><td>15</td><td>15000000</td></tr>
<tr><td>Data Cleansing</td><td>1500000</td><td>10</td><td>15000000</td></tr>
<tr><td>Data Integration</td><td>2000000</td><td>15</td><td>30000000</td></tr>
<tr><td>Data Transformation</td><td>2500000</td><td>10</td><td>25000000</td></tr>
<tr><td colspan="3">Total</td><td>85000000</td></tr>
</table></details>

<details align="justify"> <summary><b>Tugas Praktek</b></br><i>jam = 17</br>
tagihan_ke = 'Mr. Yoyo'</br>
warehousing = { 'harga_harian': 1000000, 'total_hari':15 } </br>
cleansing = { 'harga_harian': 1500000, 'total_hari':10 } </br>
integration = { 'harga_harian':2000000, 'total_hari':15 } </br>
transform = { 'harga_harian':2500000, 'total_hari':10 }</br>
sub_warehousing = warehousing['harga_harian']*warehousing['total_hari'] </br>
sub_cleansing = cleansing['harga_harian']*cleansing['total_hari'] </br>
sub_integration = integration['harga_harian']*integration['total_hari'] </br>
sub_transform = transform['harga_harian']*transform['total_hari']</br>
total_harga = sub_warehousing+sub_cleansing+sub_integration+sub_transform</br>
print("Tagihan kepada:")</br>
print(tagihan_ke)</br>
if jam>19:</br>
    print("Selamat malam, anda harus membayar tagihan sebesar:")</br>
elif jam>17:</br>
    print("Selamat sore, anda harus membayar tagihan sebesar:") </br>
elif jam > 12:</br>
    print("Selamat siang, anda harus membayar tagihan sebesar:")</br>
else:</br>
    print("Selamat pagi, anda harus membayar tagihan sebesar:") </br>
print(total_harga)</br></br></i>
</summary><table align="justify"><i>Output : </br>Tagihan kepada:</br>
Mr. Yoyo</br>
Selamat siang, anda harus membayar tagihan sebesar:</br>
85000000 </i></table></details>

<details align="justify"> <summary><b>Tugas Praktek</b></br>
  “Aksara, kantor kita akan merilis penawaran baru terkait jasa pembuatan data warehouse. Bisa tolong kembangkan kalkulatormu untuk menghitung tagihan pembayaran? Soalnya selama ini kita masih manual,” jelas Senja sembari memberikan contoh nota tagihan kantor. Aku belum mengiyakan karena sedikit ragu. Mengingat sebelumnya aku sempat salah. Tapi dalam hati aku berkata, pasti bisa! Kali ini aku harus mampu membuat kalkulator lebih rumit.</br>Solusi yang terlintas dalam bayanganku: Kalkulator ini harus dapat menghitung subtotal setiap jasa yang diambil dari kolom harga/ hari dan total hari dari setiap jasa. Ternyata Senja juga memikirkan hal yang sama dengan instruksinya yang sangat membantu.</br>tagihan_ke = 'Mr. Yoyo'</br>
warehousing = { 'harga_harian': 1000000, 'total_hari':15 } </br>
cleansing = { 'harga_harian': 1500000, 'total_hari':10 } </br>
integration = { 'harga_harian':2000000, 'total_hari':15 } </br>
transform = { 'harga_harian':2500000, 'total_hari':10 }</br>
sub_warehousing = warehousing['harga_harian']*warehousing['total_hari']</br>
sub_cleansing = cleansing['harga_harian']*cleansing['total_hari']</br>
sub_integration = integration['harga_harian']*integration['total_hari']</br>
sub_transform = transform['harga_harian']*transform['total_hari']</br>
total_harga = sub_warehousing+sub_cleansing+sub_integration+sub_transform</br>
print("Tagihan kepada:") </br>
print(tagihan_ke)</br>
print("Selamat pagi, anda harus membayar tagihan sebesar:") </br>
print(total_harga)</br></br>
</summary><table align="justify"><i>Output : </br>
Tagihan kepada:</br>
Mr. Yoyo</br>
Selamat pagi, anda harus membayar tagihan sebesar:</br>
85000000</i></table></details>

<p align="justify">Aku menunjukkan potongan kode dan hasil dari kalkulator yang telah aku buat ke Senja yang sudah berhasil menampilkan kalimat:</br><b>Selamat pagi, Anda harus membayar tagihan sebesar: </b></br>
Kulihat kedua alis Senja bertaut, ini pertanda kodeku pasti ada yang keliru.</br>
“Kalau kamu hanya memasukkan perintah ‘selamat pagi’ seakan kalau tagihan ini dikirim hanya saat pagi, padahal bisa kapan saja sesuai kebutuhan,” komentar Senja. Begini, jam pengiriman email kantor kita mulai dari 6 pagi sampai 9 malam.</br>
  Tolong masukkan variabel keterangan waktu tersebut di kodemu. Lalu, diatur dengan detail berikut:
<ol><li>Diatas jam 07 malam adalah salam 'selamat malam'</li>
<li>Diatas jam 05 sore adalah salam 'selamat sore'</li>
<li>Diatas jam 12 siang, adalah 'selamat siang'</li>
<li>dan selain itu 'selamat pagi'</li></ol>
<details align="justify"> <summary><b>Menampilkan suatu data dari baris dan kolom tertentu</b></br><i>
  jam = 17</br>
tagihan_ke = 'Mr. Yoyo'</br>
warehousing = { 'harga_harian': 1000000, 'total_hari':15 } </br>
cleansing = { 'harga_harian': 1500000, 'total_hari':10 } </br>
integration = { 'harga_harian':2000000, 'total_hari':15 } </br>
transform = { 'harga_harian':2500000, 'total_hari':10 }</br>
sub_warehousing = warehousing['harga_harian']*warehousing['total_hari'] </br>
sub_cleansing = cleansing['harga_harian']*cleansing['total_hari'] </br>
sub_integration = integration['harga_harian']*integration['total_hari'] </br>
sub_transform = transform['harga_harian']*transform['total_hari']</br>
total_harga = sub_warehousing+sub_cleansing+sub_integration+sub_transform</br>
print("Tagihan kepada:")</br>
print(tagihan_ke)</br>
if jam>19:</br>
    print("Selamat malam, anda harus membayar tagihan sebesar:")</br>
elif jam>17:</br>
    print("Selamat sore, anda harus membayar tagihan sebesar:") </br>
elif jam > 12:</br>
    print("Selamat siang, anda harus membayar tagihan sebesar:")</br>
else:</br>
    print("Selamat pagi, anda harus membayar tagihan sebesar:") </br>
print(total_harga)</br></br></i>
</summary><table align="justify"><i>Output : </br>Tagihan kepada:</br>
Mr. Yoyo</br>
Selamat siang, anda harus membayar tagihan sebesar:</br>
85000000</i></table></details>

<details align="justify"> <summary><b>Python while loops – Part 1</b></br> </br>#Tagihan
tagihan = [50000, 75000, 125000, 300000, 200000]</br>
#Tanpa menggunakan while loop</br>
total_tagihan = tagihan[0]+tagihan[1]+tagihan[2]+tagihan[3]+tagihan[4]</br>
print(total_tagihan)</br>
#Dengan menggunakan while loop</br>
i = 0 # sebuah variabel untuk mengakses setiap elemen tagihan satu per satu</br>
jumlah_tagihan = len(tagihan) # panjang (jumlah elemen dalam) list tagihan</br>
total_tagihan = 0 # mula-mula, set total_tagihan ke 0</br>
while i < jumlah_tagihan : # selama nilai i kurang dari jumlah_tagihan</br>
    total_tagihan += tagihan[i] # tambahkan tagihan[i] ke total_tagihan</br>
    i += 1 # tambahkan nilai i dengan 1 untuk memproses tagihan selanjutnya.</br>
print(total_tagihan)</br></br>
</summary><table align="justify"><i>Output : </br>750000</br>
750000</i></table></details>

<details align="justify"> <summary><b>Python while loops – Part 2</b></br>tagihan = [50000, 75000, -150000, 125000, 300000, -50000, 200000]</br>
i = 0</br>
jumlah_tagihan = len(tagihan)</br>
total_tagihan = 0</br>
while i < jumlah_tagihan:</br>
    #jika terdapat tagihan ke-i yang bernilai minus (di bawah nol),</br>
    #pengulangan akan dihentikan</br>
    if tagihan[i] < 0:</br>
        total_tagihan = -1</br>
        print("terdapat angka minus dalam tagihan, perhitungan dihentikan!")</br>
        break</br>
    total_tagihan += tagihan[i]</br>
    i += 1</br>
print(total_tagihan)</br></br>
</summary><table align="justify"><i>Output : </br>terdapat angka minus dalam tagihan, perhitungan dihentikan!</br>
-1</i></table></details>

<details align="justify"> <summary><b>Python while loops – Part 3</b></br>tagihan = [50000, 75000, -150000, 125000, 300000, -50000, 200000]</br>
i = 0</br>
jumlah_tagihan = len(tagihan)</br>
total_tagihan = 0</br>
while i < jumlah_tagihan:</br>
    # jika terdapat tagihan ke-i yang bernilai minus (di bawah nol),</br>
    # abaikan tagihan ke-i dan lanjutkan ke tagihan berikutnya</br>
    if tagihan[i] < 0:</br>
        i += 1</br>
        continue</br>
    total_tagihan += tagihan[i]</br>
    i += 1</br>
print(total_tagihan)</br>
</summary><table align="justify"><i>Output : </br>
750000</i></table></details>

<details align="justify"> <summary><b>Python for loops – Part 1</b></br>list_tagihan = [50000, 75000, -150000, 125000, 300000, -50000, 200000]</br>
total_tagihan = 0</br>
for tagihan in list_tagihan: # untuk setiap tagihan dalam list_tagihan</br>
    total_tagihan += tagihan# tambahkan tagihan ke total_tagihan</br>
print(total_tagihan)</br></br>
</summary><table align="justify"><i>Output : </br>550000</i></table></details>

<details align="justify"> <summary><b>Python for loops – Part 2</b></br>list_tagihan = [50000, 75000, -150000, 125000, 300000, -50000, 200000]</br>
total_tagihan = 0</br>
for tagihan in list_tagihan:</br>
    if tagihan < 0:</br>
        print("terdapat angka minus dalam tagihan, perhitungan dihentikan!")</br>
        break</br>
    total_tagihan += tagihan</br>
print(total_tagihan)</br></br>
</summary><table align="justify"><i>Output : </br>terdapat angka minus dalam tagihan, perhitungan dihentikan!</br>
125000</i></table></details>

<details align="justify"> <summary><b>Python for loops – Part 3</b></br>Ternyata, aku belajar bahwa ada istilah nested loops, yaitu pengulangan bersarang. Dengan nested loops, aku dapat mengkombinasikan (menambahkan) struktur pengulangan lain di dalamnya.  Aku mencoba potongan kode di bawah menggunakan live code editor:</br></br>list_daerah = ['Malang', 'Palembang', 'Medan']</br>
list_buah = ['Apel', 'Duku', 'Jeruk']</br>
for nama_daerah in list_daerah :</br>
    for nama_buah in list_buah:</br>
        print(nama_buah+" "+nama_daerah)</br></br>
</summary><table align="justify"><i>Output : </br>Apel Malang</br>
Duku Malang</br>
Jeruk Malang</br>
Apel Palembang</br>
Duku Palembang</br>
Jeruk Palembang</br>
Apel Medan</br>
Duku Medan</br>
Jeruk Medan</i></table></details>

<details align="justify"> <summary><b>Tugas Praktek</b></br>list_cash_flow = [</br>
2500000, 5000000, -1000000, -2500000, 5000000, 10000000,</br>
-5000000, 7500000, 10000000, -1500000, 25000000, -2500000</br>
]</br>
total_pengeluaran, total_pemasukan = 0, 0</br>
for dana in list_cash_flow: </br>
    if dana > 0:</br>
        total_pemasukan += dana </br>
    else:</br>
        total_pengeluaran += dana</br>
total_pengeluaran *= -1</br>
print(total_pengeluaran) </br>
print(total_pemasukan)</br></br>
</summary><table align="justify"><i>Output : </br>12500000</br>
65000000 </i></table></details>


<details align="justify"> <summary><b>Ekspedisi Pamanku</b></br>Aku menyambar ponsel di meja dan membuka pesan singkat dari paman tempo hari yang menjelaskan jika paman harus mengeluarkan uang sebesar 1,5 juta per mobil dalam sehari. Tapi, beliau selalu kebingungan total pengeluaran per bulan karena adanya aturan ganjil-genap yang membuat pengoperasian mobil yang berbeda. </br>“Kalau begitu, aku akan masukkan variabel jumlah_hari berisi jumlah hari dalam sebulan dan variabel list_plat_nomor berisi seluruh nomor plat mobil milik paman,” gumamku sendiri. Kalau seperti ini paman hanya perlu mengganti variabel jumlah_hari atau modifikasi variabel list_plat_nomor untuk melacak total pengeluaran paman selama sebulan. Ide Cemerlang!</br></br> #Data</br>
uang_jalan = 1500000</br>
jumlah_hari = 31</br>
list_plat_nomor = [8993, 2198, 2501, 2735, 3772, 4837, 9152]</br>
#Pengecekan kendaraan dengan nomor pelat ganjil atau genap </br>
#Deklarasikan kendaraan_genap dan kendaraan_ganjil = 0</br>
kendaraan_genap = 0 </br>
kendaraan_ganjil = 0</br>
for plat_nomor in list_plat_nomor:</br>
    if plat_nomor % 2 == 0:</br>
        kendaraan_genap += 1</br>
    else:</br>
        kendaraan_ganjil += 1</br>
#Total pengeluaran untuk kendaraan dengan nomor pelat ganjil </br>
#dan genap dalam 1 bulan</br>
i = 1</br>
total_pengeluaran = 0</br>
while i <= jumlah_hari:</br>
    if i % 2 == 0:</br>
        total_pengeluaran += (kendaraan_genap * uang_jalan)</br>
    else:</br>
        total_pengeluaran += (kendaraan_ganjil * uang_jalan)</br>
    i += 1</br>
#Cetak total pengeluaran</br>
print(total_pengeluaran)</br></br>
</summary><table align="justify"><i>Output : </br>163500000 </i></table></details>



<p align="justify"> <b>Hasil Belajarku</b></br>
Wah senangnya! Aku telah berhasil menyelesaikan pelajaran Python pertamaku, Python for Data Professional Beginner - Part 1.
Selain membabat habis materi dari Senja, aku berhasil menyelesaikan latihan, dan membantu Pamanku. Dari materi yang telah aku pelajari dan praktekkan, aku telah mempelajari:</p>
Alasan Python secara luas digunakan dalam komputasi saintifik, web, ranah data (data domain).<ol><li>
Konstruksi dari struktur bahasa pemrograman Python.</li>
<li>Teknik mempraktekkan penggunaan tipe data pada Python.</li>
<li>Teknik mempraktekkan penggunaan jenis-jenis operator pada Python.</li>
<li>Teknik mempraktekkan penggunaan pengkondisian untuk pengambilan keputusan dan perulangan pada Python.</li>
<li>Program Python untuk penyelesaian kasus bisnis sederhana.</li></ol>

