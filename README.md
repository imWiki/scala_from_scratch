Scala Programming - Learning Notes
==

## Pre-Requisites
1. [Download Intellij](https://www.jetbrains.com/idea/download/)
2. [Download Java 1.8](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) 
3. [Setting up Intellij with Scala Plugin](https://www.javahelps.com/2018/12/setup-scala-on-intellij-idea.html)

# Part 1 - Basics
__Variables & Types of Scala__
```
Package = lectures.part1basics
File = Expressions.scala & ValuesVariableTypes.scala
```

`Exercise 1: What's the difference between "Hello, Scala" & println("Hello, Scala")`

__Functions__
```
Package = lectures.part1basics
File = Functions.scala
```

__Call By Value Vs Call By Name (Reference)__
```
Package = lectures.part1basics
File = CallByValVsName.scala
```

__Recursions__
```
Package = lectures.part1basics
File = Recusrions.scala
```

__Named Arguments__
```
Package = lectures.part1basics
File = NamedArguments.scala
```

`Exercise 2: Write function for below operations`
1. Fibonacci Series
2. Factorial
3. Finding a Prime number

__String Manipulations__
```
Package = lectures.part1basics
File = StringOperations.scala
```

`Exercise 3 (Recursive): Write function for below operations`
1. Fibonacci Series using tail recursion
2. Finding a Prime number using tail recursion
3. Concatenate a given string n times using recursion

# Part 2 - Object Oriented Concepts

__Classes & Methods__
```
Package = lectures.part2oops
File = ObjectOrientedBasics.scala
```

`Exercise 4 (Classes & Objects): Write below classes & methods`
1. A Writer or an Author class which takes three input parameters\
    a. firstName\
    b. lastName\
    c. yearOfBirth\
  and has methods as below,\
    a. fullName - prints fill name with init caps
2. A Novel class which takes three input parameters\
    a. bookName\
    b. yearOfRelease\
    c. Writer Object\
    and has methods as below,\
    a. authorAge - returns author age at the time of writing the book\
    b. isWrittenBy(authorObject) - returns true if author object or author name matches with current instance of novel\
    c. copy(newReleaseYear) - returns a new instance of Novel object with year as given input parameter for this method
3. Counter class with a number as parameter and following methods\
    a. increment & decrement method which creates new object of Counter class with parameter value inc or dec by 1\
    b. increment & decrement overloaded method with number as parameter, which again creates a new object of Counter class, but increments the class parameter with method parameter. 

__Method Notations & Syntactic Sugar__
```
Package = lectures.part2oops
File = MethodNotations.scala
```

`Exercise 5: Write below classes and methods as below`
1. Overload the + operator in Person class implemented in MethodNotations.scala which will return new Person Object with modified name or appended name
2. Add an age parameter to Person class & implement a unary_+ method that will increment the age by 1 in new object
3. Add a learns method that can be called with post fix notation. ex: vignesh learns scala
4. Overload apply method with an argument and return some string.

 __Objects__
```
Package = package lectures.part2oops
File = Objects.scala
```

 __Inheritance & Traits__
```
Package = package lectures.part2oops
File = Inheritance.scala & AbstractDataTypes.scala
```

`Exercise 6: Write a custom Linked List using abstract class and inheritance`\
File name = exercises.MyList.scala 

__Generics__
```
Package = package lectures.part2oops
File = Generics.scala
``` 

`Exercise 7: Modify the linked list written above using generics`\
File name = exercises.MyListGeneric.scala
