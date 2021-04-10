# math-ll

![regex-ll](https://github.com/vs-123/math-ll/blob/main/math-ll-icon.png)

## Introduction:
**math-ll** is a lined-language that was designed for performing mathematical operations with ease.

## Quick Start:
Let's suppose, I want to perform the following mathematical operation `(√(3 + 6))!` and then show the output to the screen.
So I would create a file `main.ll` (the file name is arbitrary).

In `main.ll`, I would write the following code.
```
add 3
add 6
root 2
factorial
show
```
Output:
```
$ ./math-ll main.ll
6
```

## Commands
For now (since 10 April 2021), there are eight commands:
 - `add <number> info: Adds the given number to the stored number.`
 - `sub <number> info: Subtracts the given number from the stored number.`
 - `mul <number> info: Multiplys the given number by the stored number.`
 - `div <number> info: Divides the given number by the stored number.`
 - `pow <number> info: Raises the stored number to the power of the given number.`
 - `root <n> info: Stores the nth root of the stored number.`
 - `factorial info: Stores the factorial of the stored number, and takes no arguments.`
 - `show info: Shows the stored number, and takes no arguments.`
