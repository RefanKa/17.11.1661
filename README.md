# 17.11.1661#include<stdio.h>
#include<conio.h>
#include<iostream>

using namespace std;

class data
{
	public:
	int harga;
	int jumlah;
		
		void input()
	{
		cout<<"masukan harga: ";
		cin>>harga;
		cout<<"masukan jumlah barang: ";
		cin>>barang;
	};
	void akhir()
	{
		total=harga*jumlah;
	};
	
	float hasil()
	{
	return total;
	};
	
	private:
	float total;
};
int main()
{
	data makanan;
	makanan.input();
	makanan.akhir();
	cout<<"harganya adalah : "<<makanan.hasil();
}
	
