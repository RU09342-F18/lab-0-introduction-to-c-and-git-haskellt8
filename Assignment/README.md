# math.c
By: Thomas Haskell

math.c includes the following math function:
```c
int math(int num1, int num2, char Operator)
```

This function supports multiple logical and mathematical operations.  The following are included:
* '\+' Add (num1 + num2)
* '\-' Subtract (num1 - num2)
* '\*' Multiply (num1 * num2)
* '/' Divide (num1 / num2)
* '%' Modulus (num1 % num2)
* '<' Left Shift (num1 << num2)
* '\>' Right Shift (num1 >> num2)
* '&' Bitwise AND (num1 & num2)
* '|' Bitwise OR (num1 | num2)
* '^' Bitwise XOR (num1 ^ num2)
* '~' Bitwise Inverse (~num1), num2 is ignored

Example uses:
```c
printf("1 + 2 = %d", math(1,2,'+'));
```
returns: "1 + 2 = 3"

```c
printf("7 or 2 = %d", math(7,2,'|'));
```
returns: "7 or 2 = 2"

