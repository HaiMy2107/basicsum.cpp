# basicsum.cpp
#include <iostream>
#include <cmath>
using namespace std;

int solveMeFirst(int a, int b) {
 // Hint: Type return a+b; below:
 return a + b;
}
int main() {
    int a, b;
    
    cout << "Please enter a number for a: ";
    cin >> a;
    
    cout << "Please enter a number for b: ";
    cin >> b;
    
    int sum = solveMeFirst(a,b);
    cout << "Sum: " << sum << endl;
  return 0;
}
