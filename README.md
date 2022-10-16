# Veronica-Amelya_Statistika-Bisnis_Programming
tugas 1 - tembakan robot
// NAMA		:Veronica Amelya Putri
// NRP		:2043221086
// Jurusan	:Statistika Bisnis

#include <iostream>
#include <cmath>
using namespace std;

int main() {
    int v0;
    int x;
    int loss;
    float vtan;
  
    cin >> v0;
    if (v0 >= 1 && v0 <= 10){
        v0 = v0 - 1;
        loss = 1;
    }else if (v0 >= 11 && v0 <= 20){
        v0 = v0 - 3;
        loss = 3;
    }else {
        v0 = v0 - 5;
        loss = 5;
    }
    x = pow(v0, 2) * sin(3.1415 / 2) / 10;
    vtan = sqrt(x * 10 / sin(3.1415 / 2)) + loss;
  	cout << x << " " << vtan << endl;
    return 0;
}
