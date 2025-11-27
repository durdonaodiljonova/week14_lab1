#include <iostream>
#include <fstream>
using namespace std;

int main() {
    ifstream fin("data.txt");
    try{
        if(!fin.is_open())
            throw "File not found";
        int x;
        fin >>x;
        cout <<x;
    }
    catch(const char* msg){
        cout <<msg;
    }
    return 0;
}
