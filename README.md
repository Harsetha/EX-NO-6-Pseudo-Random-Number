# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
 {
    srand(time(0));  
    int random = rand(); 
    printf("Random number: %d\n", random); 
    return 0;
}

```
# OUTPUT:
![image](https://github.com/user-attachments/assets/70d2d611-1ad3-46c3-a072-5deba236e3fa)

# RESULT:
Thus the program for pseudorandom number generation successfully executed.
