#include <iostream>
using namespace std;

int main() {
    int x;
    cin >>x;
    try{
        if(x ==0) throw 0;
        if(x <0) throw "Negative number";
        cout <<"Valid";
    }
    catch(int){
        cout <<"Zero is not allowed";
    }
    catch(const char* msg) {
        cout <<msg;
    }
    return 0;
}
