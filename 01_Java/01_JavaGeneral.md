## Java
1 Tell me about Java?
  Java is the high-level programming language. It is based on the principles of object-oriented programming that is platform independent and multithreaded. 

2 What do you like about Java?
  Skip


3 Why might someone not like Java?
  Skip



A **Scopes**
  4 Tell me the scopes in Java.
    In Java, scope defines where a certain variable or method is accessible in a program. Variables can be defined as having one of three types of scope:
    1) Class level scope (instance variables): any variable declared within a class is accessible by all methods in that class. Depending on its access modifier (ie. public or private), it can sometimes be accessed outside the class.
    2) Method level scope (local variables): any variable declared within a method, arguments included, is NOT accessible outside that method.
    3) Block scope (loop variables): any variable declared in a for loop condition is not accessible after the loop, unless you defined it beforehand.

  5 What is a scope?
    Scope defines where variables can be accessed or referenced.


  6 How do I make a variable of x scope?
    Class Scope - Variables are within the Class and available in all Methods and Blocks
    Method Scope -Variables declared directly inside a method are available anywhere in the method following the line of code in which they were declared. 
    Block Scope - A block of code refers to all of the code between curly braces {}. Variables declared inside blocks of code are only accessible by the code between the curly braces, which follows the line in which the variable was declared


- **Access Modifiers**
  7 What are Access Modifiers?
    Access modifiers in Java helps to restrict the scope of a class, constructor, variable, method, or data member.


  8 What are the Access Modifiers in Java?
    Private: The most restrictive modifier. It limits access to methods and variables to the class in which they are declared. private is chosen when there is no need to use certain methods or variables outside the class.

    Default: Allows access only from within the current package. If there is no specified access modifier, the method or variable will take on this one.

    Protected: Allows access to a method or variable only from within the current package, unless it is accessed through a child class outside of the package.

    Public: The least restrictive modifier. It allows access to a class, method or variable not only from within the class in which it is declared, but outside as well. This is most common access modifier.

  9 How are access modifiers different from scope?
     Scope modifiers changes the scope of a particular element or a method. For ex - static changes the scope of that of class and not of object.
    
    Access modifiers changes the access priviledges of a particular element or a method. For ex - private , public etc.


  10 What does the access modifier x do?
    Access modifiers changes the access priviledges of a particular element or a method. For ex - private , public etc.

- **Keywords**
  11 Tell me Keywords in Java?
    Reserved words that cannot be used as variables, methods, classes, or any other identifiers

  12 What does final keyword do?
  A non-access modifier used for classes, attributes and methods, which makes them non-changeable (impossible to inherit or override)
    - On variable
    - On a method
    - On a class

  13 What does static do?
  A non-access modifier used for methods and attributes. Static methods/attributes can be accessed without creating an object of a class

- **Class Structure**
  14 How do I inherit a class?
  To inherit from a class, use the extends keyword.

  15 How do I make a constructor?
  To create a constructor you declare a method with the same name as the class without a return type ie void. 

  16 How Do I implement an interface
  An interface is a completely "abstract class" that is used to group related methods with empty bodies:
  `interface Name {
  public void methodOne(); // interface method (does not have a body)
  public void methodTwo(); // interface method (does not have a body)
}`

  17 Override a method
  Overridden methods allow one to call methods from any derived class object without identifying the form of the modified super-class.

  18 What is an abstract class?
  Abstract class: is a restricted class that cannot be used to create objects (to access it, it must be inherited from another class).

  19 Abstract Class vs Interface?
  Abstract class can have abstract and non abstract methods. Doesn't support multiple inheritance. Can have final, non-final, static, and non static variables. Can extend another java cass and implement multiple java interfaces. Can have class members like private, protected ect. 

  Interface can have abstract, default and static methods. Supports multiple inheritence. Can only have static and final variables. Can't provide implementation of abstract class. Can only extend another interface. Members are public by default. 


  20 Variables in an abstract class or interface
    Abstract class can have final, non-final, static and non-static variables. Interface has only static and final variables.

  21 what is toString()?
   A built in method in Java that returns the value given to it in string format. 

  22 what is equals()?
    The equals() method compares two strings, and returns true if the strings are equal, and false if not.

  23 == vs equals()
  The main difference between the . equals() method and == operator is that one is a method, and the other is the operator. We can use == operators for reference comparison (address comparison) and . equals() method for content comparison.


- **Exception Handling**
  24 How does try catch finally work?
    The try block contains the application code which is expected to work in normal conditions. The optional catch block(s) follows the try block and MUST handle the checked exceptions thrown by try block as well as any possible unchecked exceptions. An optional finally block gives us a chance to run the code which we want to execute EVERYTIME a try-catch block is completed – either with errors or without any error.

  25 throws and throw keywords
  Throw Creates a custom error. Throws Indicates what exceptions may be thrown by a method

  26 Checked vs unchecked exceptions? - Give me an example of each
  In general, checked exceptions represent errors outside the control of the program. For example, the constructor of FileInputStream throws FileNotFoundException if the input file does not exist. If a program throws an unchecked exception, it reflects some error inside the program logic. For example, if we divide a number by 0, Java will throw ArithmeticException:

  27 Exception vs Error?
  Errors and exceptions are subclasses of the Throwable Java class. The Error class represents critical conditions that can not be caught and handled by the code of the program. On the other hand, the Exception class represents concerning conditions raised by the application itself; these can be caught and handled within the code to ensure that ​the application continues to run smoothly.
  
- **JVM Architecture**
  28 What is the main method?
  29 What is the method signature of the main method?
  30 Where does every Java Application start?
  31 Heap vs Stack memory?
  32 What is the JRE and JVM?
- **Java 8 features**
  33 What features were added in Java 8?
  34 What is a functional interface?
  35 What is a lambda?
  36 Where have you used lambdas?
    37 What is the Streams API
- **Threads**
  38 What is a thread?
  39 Why would you multi-thread?
  40 Have you used threading?
  41 How would you make a thread?