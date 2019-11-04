# Tugas Praktikum 2
Disini akan membahas bagaimana mencari nilai terbesar dari 3 bilangan yang dimasukan.

**Diagram aliran data :**

![Flowchart_project.py](https://github.com/antonmartinus72/labspy02/blob/master/img/FChart_Anton.png)

### 1. Input Program

![input](https://github.com/antonmartinus72/labspy02/blob/master/img/1_Input.PNG)

Kode di atas adalah kode yang digunakan untuk menggunakan input dari user untuk data yang akan di proses nantinya. Data yang akan di prosen harus berbentuk integer (int). **Bil1**, **Bil2** dan **Bil3** adalah variabel yang digunakan untuk memasukan input.

### 2. Mencari 1 bilangan terbesar

![1Bil](https://github.com/antonmartinus72/labspy02/blob/master/img/2_Looking_f_1.PNG)

Kode di atas digunakan untuk mencari bilangan terbesar berdasarkan input yang dimasukan dengan statement if perbandingan :
Jika **Bilangan 1** lebih besar **(>)** dari **Bilangan 2 dan 3** maka Bilangan 1 akan di masukan ke dalam Variabel "**Terbesar**".  
Tapi jika kondisi diatas tidak terpenuhi, maka akan dilanjutkan ke statement **elif** dan seterusnya. Variabel **Nam_Bil** adalah variabel yang berisi **string** yang akan dicetak nanti, yang menandakan bahwa "**Bilangan 1**" adalah **string** yang dimiliki oleh variabel **Bilangan 1** atau bilangan dengan nilai terbesar. Dan nanti bilangan dan nilainya akan ditampilkan oleh statement print() di akhir baris pada file **project**.
**Output :**

![1Bil_Out](https://github.com/antonmartinus72/labspy02/blob/master/img/2_Looking_f_1_Output.PNG)

### 3. Mencari 2 bilangan terbesar
Mencari 2 Bilangan terbesar juga tidak berbeda jauh dengan mencari 1 Bilangan terbesar. Hanya saja statement yang digunakan adalah **elif**, meneruskan statement yang mencari 1 Bilangan terbesar.

![2Bil](https://github.com/antonmartinus72/labspy02/blob/master/img/3_Looking_f_2.PNG)

Perbandinganya adalah :
Jika **Bilangan 1** dan **Bilangan 2** bernilai **sama**, **dan Bilangan 1 tidak sama** dengan **Bilangan 3** maka Bilangan 1 dan Bilangan 2 akan di proses.
**Output :**

![2Bil_Out](https://github.com/antonmartinus72/labspy02/blob/master/img/3_Looking_f_2_Output.PNG)

### 3. Mencari Ketiga Bilangan Sama Besar

Saya menggunakan statement **elif** untuk mencari perbandingannya.

![3Bil](https://github.com/antonmartinus72/labspy02/blob/master/img/4_Looking_f_3.PNG)

Perbandinganya adalah :
Jika Bilangan 1, 2, 3 **sama dengan** Bilangan 1, 2, 3 maka data akan di proses yang menghasilkan output bilangan 1, 2, dan 3 **adalah yang terbesar** atau **sama**.
**Output :**

![3Bil_Out](https://github.com/antonmartinus72/labspy02/blob/master/img/4_Looking_f_3_Output.PNG)

### 4. Mencetak Output
![Print](https://github.com/antonmartinus72/labspy02/blob/master/img/5_Print_Output.PNG)
Perintah ini digunakan untuk **mencetak** hasil dari perbandingan di atas yang nilai perbandingannya sudah dideklarasikan kembali sehingga hasil yang sudah **final** di masukan dalam Variabel "**Nam_Bil**" untuk nama bilangan dan "**Terbesar**" untuk nilai bilangan dan dicetak menggunakan fungsi print.