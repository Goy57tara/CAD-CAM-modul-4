# CAD-CAM-modul-4

## Materi Dasar CAD/CAM Menggunakan SolidWorks

### 1. Pengertian CAD/CAM

CAD (Computer Aided Design) adalah teknologi yang digunakan untuk membuat desain teknik menggunakan bantuan komputer. Dengan CAD, proses pembuatan gambar teknik menjadi lebih cepat, presisi, dan mudah untuk dimodifikasi.

CAM (Computer Aided Manufacturing) adalah teknologi yang digunakan untuk membantu proses manufaktur atau produksi menggunakan data desain yang dibuat dari CAD. Data dari CAD dapat digunakan untuk proses produksi seperti CNC machining, 3D printing, dan proses manufaktur lainnya.

Dalam praktiknya, CAD dan CAM saling terhubung. Desain yang dibuat pada software CAD dapat langsung digunakan dalam proses manufaktur melalui sistem CAM.

---

# 2. Pengenalan SolidWorks

SolidWorks merupakan salah satu software CAD yang banyak digunakan dalam bidang teknik, khususnya teknik mesin, manufaktur, dan otomasi. Software ini memungkinkan pengguna untuk membuat model 3D, melakukan perakitan komponen (assembly), serta membuat gambar teknik (drawing).

Beberapa fungsi utama SolidWorks antara lain:

* Membuat model 3D dari suatu komponen (Part)
* Menggabungkan beberapa komponen menjadi satu sistem (Assembly)
* Membuat gambar teknik 2D dari model 3D (Drawing)
* Menganalisis massa dan properti material
* Melakukan simulasi sederhana terhadap desain

---

# 3. Pemilihan Material pada SolidWorks

Material pada suatu desain sangat penting karena akan mempengaruhi beberapa hal seperti:

* Massa benda
* Kekuatan material
* Ketahanan terhadap suhu atau tekanan
* Biaya produksi

## Langkah memilih material

1. Buka model part yang telah dibuat.
2. Pada Feature Manager, klik kanan pada **Material <not specified>**.
3. Pilih **Edit Material**.
4. Pilih jenis material yang tersedia pada library, misalnya:

   * Steel
   * Aluminum
   * Plastic
   * Copper
5. Klik **Apply** lalu **Close**.

Setelah material dipilih, SolidWorks akan otomatis menyesuaikan properti seperti:

* Density (massa jenis)
* Yield strength
* Thermal properties

---

# 4. Menghitung Massa Menggunakan Evaluate

SolidWorks menyediakan fitur untuk menghitung massa, volume, dan pusat massa dari suatu model.

## Langkah menggunakan fitur Evaluate

1. Buka model part yang ingin dianalisis.
2. Klik menu **Evaluate** pada toolbar.
3. Pilih **Mass Properties**.
4. SolidWorks akan menampilkan informasi seperti:

   * Mass (massa)
   * Volume
   * Surface area
   * Center of mass
   * Density material

Perhitungan massa ini bergantung pada:

* Geometri model
* Material yang dipilih

Jika material belum ditentukan, maka nilai massa tidak akan akurat.

---

# 5. Menambahkan Variabel dengan Value Tertentu

Variabel digunakan untuk membuat desain yang lebih fleksibel. Dengan menggunakan variabel, ukuran model dapat diubah dengan mudah tanpa harus mengubah setiap dimensi secara manual.

Fitur yang digunakan adalah **Equations**.

## Langkah menambahkan variabel

1. Klik menu **Tools**.

2. Pilih **Equations**.

3. Pada jendela Equations, pilih **Add Global Variable**.

4. Masukkan nama variabel, misalnya:

   `Panjang = 100 mm`

5. Klik **OK**.

## Menggunakan variabel pada dimensi

1. Klik pada dimensi yang ingin diubah.

2. Pada kolom dimension value, ketik:

   `=Panjang`

3. Tekan Enter.

Dengan cara ini, jika nilai **Panjang** diubah pada menu Equations, maka semua dimensi yang menggunakan variabel tersebut akan otomatis ikut berubah.

---

# 6. Kesimpulan

CAD/CAM merupakan teknologi penting dalam dunia teknik modern karena memungkinkan proses desain dan manufaktur menjadi lebih efisien dan akurat. SolidWorks sebagai salah satu software CAD menyediakan berbagai fitur yang membantu proses perancangan, mulai dari pembuatan model 3D, pemilihan material, hingga analisis massa menggunakan fitur Evaluate.

Selain itu, penggunaan variabel melalui fitur Equations memungkinkan desain menjadi lebih fleksibel dan mudah dimodifikasi. Dengan memahami fitur-fitur dasar ini, pengguna dapat membuat desain teknik yang lebih efektif dan siap digunakan dalam proses produksi.

---

# Referensi

Groover, M. P. (2016). *Automation, Production Systems, and Computer-Integrated Manufacturing*. Pearson Education.

Planchard, D. (2018). *Engineering Design with SolidWorks*. SDC Publications.

Shih, R. H. (2019). *Parametric Modeling with SolidWorks*. SDC Publications.
