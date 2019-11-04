# Tugas Praktikum 2
Disini akan membahas bagaimana mencari nilai terbesar dari 3 bilangan yang dimasukan.

**Diagram aliran data :**

![Flowchart_project.py](Flowchart_Anton)

### 1. Input Program

![input](input)

Kode di atas adalah kode yang digunakan untuk menggunakan input dari user untuk data yang akan di proses nantinya. Data yang akan di prosen harus berbentuk integer (int). **Bil1**, **Bil2** dan **Bil3** adalah variabel yang digunakan untuk memasukan input.

### 2. Mencari 1 bilangan terbesar

![1Bil](1_Bilangan)

Kode di atas digunakan untuk mencari bilangan terbesar berdasarkan input yang dimasukan dengan statement if perbandingan :
Jika **Bilangan 1** lebih besar **(>)** dari **Bilangan 2 dan 3** maka Bilangan 1 akan di masukan ke dalam Variabel "**Terbesar**".  
Tapi jika kondisi diatas tidak terpenuhi, maka akan dilanjutkan ke statement **elif** dan seterusnya. Variabel **Nam_Bil** adalah variabel yang berisi **string** yang akan dicetak nanti, yang menandakan bahwa "**Bilangan 1**" adalah **string** yang dimiliki oleh variabel **Bilangan 1** atau bilangan dengan nilai terbesar. Dan nanti bilangan dan nilainya akan ditampilkan oleh statement print() di akhir baris pada file **project**.
**Output :**

![1Bil_Out](1Bil_Output)

### 3. Mencari 2 bilangan terbesar
Mencari 2 Bilangan terbesar juga tidak berbeda jauh dengan mencari 1 Bilangan terbesar. Hanya saja statement yang digunakan adalah **elif**, meneruskan statement yang mencari 1 Bilangan terbesar.

![2Bil](2%20Bilangan)

Perbandinganya adalah :
Jika **Bilangan 1** dan **Bilangan 2** bernilai **sama**, **dan Bilangan 1 tidak sama** dengan **Bilangan 3** maka Bilangan 1 dan Bilangan 2 akan di proses.
**Output :**

![2Bil_Out](3%20Bil%20output)

### 3. Mencari Ketiga Bilangan Sama Besar

Saya menggunakan statement **elif** dan fungsi **list** untuk perbandingannya, agak berbeda jika dibandingkan dengan mencari 1 dan 2 Bilangan terbesar.

![3Bil](3%20Bil)# Tugas Praktikum 2
Disini akan membahas bagaimana mencari nilai terbesar dari 3 bilangan yang dimasukan.

**Diagram aliran data :**

![Flowchart_project.py](Flowchart_Anton)

### 1. Input Program

![input](input)

Kode di atas adalah kode yang digunakan untuk menggunakan input dari user untuk data yang akan di proses nantinya. Data yang akan di prosen harus berbentuk integer (int). **Bil1**, **Bil2** dan **Bil3** adalah variabel yang digunakan untuk memasukan input.

### 2. Mencari 1 bilangan terbesar

![1Bil](1_Bilangan)

Kode di atas digunakan untuk mencari bilangan terbesar berdasarkan input yang dimasukan dengan statement if perbandingan :
Jika **Bilangan 1** lebih besar **(>)** dari **Bilangan 2 dan 3** maka Bilangan 1 akan di masukan ke dalam Variabel "**Terbesar**".  
Tapi jika kondisi diatas tidak terpenuhi, maka akan dilanjutkan ke statement **elif** dan seterusnya. Variabel **Nam_Bil** adalah variabel yang berisi **string** yang akan dicetak nanti, yang menandakan bahwa "**Bilangan 1**" adalah **string** yang dimiliki oleh variabel **Bilangan 1** atau bilangan dengan nilai terbesar. Dan nanti bilangan dan nilainya akan ditampilkan oleh statement print() di akhir baris pada file **project**.
**Output :**

![1Bil_Out](1Bil_Output)

### 3. Mencari 2 bilangan terbesar
Mencari 2 Bilangan terbesar juga tidak berbeda jauh dengan mencari 1 Bilangan terbesar. Hanya saja statement yang digunakan adalah **elif**, meneruskan statement yang mencari 1 Bilangan terbesar.

![2Bil](2%20Bilangan)

Perbandinganya adalah :
Jika **Bilangan 1** dan **Bilangan 2** bernilai **sama**, **dan Bilangan 1 tidak sama** dengan **Bilangan 3** maka Bilangan 1 dan Bilangan 2 akan di proses.
**Output :**

![2Bil_Out](3%20Bil%20output)

### 3. Mencari Ketiga Bilangan Sama Besar

Saya menggunakan statement **elif** untuk mencari ketiga bilangan jika sama besar.

![3Bil](3%20Bil)

Perbandinganya adalah :
Jika Bilangan 1, 2, 3 **sama dengan** Bilangan 1, 2, 3 maka data akan di proses yang menghasilkan output bilangan 1, 2, dan 3 **adalah yang terbesar** atau **sama**.
**Output :**

![3Bil_Out](3bil_Out)

### 4. Mencetak Output
![Print](Print_Output)
Perintah ini digunakan untuk **mencetak** hasil dari perbandingan di atas yang nilai perbandingannya sudah dideklarasikan kembali sehingga hasil yang sudah **final** di masukan dalam Variabel "**Nam_Bil**" untuk nama bilangan dan "**Terbesar**" untuk nilai bilangan dan dicetak menggunakan fungsi print.