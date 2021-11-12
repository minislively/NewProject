#include<iostream>
using namespace std;
int arr[1001] = { 0, };
void A(int a, int b) {
	int k = 0, sum=0;
	for (int i = 1; i <= 1000; i++) {
		for (int j = 1; j <= i; j++) {
			arr[i] = i;
			k++;
			if (k >= a && k <= b)
				sum += arr[i];
		}
	}
	cout << sum;
}

int main() {
	int a, b;
	cin >> a >> b;
	A(a,b);
}
