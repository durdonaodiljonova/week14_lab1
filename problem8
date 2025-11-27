#include <iostream>
#include <string>
using namespace std;

class MyError : public exception {
public:
    const char* what() const noexcept override {
        return "Odd number error.";
    }
};

int main() {
    int n;
    cin >> n;
    try {
        if (n % 2 != 0) {
            throw MyError();
        }
        cout << "Even" << endl;
    } catch (MyError& e) {
        cout << e.what() << " Input was: " << n << endl;
    }
    return 0;
}
