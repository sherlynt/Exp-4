# Experiment-4
AIM: 
To study and implement C++ bitwise operators.

SOFTWARE: Visual Studio Code

THEORY:
Bitwise AND (&):
Compares each bit of its operands. The result is 1 if both corresponding bits are 1; otherwise, it is 0.

Bitwise OR (|):
Compares each bit of its operands. The result is 1 if at least one of the corresponding bits is 1.

Bitwise XOR (^):
Compares each bit of its operands. The result is 1 if exactly one of the corresponding bits is 1; otherwise, it is 0.

Bitwise NOT (~):
Inverts all the bits of its operand (flips 0s to 1s and 1s to 0s).

Bitwise Left Shift (<<):
Shifts the bits of the left operand to the left by the number of positions specified by the right operand. The vacated bits on the right are filled with 0s.

Bitwise Right Shift (>>):
Shifts the bits of the left operand to the right by the number of positions specified by the right operand. The vacated bits on the left are filled with the sign bit (0 for positive numbers, 1 for negative numbers in signed types).

CODE:
```
#include<iostream>
using namespace std;

int main()
{
    int a,b;
    cout<<"enter the value of a ";
    cin>>a; 
    cout<<"enter the value of b: ";
    cin>>b; 
    cout<< "bitwise AND:"<<(a&b)<<endl;
    cout<< "bitwise OR:"<<(a|b)<<endl;
    cout<< "bitwise XOR:"<<(a^b)<<endl;
    cout<< "bitwise NOT:"<< (~a)<<endl;
    cout<< "bitwise LEFT SHIFT:"<<(a<<1)<<endl;
    cout<< "bitwise RIGHT SHIFT:"<< (a>>1)<<endl;

    return 0; 
}
```

O/P:




CONCLUSION:

By enabling operations to be carried out at the bit level, bitwise operators give users a strong tool for modifying individual data bits. When low-level control is needed and performance is crucial, they are very important. More compact and efficient code can result from knowing and using these operators, especially for system-level programming and applications that call for direct bit manipulation.
