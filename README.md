# Ex-6-Pseudorandom-Number-Generation

## Aim:
Implementation of Pseudorandom Number Generation Using Standard library

## Algorithm:
1.Start.

2.Import the random module from the Python standard library using import random.

3.Generate a random integer: Use random.randint(a, b) to generate a pseudorandom integer between the range a and b (inclusive).

4.Generate a random floating-point number: Use random.random() to generate a floating-point number between 0 and 1.

5.Generate a random number from a range: Use random.randrange(start, stop, step) to generate a number from a specified range with a step value.

6.Shuffle a list randomly: Create a list and use random.shuffle(list) to randomly shuffle the elements of the list.

7.Select a random element from the list: Use random.choice(list) to pick a random element from the list.

8.Display all the results.

9.End.

## PROGRAM:
```
import random

# Generate a pseudorandom integer between 1 and 100

random_integer = random.randint(1, 100)
print(f"Pseudorandom integer: {random_integer}")

# Generate a pseudorandom floating-point number between 0 and 1

random_float = random.random()
print(f"Pseudorandom float: {random_float}")

# Generate a pseudorandom number from a range with a step

random_range = random.randrange(0, 50, 5)
print(f"Pseudorandom number from range: {random_range}")

# Shuffle a list of items randomly

items = [1, 2, 3, 4, 5]
random.shuffle(items)
print(f"Shuffled list: {items}")

# Generate a pseudorandom choice from a list

random_choice = random.choice(items)
print(f"Pseudorandom choice from list: {random_choice}")
```
## OUTPUT:



## RESULT:
Thus, pseudorandom number generation using Python's random module was successfully implemented and tested.
