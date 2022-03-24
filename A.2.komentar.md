## **1.7	Komentar Pada Java**
Komentar adalah  catatan  yang  ditulis  pada  kode  dengan  tujuan  sebagai  bahan dokumentasi. Komentar membantu programmer untuk mengkomunikasikan dan memahami program. Komentar tersebut bukan bagian dari program (bukan statement) dan diabaikan oleh kompiler sehingga tidak mempengaruhi jalannya program.

Terdapat 3 cara penulisan komentar pada java:
1.	Menggunakan dua garis miring (//)
Semua teks setelah tanda // dianggap sebagai komentar. Contoh:
```java
// ini adalah komentar satu baris single line comment
```

2.	Menggunakan sepasang /* dan */
Cara ini digunakan untuk membuat komentar dalam beberapa baris.
Diawali dengan /* dan diakhiri dengan */, semua teks yang berada diantara dua tanda tersebut dianggap sebagai komentar.
Contoh:
```java
/* ini adalah contoh komentar yang ditulis dalam 2 baris atau juga disebut dengan multilines comments */
```

3.	Komentar khusus javadoc
Komentar javadoc khusus digunakan untuk men-generate dokumentasi HTML untuk program Java Anda. Anda dapat menciptakan komentar javadoc dengan  memulai baris dengan __/**__ dan mengakhirinya dengan __*/__.
```java
/**
*	Write a description of class MateriTiga here.
*	@author (your name)
*	@version (a version number or a date)
*/
```
Gambar 1.2 Penjelasan Class Sederhana

## **Praktikum**
```java
/**
* Mengetahui cara menuliskan komentar pada java
* @author Teknik Informatika Unindra
*/

public class PraktikumDua{
  public static void main(String[] args){
  // Menampilkan NPM (Komentar Satu Baris)
  System.out.println(“NPM : ”);

  /* Contoh Komentar Lainnya */
  System.out.println(“Nama : ”);

  /* Komentar
  ini lebih
  Dari satu baris */
  System.out.println(“Teknik Informatika”);
  }
}
```