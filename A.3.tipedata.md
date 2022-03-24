## **2.1	TIPE DATA**
Tipe data mendefinisikan metode penyimpanan untuk mereperesentasikan informasi dan cara informasi diinterprentasikan. Tipe data berkaitan erat dengan penyimpanan variabel di memori, karena tipe data variabel menentukan cara kompilator menginterpretasikan isi memori. Tipe data dalam Java dibagi 2 kategori; tipe data sederhana (primitive types) dan tipe data komposit (reference types).

### **2.1.1	Tipe data sederhana (primitive types)**
Bahasa pemrograman Java mendefinisikan delapan tipe data primitif. Mereka diantaranya adalah boolean (untuk bentuk logika), char (untuk bentuk tekstual), **byte**, **short**, **int**, **long** (integer), **double** and **float** (floating point).

a. Byte\
Tipe ini adalah tipe terkecil dari tipe integer. Tipe byte pada umumnya digunakan pada saat kita bekerja dengan sebuah data stream dari suatu file maupun jaringan, yaitu untuk keperluan proses membaca / menulis. Rentang nilai byte adalah `-128` s.d `127`.

Untuk mendeklarasikan variabel bertipe `byte`, perlu menggunakan kata kunci `byte`. Berikut ini contoh pendeklarasian tiga buah variabel bertipe `byte`.

    byte a;
    byte b, c = 20; 
    byte x = 121;

b.	Short\
Tipe ini merupakan tipe 16-bit yang berada pada rentang nilai `-32.768` s.d `32.767`. Untuk mendeklarasikan variabel bertipe `short`, perlu menggunakan kata kunci `short`. Berikut ini contoh pendeklarasian tiga buah variabel bertipe `short`.

    hort a;
    short b, c = 20; 
    short x = 121;

c.	Int\
Tipe ini adalah tipe yang paling banyak digunakan untuk merepresentasikan nilai integer. Karena dianggap paling efisien dibandingkan dengan tipe – tipe integer lainnya. Tipe data ini memiliki rentang nilai `-2147483648` s.d `2147483647`. Berikut ini contoh pendeklarasian tiga buah variabel bertipe `int`.
    
    int a;
    int b, c = 20; 
    int x = 32789;

d.	Long\
Long adalah tipe 64-bit bertanda. Tipe ini digunakan untuk kasus – kasus tertentu yang nilainya berada di luar rentang tipe `int`. Dengan kata lain, tipe `long` biasanya terpaksa digunakan

pada saat tipe int sudah tidak cukup lagi menampungnya. Berikut ini contoh pendeklarasian tiga buah variabel bertipe `long`.

    long a;
    int b, c = 24569845632; 
    int x = 327891345;

e.	Float\
Dispesifikasikan dengan kata kunci `float`, menggunakan 32-bit untuk menyimpan nilai. Ketelitian tunggal diolah lebih cepat pada sejumlah prosesor dan hanya mengambil ruang setengahnya, tetapi akan mulai tidak teliti jika nilai yang diolah terlalu besar atau terlalu kecil. Perhitungan sederhana  yang  membutuhkan  hanya  sedikit  ketelitian  pecahan,  misalkan perhitungan total suatu besaran, dimana kita hanya membutuhkan ketelitian sepersepuluh, dapat direperesentasikan dengan tepat, yaitu dengan `float`. Berikut contoh deklarasi variabel `float` :

    float a;
    float b, c = 0.56; 
    float x = 33.49;

f.	Double\
Dinyatakan dengan kata kunci double, menggunakan 64-bit untuk menyimpan nilai. Semua fungsi matematis transcendental, seperti sin, cos, dan sqrt, menghasilkan besaran double. Jika kita ingin menjaga ketelitian sampai banyak perulangan perhitungan atau mengolah bilangan besar, double adalah pilihan terbaik. Berikut contoh deklarasi variabel double :

    double luas;
    double pi = 3.1416; 
    double inch = 2.54;

Untuk lebih jelasnya lihat tabel dibawah ini:
Tabel 2.1 Daftar Tipe Data Sederhana

### **2.1.2	Tipe data komposit (reference types)**
Komposit, Tipe data komposit disusun dari tipe data sederhana atau tipe komposit lain yang telah ada. Tipe ini antara lain: `String`, `array`, `class`, dan `interface`.