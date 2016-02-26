# MultiploDe4
Verifica si un numero es multiplo de 4
#include <iostream>
using namespace std;

int main() {
	int a;
	int b;
	b=4;
	cout<<"Ingrese cualquier numero";
	cin>> a;
	if (a%b ==0){
		cout<<a <<" es multiplo de 4";

	} else{
		cout<<"No es multiplo de 4";
	}
}

