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
 int main() {
     
     int i, n;
     srand(time(0));
     printf("Enter how many pseudorandom numbers you want to generate");
     scanf("%d", &n);
     printf("Generating %d pseudorandom numbers between 0 and 99:\n", n);
     for (i = 0; i < n; i++) {
         int randomNumber = rand() % 100;
         printf("%d ", randomNumber);
         }
         printf("\n");
         return 0;
 }
```

# OUTPUT:

<img width="1528" height="1007" alt="Screenshot 2025-10-17 092754" src="https://github.com/user-attachments/assets/1eecfd30-34e7-450a-a47f-b83dc34f3df3" />

# RESULT:

The Implementation of Pseudorandom Number Generation Using Standard library is successfully done
