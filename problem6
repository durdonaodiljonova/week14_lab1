#include <iostream>
using namespace std;

int main() {
    int number;
    cin >> number;
    try {
        if (number > 100) {
            throw number;
        }
        cout << "The number is within the acceptable range." << endl;
    } catch (int e) {
        cout << "Error: " << e << endl;
    }
    return 0;
}
