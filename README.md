# Age Classification Program

This repository contains a simple C++ program that classifies a person's age into different categories: Child, Teenager, Adult, and Senior.

## Code Description

The program prompts the user to enter their age and then classifies the age into one of the following categories based on the input:

- Child: 0-11 years
- Teenager: 12-18 years
- Adult: 19-63 years
- Senior: 64 years and above

## Code

```cpp
#include<iostream>
using namespace std;

int main()
{
    int age;
    cout << "Enter age: ";
    cin >> age;
    
    if ((age > 0) && (age < 12))
        cout << "\nChild";
    else if ((age > 12) && (age < 19))
        cout << "\nTeenager";
    else if ((age > 19) && (age < 64))
        cout << "\nAdult";
    else
        cout << "\nSenior";
}
