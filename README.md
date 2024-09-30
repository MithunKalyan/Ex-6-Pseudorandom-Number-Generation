# Ex-6-Pseudorandom-Number-Generation

## Aim:
To implement Pseudorandom Number Generation using the standard library functions in C.

## Algorithm:
1.Seed the random number generator using srand() to initialize it with a starting value.
2.Generate pseudorandom numbers using rand().
3.To ensure different results on each execution, seed srand() with a dynamic value like the current time (time(NULL)).
4.Use modulo operation to limit the range of generated numbers.

## Program:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    // Seed the random number generator with the current time
    srand(time(0));

    // Generate and print 5 pseudorandom numbers in the range [0, 99]
    printf("Pseudorandom numbers:\n");
    for (int i = 0; i < 5; i++) {
        int random_number = rand() % 100;  // Limit range to 0-99
        printf("%d ", random_number);
    }
    printf("\n");

    return 0;
}
```

## Output:
![exp6_output_crypt](https://github.com/user-attachments/assets/f259fdcc-2577-4b9d-a597-9b9df8489853)

## Result:
Thus, the pseudorandom number generation was successfully implemented using the standard library functions srand() and rand().
