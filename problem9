#include <iostream>
using namespace std;

void test(){
    throw "Error!";
}

main() {
    try{
        test();
    }
    catch(const char*){
        cout <<"Caught in main";
    }
    return 0;
}
