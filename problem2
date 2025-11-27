#include <iostream>
using namespace std;

int main() {
    int arr[5] = {10, 20, 30, 40, 50};
    int n;
    cin >> n;
    try {
        if (n < 0 || n > 4)
            throw "Index out of range!";

        cout << arr[n] << endl;
    }
    catch (const char* msg) {
        cout << msg << endl;
    }
    return 0;
}
