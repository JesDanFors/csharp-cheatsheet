# CSharp Cheat Sheet Template

Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`;`     | Used to separate statements from each other.| `int i = 5; i++; Console.WriteLine(i);` | [Script Execution](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#0-script-execution)
`//`    | Used for single-line comments              | `float multiplier = 0.01f; // % to float (e.g. 24% = 0.24)` | [Comments](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#single-line-comments)
Variable Initialization | When a value is assigned to a variable for the first time | `int a = 5;` | [Variables](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-initialization)
`dotnet new console -o project-name` | Used to initialize a new console project in the cmd. | `dotnet new console -o NimGame´ | [Console](https://github.com/marczaku/csharp-basics/blob/main/slides/003.1-hello-world.md)
Script Execution Order | The knowledge of in which order your code is executed, top to bottom | ´i= 1; console.WriteLine(i); i++; //Output = 1` | [Script execution](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#0-Script-Execution)
Formatting | How the code should be Structured | `Console.WriteLine("Hi")    ; //this is still fine.´ | [Script execution](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#0-Script-Execution)
`Console.WriteLine` | Calling the method WriteLine in class Console. Made for printing in console. | `Console.WriteLine("Hello world!")` | [Printing output](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#1-Printing-Output)
`Console.Write` | Calling the method Write in class Console. Made for printing in console. | `Console.Write("h"); Console.Write("i"); //prints hi` | [Printing output](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#1-Printing-Output)
Multi-Line Comment | Comments used on multiple lines. | /*    */ | [Multiline comments](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#multi-line-comments)
XML Documentation Comment | XML markup which can be used in your IDE to understand functions and code better. | `<summary> blah blah blah </summary> <param name="blah"> </param>` | [XML documentation](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#xml-documentation-comments)
Variable | Variable is a capsule made for keeping data, and also to change and manipulate the data. | `var hi = "hi";` | [Variables](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#3-variables)
Variable Declaration | Variables have a name and type. | `int age;` | [Variable declaration](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-declaration)
Variable Assignment | Variables can be assigned valid data. | `age = 12;`| [Variable assignment](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-assignment)
Uninitialized Variable | A variable which has no value assigned is Uninitialized. | `var age;` | [Variable instantiation](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-initialization)
`=` (Assignment Operator) | The = is used to give a variable it's value. | `age = 13;` | [Variable instantiation](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-initialization)
Scope | Scopes are used to encapsulate your code so it doesn't get to complex. | `{//your code here.}` | [Scope](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#31-scope)
Variable Scope | A variable can only be used inside the scope it is created in. | `{var age;}` | [Variable scope](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-scope)
`int` | Variable type for whole-numbers. | `int age = 12;` | [Basic data types](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`float` | Variable type for fractional numbers. | `float temperature = 12,5f;` | [Basic data types](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`double` | Variable type for more precise fractional numbers. | `double diameter = 5,004;` | [Basic data types](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`bool` | Variable type for true/false. | `bool wantCoffee = true;` | [Basic data types](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`char` | variable for a single character | `char Initial = 'A';` | [Basic data types](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`string` | variable for multiple characters. | `string message = "oh hello there";` | [Basic data types](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`byte` | Variable for smaller values. | `byte someByte = 0xF1;` | [Basic data types](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
Implicit Casting | ? | ? | ?
Explicit Casting | ? | ? | ?
Type Conversion | ? | ? | ?
`Convert.ToInt32` | ? | ? | ?
Operators | ? | ? | ?
Arithmetic Operators | ? | ? | ?
`+` | ? | ? | ?
`-` | ? | ? | ?
`*` | ? | ? | ?
`/` | ? | ? | ?
`%` | ? | ? | ?
`+=` | ? | ? | ?
`-=` | ? | ? | ?
`++` | ? | ? | ?
`--` | ? | ? | ?
Post-Increment `i++` | ? | ? | ?
Pre-Increment `++i` | ? | ? | ?
`System.Math` | ? | ? | ?
`static` | ? | ? | ?
`Math.Max` | ? | ? | ?
`Math.Min` | ? | ? | ?
`Math.Sqrt` | ? | ? | ?
`Math.Abs` | ? | ? | ?
`Math.Round` | ? | ? | ?
`Math.Floor` | ? | ? | ?
`Math.Ceiling` | ? | ? | ?
`Math.Clamp` | ? | ? | ?
`Math.Pow` | ? | ? | ?
`string.Length` | ? | ? | ?
`string.ToUpper` | ? | ? | ?
`string.+` | ? | ? | ?
`$"{}"` | ? | ? | ?
`string.[]` | ? | ? | ?
`string.IndexOf` | ? | ? | ?
`string.SubString(int)` | ? | ? | ?
`string.Substring(int, int)` | ? | ? | ?
`string.Replace` | ? | ? | ?
immutable | ? | ? | ?
Logical Operators | ? | ? | ?
`!` | ? | ? | ?
`&&` | ? | ? | ?
`||` | ? | ? | ?
Comparison Operators | ? | ? | ?
`>` | ? | ? | ?
`==` | ? | ? | ?
`!=` | ? | ? | ?
`||` | ? | ? | ?
`>=` | ? | ? | ?
`<=` | ? | ? | ?
`if` | ? | ? | ?
`else` | ? | ? | ?
`else if` | ? | ? | ?
`? :` | ? | ? | ?
Flow Control Statements | ? | ? | ?
`System.Random` | ? | ? | ?
pseudo-random | ? | ? | ?
seed | ? | ? | ?
`Random.Next(int, int)` | ? | ? | ?
`Random.Next()` | ? | ? | ?
`Random.NextDouble()` | ? | ? | ?
`Random.Next()` | ? | ? | ?
`while` | ? | ? | ?
bool-expression | ? | ? | ?
`do..while` | ? | ? | ?
`for` | ? | ? | ?
iteration statement | ? | ? | ?
loop body | ? | ? | ?
loop | ? | ? | ?
execution | ? | ? | ?
execution jump | ? | ? | ?
`break` | ? | ? | ?
`continue` | ? | ? | ?
`Array` | ? | ? | ?
`int[]` | ? | ? | ?
Array Initialization | ? | ? | ?
Array Access for Assignment | ? | ? | ?
Array Access for Reading | ? | ? | ?
`Array.Resize` | ? | ? | ?
`Array.Length` | ? | ? | ?
`foreach` | ? | ? | ?
`2D-Array` | ? | ? | ?
2D-Array Initialization | ? | ? | ?
2D-Array Access for Assignment | ? | ? | ?
2D-Array Access for Reading | ? | ? | ?
Jagged Arrays | ? | ? | ?
Method | ? | ? | ?
`void` | ? | ? | ?
Return Type | ? | ? | ?
`()` | ? | ? | ?
Parameter | ? | ? | ?
Argument | ? | ? | ?
Parameter | ? | ? | ?
Parameter-List | ? | ? | ?
Named Arguments | ? | ? | ?
Optional Arguments | ? | ? | ?
Default Value | ? | ? | ?
`return` | ? | ? | ?
Code Paths | ? | ? | ?
Method Overloading | ? | ? | ?
Object-Oriented Programming | ? | ? | ?
Data | ? | ? | ?
Function | ? | ? | ?
Structured Programming | ? | ? | ?
Objects | ? | ? | ?
Instance Method | ? | ? | ?
Class | ? | ? | ?
Type | ? | ? | ?
`class` | ? | ? | ?
`new` | ? | ? | ?
Class Member | ? | ? | ?
Class Instance | ? | ? | ?
Garbage Collector | ? | ? | ?
`null` | ? | ? | ?
Invoke | ? | ? | ?
Field | ? | ? | ?
Static Class Member | ? | ? | ?
Static Class | ? | ? | ?
Global Access | ? | ? | ?
Constructor | ? | ? | ?
Initial Class Values | ? | ? | ?
Parameterless | ? | ? | ?
Default Contructor | ? | ? | ?
Finalizer | ? | ? | ?
Object Destruction | ? | ? | ?
`GC.Collect` | ? | ? | ?
Encapsulation | ? | ? | ?
Access Modifier | ? | ? | ?
`private` | ? | ? | ?
`protected` | ? | ? | ?
`public` | ? | ? | ?
`internal` | ? | ? | ?
Class Member Access | ? | ? | ?
Inheritance | ? | ? | ?
Property | ? | ? | ?
Getter Method | ? | ? | ?
Setter Method | ? | ? | ?
Validation | ? | ? | ?
Processing | ? | ? | ?
`get` | ? | ? | ?
`set` | ? | ? | ?
Expression Body Syntax | ? | ? | ?
Auto Property | ? | ? | ?
Read-Only Property | ? | ? | ?
Auto Property | ? | ? | ?
base-Class | ? | ? | ?
Inherit From | ? | ? | ?
Derived Class | ? | ? | ?
Child Class | ? | ? | ?
Parent Class | ? | ? | ?
`sealed` | ? | ? | ?
Polymorphism | ? | ? | ?
`as` | ? | ? | ?
`virtual` | ? | ? | ?
`override` | ? | ? | ?
`base` | ? | ? | ?
Abstraction | ? | ? | ?
`abstract` | ? | ? | ?
Implementation | ? | ? | ?
Composition | ? | ? | ?
"Composition over Inheritance" | ? | ? | ?
