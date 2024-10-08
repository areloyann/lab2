#include <iostream>
#define n 10
using namespace std;

void maxElement(int arr[n]) {
	for (int i = 0; i < n; i++) {
		for (int j = i + 1; j < n; j++) {
			if (arr[i] > arr[j]) {
				swap(arr[i], arr[j]);
			}
		}
	}
	for (int i = 0; i < n; i++) {
		cout << arr[i] << " ";
	}
}
	int multiplyMax(int arr[n]) {
		return arr[n - 1] * arr[n - 2];
	}

int main() {
	int arr[n] = { 8, 1, 9, 10, 2, 4, 3, 6, 5, 4 };
	maxElement(arr);
	cout << endl;
	cout << multiplyMax(arr);
	return 0;
}
