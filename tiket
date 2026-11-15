#include <iostream>
using namespace std;
int pilihan,penumpang,harga,total;
string ulang, tujuan;
void to()
{
    do{
    cout<<"___________________________"<<endl;
    cout<<"     ---HARGA TIKET---"<<endl<<endl;
    cout<<"1. Malang-Surabaya: Rp35000"<<endl;
    cout<<"2. Malang-Pasuruan: Rp20000"<<endl;
    cout<<"3. Malang-Jombang : Rp25000"<<endl<<endl;

    cout<<"___________________________"<<endl;
    cout<<"Pilih tiket tujuan anda: ";
    cin>>pilihan;

    if (pilihan==1)
    {
        tujuan="Malang-Surabaya";
        harga=35000;
        cout<<"___________________________"<<endl;
        cout<<"Tujuan:    Malang-Surabaya"<<endl;
        cout<<"Harga:            Rp.35000"<<endl;
        cout<<"___________________________"<<endl;
    }
    else if (pilihan==2)
    {
        tujuan="Malang-Pasuruan";
        harga=20000;
        cout<<"___________________________"<<endl;
        cout<<"Tujuan:     Malang-Pasuruan"<<endl;
        cout<<"Harga:              Rp20000"<<endl;
        cout<<"___________________________"<<endl;
    }
    else if (pilihan==3)
    {
        tujuan="Malang-Jombang";
        harga=25000;
        cout<<"___________________________"<<endl;
        cout<<"Tujuan:     Malang-Jombang"<<endl;
        cout<<"Harga:             Rp25000"<<endl;
        cout<<"___________________________"<<endl;
    }
    else 
    {
        cout<<"_________________________"<<endl;
        cout<<"Pilihan tidak tersedia."<<endl;
        cout<<"_________________________"<<endl;
    }

    cout<<"Jumlah Penumpang: ";
    cin>>penumpang;
    total=harga*penumpang;
    cout<<"___________________________"<<endl;
    cout<<"       ---TIKET---"<<endl<<endl;
    cout<<"Tujuan:    ";
    cout<<tujuan<<endl;
    cout<<"Jumlah Penumpang:        ";
    cout<<penumpang<<endl;
    cout<<"Total Harga:     Rp ";
    cout<<total<<endl<<endl;
    cout<<"___________________________"<<endl;
    cout<<"apakah anda ingin mengulang? tekan y atau Y "<<endl;
    cin>>ulang;
    }
      while (ulang=="y"||ulang=="Y");  
}
int main() {
    to();
    system("pause");
    return 0;
}
