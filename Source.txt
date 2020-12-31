#include<iostream>
#include<conio.h>
using namespace std;
void input(float[], int);
void main() {
	float a[999]; int b;
	cin >> b;


	input(a, b);



	_getch();
}
void input(float ary[], int b) {

	cout << "Enter a arry" << endl;
	for (int i = 0; i <= b; i++) {
		cin >> ary[i];
	}
