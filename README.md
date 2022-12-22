# 1227050067_Mahesa-adlan-falah_IF
# Ujian Akhir Semester 
<br>Mata Kuliah 	: Dasar Programman
<br> Nama		: Mahesa Adlan Falah
<br>NIM		:	1227050067
<br>Jurusan		:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 


## Deskripsi Umum
Array adalah larik yang berisi kumpulan data dengan tipe serupa. Teknologi ini dapat digunakan untuk mempermudah penghitungan data karena mengelompokkan data-data berdasarkan kesamaannya. Untuk mempermudah pemahaman Anda mengenai hal ini, simak analogi berikut.

Misalnya, sebuah kereta terdiri dari beberapa gerbong yang menyimpan barang bawaan di dalamnya. Barang bawaan tersebut sama artinya dengan sekelompok data dengan tipe yang sama, sedangkan kereta tersebut adalah apa yang disebut dengan array itu sendiri. Kereta menampung barang-barang yang memiliki kesamaan nilai, sama seperti array yang memuat data-data dengan kemiripan tertentu
Array dua dimensi adalah sebutan untuk array yang penomoran index-nya menggunakan 2 buah angka.Analogi lain adalah matriks. Dalam matematika, matriks terdiri dari kolom dan baris. Kembali, untuk menentukan nilai dari sebuah matriks, kita harus sebut secara berpasangan seperti baris 1 kolom 1, atau baris 2 kolom 3, dst. Konsep seperti inilah yang menjadi dasar dari array 2 dimensi.

Untuk membuat array 2 dimensi di dalam bahasa C++, caranya tulis 2 kali tanda kurung siku setelah nama variabel, seperti contoh berikut:
int arr[2][2];
Pada UAS kali ini kami diminta membuat 2 buah program yaitu program pertama adalah membuat array 2 dimensi dengan baris ,kolom dan nilai nya di input sedangkan program ke dua digunakan untuk mencari nilai yanng dapat di bagi 3 7 5

## Source Code
      #include <iostream>
      using namespace std;

      int main()
      {
          cout << endl;
          cout << " Nama  : Mahesa adlan falah " << endl;
          cout << " NIM   : 1227050067 " << endl;
          cout << " Kelas : IF-B " << endl
               << endl;
          cout << " ===== Program Perkalian Matrix Ordo 2 ===== " << endl;
          cout << endl;


          double a[100][100];
          int i, j, k, baris, colom;

          cout << " - Masukan Baris = ";
          cin >> baris;
          cout << " - Masukan Colom = ";
          cin >> colom;
          cout << endl;

          cout << " Elemen matriks A : " << endl;
          for (i = 0; i < baris; i++)
          {
              for (j = 0; j < colom; j++)
              {
                  cout << " Elemen matrik A baris ke-" << i << " kolom ke-" << j << ": ";
                  cin >> a[i][j];
              }
          }

          cout << endl;

          cout << " Element matriks A adalah : " << endl;
          for (i = 0; i < baris; i++)
          {
              for (j = 0; j < colom; j++)
              {
                  cout << "    " << a[i][j];
              }
              cout << endl;
          }
          cout << endl;
          cout << " Matriks yang di balik :" << endl;
          for (i = 0; i < colom; i++)
          {
              // if ()
              for (j = 0; j < baris; j++)
              {
                  cout << "    " << a[j][i];
              }
              cout << endl;
          }
          cout << endl;
      }
      
      ##Output
      <img width="860" alt="image" src="https://user-images.githubusercontent.com/121010896/209143781-fc6ccca2-daeb-44f6-a582-431e085d74cf.png">
