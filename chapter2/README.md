# Canonical "Hello World" program in Go

```go
package main

import "fmt"

// this is a comment

func main() {
	fmt.Println("Hello World")
}
```

## Lets understand the code line by line


```go
  package main
```

Every Go program must start with a package declaration. Packages are Go's way of organizing and reusing code. 

There are two types of Go programs: 
  * Executables
  * Libraries

```go
  import "fmt"
```

The import keyword is how we include code from other packages to use with our program

```go
  // this is a comment
```

The line that starts with ```//``` is known as a comment. Comments are ignored by the Go compiler.

Go supports two different styles of comments: 
```go
  // single line comment 
```

and 

```go
/*  
	multiline comments
	that continues on next line
*/
```

```go
  func main() {
    fmt.Println("Hello World")
  }
```

Functions are the building blocks of a Go program.

All functions start with the keyword func followed by the name of the function (main in this case), a list of zero or more “parameters” surrounded by parentheses, an optional return type and a “body” which is surrounded by curly braces.


```go
	fmt.Println("Hello World")
```

This statement is made of three components. First we access another function inside of the fmt package called Println. Then we create a new string that contains Hello World and invoke that function with the string as the argument.

To run this program simpley type following in the terminal from within the directory containing this program.

```
  go run hello-world.go
```

