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



------------------------------------------------------------
		// zadanie 2.cpp : Ten plik zawiera funkcję „main”. W nim rozpoczyna się i kończy wykonywanie programu.
//

#include <iostream>
using namespace std;
void kwadrat(int a, int b) {
	cout << "kwadrat" << endl;
	cout << "pole" << endl;
	cout << a * a << endl;
	cout << "pobwod" << endl;
	cout << a * 4 << endl;
}
void trojkat_pk(int a, int b, int h) { 
	cout << "trojkat_pk" << endl;
	cout << "pole" << endl;
	cout << 0.5 * (a + h) << endl;
	cout << "obwod" << endl;
	int c = (a * a) + (b * b);
	cout << a + b + sqrt(c) << endl;
}
void trapez_r(int a, int b, int h) { 
	cout << "trapez_r" << endl;
	cout << "pole" << endl;
	cout << 0.5 * (a + b) * h << endl;
	cout << "obwod" << endl;
	int c = (a * a) + (b * b);
	cout << a + b + (sqrt(c) * 2) << endl;
}

int main()
{
	trapez_r(5, 2, 3);
	trojkat_pk(3, 6, 9);
		kwadrat(6, 2, 7);
}
------------------------------------------------------------
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
