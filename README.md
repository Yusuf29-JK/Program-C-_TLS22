# ProgramC++_TLS22
Ahmad Yusuf Jauharul Khoiri-EULER
#include<iostream>

using namespace std;
int main()
{	int a, b, n;
	int jumlah=0;
	cout<<"||						Selamat Datang di					||"<<endl;
	cout<<"||				TOKO KLONTONG MANFAAT BAROKAH BAHAGIA DUNIA AKHIRAT			||"<<endl;
	cout<<endl;
	cout<<"Masukkan jumlah jenis barang yang dibeli : ";
	cin>>a;
	cout<<endl;
	for(int i=1;i<=a;i++)
	{	cout<<"Masukkan jenis barang : ";
		cin>>b;
		if(b==1)
		{	cout<<"Masukkan jumlah telur yang dibeli : ";
			cin>>n;
			jumlah = jumlah + 3000 * n;
			cout<<endl;
		}
		else if(b==2)
		{	cout<<"Masukkan jumlah gula yang dibeli : ";
			cin>>n;
			jumlah = jumlah + 9000 * n;
			cout<<endl;
		}
		else if(b==3)
		{	cout<<"Masukkan jumlah beras yang dibeli : ";
			cin>>n;
			jumlah = jumlah + 10000 * n;
			cout<<endl;
		}
		else
		{	cout<<"Masukkan jumlah minyak goreng yang dibeli : ";
			cin>>n;
			jumlah = jumlah + 14000 * n;
			cout<<endl;
		}
	}
	cout<<"Total biaya : Rp "<<jumlah<<endl;
	cout<<"||						Terima Kasih 						||"<<endl;
	cout<<"||													||"<<endl;
	
	return 0;
}
