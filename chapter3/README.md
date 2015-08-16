# Types in Go

Go comes with several built-in data types which we will now look at in more detail.

## Integers
	are numbers without a decimal component

Go's integer types are: ```uint8, uint16, uint32, uint64, int8, int16, int32``` and ```int64```.

```uint``` means “unsigned integer” while ```int``` means “signed integer” 

there two alias types: ```byte``` which is the same as ```uint8``` and ```rune``` which is the same as ```int32```.

 There are also 3 machine dependent integer types: ```uint, int``` and ```uintptr``` as their size depends on the type of architecture you are using.

## Floating Point Numbers

 Floating point numbers are numbers that contain a decimal component.
 Floating point numbers
   * are inexact.
   * have a certain size (32 bit or 64 bit)

#### In addition to numbers there are several other values which can be represented: “not a number” (```NaN```, for things like ```0/0```) and positive and negative infinity. (```+∞``` and ```−∞```)


Go has two floating point types: 
  * ```float32 // single precision```
  * ```float64 // double precision```
 
 And two types for representing complex numbers (numbers with imaginary parts): 
   * ```complex64```
   * ```complex128```


## Strings
	String is a sequence of characters with a definite length used to represent text. Go strings are made up of individual bytes, usually one for each character. 

String literals can be created using double quotes ```"Hello World"``` or back ticks ``` `Hello World` ```. The difference between these is that double quoted strings cannot contain newlines and they allow special escape sequences. 


## Booleans 

A boolean value is a special 1 bit integer type used to represent true and false (or on and off).
