# C-language
Projects from basics to advanced.
 C - basic syntax
```
   #include <stdio.h>
   #include <stdlib.h>
    #include <math.h>
    int main (){

    }
```

 printf function - <br>
   The printf function is used to output (print) text to the console. It's part of the standard input-output library (stdio.h).
  ```
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
```
New Line 

```
// we add \n at the end of code where we want line break.

#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}

```

 Decalaration function- <br>
 
 Declaration is when you declare a variable, specifying its type and name. It reserves memory space for the variable.
 ```
 int number;
float price;
char letter;
```
Here, number is an integer, price is a floating-point number(decimal), and letter is a character.
 
 Initialization funtion - <br>
 Initialization is assigning an initial value to a variable at the time of declaration.
```
 int number = 10;
float price = 36.5;
char letter = 'A';

```

 
 Output -<br>
 Output in C is generally done using the printf function to display information to the console.

 ```
#include <stdio.h>

int main() {
    int number = 25;
    printf("The number is %d", number);
    return 0;
}

```
 
 Input -<br>
 Input is getting data from the user. This is done using the scanf function.
 ```
#include <stdio.h>

int main() {
    int number;
    printf("Enter a number: ");
    scanf("%d", &number);
    printf("You entered: %d\n", number);
    return 0;
}

```
 
