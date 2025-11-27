#include <iostream>
#include <string>
using namespace std;

int main() {
    string input;
    cin >> input;

    try {
        if (input.length() > 10) {
            throw "Too long!";
        } else {
            cout << input << endl;
        }
    } catch (const char* msg) {
        cout << msg << endl;
    }

    return 0;
}
