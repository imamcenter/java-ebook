## **2.3	KONSTANTA**
Konstanta sama seperti variabel, tetapi suatu konstanta merepresentasikan data permanen yang tidak dapat diubah. Suatu konstanta harus dideklarasikan dan diinisialisasikan dalam statement yang sama. Kata  `final` merupakan kata kunci (keyword) dalam  java  untuk  mendeklarasikan suatu konstanta. Bentuk umum deklarasi konstanta adalah sebagai berikut:

    final tipedata NAMA_KONSTANTA = nilai;

Contoh deklarasi konstanta:

    final double PI = 3.14159;
    final String KAMPUS = “Unindra”;

Praktikum
```java
/*
* Praktikum Tiga
* Mengetahui cara penggunaan variabel dan menampilkannya
* @author Teknik Informatika Unindra
*/

public class PraktikumTiga{
  public static void main(String[] args){
  //membuat variabel panjang
  int panjang;

  //membuat variabel lebar dan langsung inisialisasi nilai
  int lebar = 8;

  //membuat variabel luas
  double luas;

  panjang = 10;
  luas = panjang * lebar;

  //Menampilkan (mencetak) data pada console
  System.out.println(“Panjang = “ + panjang);
  System.out.println(“Lebar = “ + lebar);
  System.out.println(“Luas = “ + luas);
  }
}

```