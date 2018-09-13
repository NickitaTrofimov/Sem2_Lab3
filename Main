#include "pch.h"
#include <iostream>


using namespace std;

int main()
{
	const unsigned int a = 10;
	const unsigned int b = 5;

	int array[a][b];

	int array1[b];

	for (int i = 0; i < a; i++) {
		for (int j = 0; j < b; j++) {
			array[i][j] = 0;
		}
	}
	cout << "Enter elements of array:" << endl;
	for (int i = 0; i < b; i++) {
		cin >> array1[i];
	}

	for (int i = 0; i < a; i++) {
		for (int j = 0; j < b; j++) {
			array[i][j] = array1[j];
		}
	}
	cout << "The lust one array: " << endl;
	for (int i = 0; i < a; i++) {
		for (int j = 0; j < b; j++) {
			cout << array[i][j] << " ";
		}
		cout << endl;
	}
}
