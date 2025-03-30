# G O  G O
Name: Mikael Quinto  
Language: **GO**

## Part I
- To get started with Go, we need to begin with the basics.
``` GO
package main

import "fmt"

func main() {
	fmt.Println("Hello World")
}
```
For basic variables, the following should be remembered:
- **int**: Stores integers (whole numbers), such as 123 or -123.
- **float32**: Stores floating-point numbers, with decimals, such as 19.99 or -19.99.
- **string**: Stores text, such as "Hello World." String values are enclosed in double quotes.
- **bool**: Stores values with two states: true or false.

There are two ways to create variables.
- var _______ -type-
- var _______ -type- = _______
- _______ := _______

The const keyword declares the variable as "constant", which means that it is unchangeable and read-only.
- const CONSTNAME type = value
this could be inside or outside of the **func**

Go has three functions to output text:

- **The Print()** function prints its arguments with their default format.
- **The Println()** print the function with a \n
- **The Printf()** function first formats its argument based on the given formatting verb and then prints them.

General Formatting Verbs fo Printf()
The following verbs can be used with all data types
|Verb	|Description				|
|%v	|Prints the value in the default format	|
|%#v	|Prints the value in Go-syntax format	|
|%T	|Prints the type of the value		|
|%%	|Prints the % sign			|
