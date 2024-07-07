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

// or

int main() {
  int num1, num2;
  int sum;
  cin>>num1>>num2;
  sum = solveMeFirst(num1,num2);
  cout<<sum;
  return 0;
}

