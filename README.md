Praktikum1
No.1
#include <iostream>
#include <conio.h>
using namespace std;
int main()
{
int  P,l,L;
cout<<"\t Menghitung Luas Persegi Panjang \n";
cout<<"Masukkan Panjang  : ";
cin>>P;
cout<<"Masukkan Lebar    : ";
cin>>l;
L=P * l;
cout<<"Luas Persegi Panjang = "<<L<<endl;}

No.2
#include <iostream>
using namespace std;
int main() {
int nilai;
cout << "masukkan nilai = ";
cin >> nilai;
if (nilai%2 == 0){
cout << "Bilangan Genap";
} else {
cout << "Bilangan Ganjil";}
return 0;
}

No.3
#include <iostream>
#include <conio.h>
using namespace std;
int main()
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
