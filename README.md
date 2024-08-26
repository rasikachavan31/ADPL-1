# ADPL-1
Write a code for addition of 2 number ?
#include <iostream>
using namespace std;

int main() {
    int num1, num2, sum;//by this user can take numbers 

    cout << "Enter the first number: ";
    cin >> num1;

    cout << "Enter the second number: ";
    cin >> num2;

    sum = num1 + num2;

    cout << "The sum of " << num1 << " and " << num2 << " is " << sum << "." << endl;

    return 0;
}
