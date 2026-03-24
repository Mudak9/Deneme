#include <iostream>
using namespace std;

int fibonacci(int n) {
    if (n <= 1) return n;
    return fibonacci(n - 1) + fibonacci(n - 2);
}

int main() {
    setlocale(LC_ALL,"turkish");
    int n;
    cout << "Kacinci Fibonacci elemanini istiyorsunuz? "; cin >> n;
    cout << "Sonuc: " << fibonacci(n) << endl;
    return 0;
}
