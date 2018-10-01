# Praktikum1
Latihan Soal Alogaritma!
Soal
1.Menghitung luas persegi panjang.
2.Mengetahui suatu bilangan ganjil/genap.
3.Mencari bilangan terbesar dari 2 bilangan yang di inputkan.

Jawaban
1. a.Masukan nilai panjang(P) persegi.
   b.Masukan nilai lebar(l) persegi.
   c.Masukan rumus luas(L)= panjang(P) X lebar(l)
   d.Tampilkan hasil luas persegi panjang.
Program Menggunakan C++  
#include <iostream.h>
#include <conio.h>main ()
{
int  P,l,L;
cout<<”\t Menghitung Luas Persegi Panjang \n”;
cout<<”Masukkan P     : “;
cin>>panjang;
cout<<”Masukkan l     : “;
cin>>lebar;
L=P * l;
cout<<”Luas Persegi Panjang = “<<L<<endl;}
   
2.a.Menginput sebuah bilangan 
  b.Jika bilangan yang di input bilangan ganjil maka akan tampil "Bilangan Ganjil"
  c.Jika bilangan yang di input bilangan genap maka akan tampil "Bilangan Genap"
Program Menggunakan C++  
#include <iostream.h>
using namespace std;
void main(){
int nilai;
cout << “masukkan nilai = “;
cin >> nilai;
if (nilai%2 == 0){
cout << “Bilangan Genap”;
} else {
cout << “Bilangan Ganjil”;}
return 0;
} 
  
3.a.Menginput 2 buah bilangan ke variabel a dan b.
  b.Jika bil(a) > bil(b), Maka mencetak hasil bil(a)
  c.Jika bil(a) < bil(b), Maka mencetak hasil bil(b)

Program Menggunakan C++  
#include <iostream.h>
#include <conio.h>main ()
{
int a,b;
cout<<"Masukkan nilai A : ";cin>>a;
cout<<"Masukkan nilai B : ";cin>>b;
if(a<b){
cout<<"B terbesar\n";
}else if(a>b){
cout<<"A terbesar\n";
}else
cout<<"Eror";}
