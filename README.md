# FirstRepo
---------------------------------------------
// 30.09.21
-------------------------------------------------

//zadanie 1
#include <iostream>
using namespace std;
int dodawanie(int a, int b) {
    return a + b;
};
int odejmowanie(int c, int d) {
    return c - d;
};
int mnożenie(int e, int f) {
    return e * f;
};
double dzielenie(double g, double h) {
    return g / h;
};
int main()
{
    cout << dodawanie(4, 5) << endl;
        cout << odejmowanie(6, 5) << endl;
        cout << mnożenie(8, 9) << endl;
        cout << dzielenie(3, 7) << endl; 
       
}

-----------------------------------------------------------------------
 //zadanie 2
----------------------------------------------------------------------
 // katrkówka pierwsza.cpp  ocena 3 
// zadeklaruj 1 wymiarową tablice o rozmiarze 10 niech za pomocą pętli wpisują sie wartości od 10 do 20 przy pomocy instrukcji warunkowej wyswietl wartości nieparzyste

#include <iostream>
using namespace std;
int main()
{

	int tab[10];

	for (int x = 10; x <= 20; x++) {
		cout << "podaj liczbe" << endl;
		cin >> tab[x];

	};


	for (int x = 10; x <= 20; x++) {
		if (tab[x] % 2 == 1) {
			cout << tab[x];
		}
	};
}
