```
Question: 
What will be the output of the following pseudocode for a = 8, b = 8?

Integer funn(Integer a, Integer b)
if(a &8 b 8& a+b > 0 )
return a + funn a - 2, b - 2) + b
End if
return a ^ b
End function funn()
```
---
```
Solution:
Here's the C code:


#include <stdio.h>

int funn(int a, int b) {
    if (a > 0 && b > 0 && a + b > 0) {
        return a + funn(a - 2, b - 2) + b;
    }
    return a ^ b;
}

int main() {
    int a = 8, b = 8;
    int result = funn(a, b);
    printf("%d\n", result);
    return 0;
}


The output of this C code will be 40.
```
