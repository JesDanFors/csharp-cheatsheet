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
Implicit Casting | Changing the type of a value to a proper type. | `int day = 5; double day = day;` | [Conversion](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#5-conversion)
Explicit Casting | Changing the type to a type that is less precise. | `double degree = 5,8; int ish = (int) degree; // ish will be 6.0` | [conversion](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#5-conversion)
Type Conversion | Some changes to a type must be checked so the don't create errors. | `int i = Convert.ToInt32("6");` | [Conversion](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#5-conversion)
`Convert.ToInt32` | A function used to convert something into a int. | `int i = Convert.ToInt32("6");` | [Conversion](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#5-conversion)
Operators | Operators are functions represented by symbols. | `!=, ==` | [Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
Arithmetic Operators | Operators used for mathematical operations. | `+=, /=` | [Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`+` | Addition between two numbers. | `+` | [Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`-` | Subtraction between two numbers. | `-` | [Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`*` | Multiplication between two numbers. | `*` | [Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`/` | Division between two numbers, | `/` | [Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`%` | Modulo between two numbers. This will do a division and return the amount that is left after possible divisions. | `%` | [Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`+=` | Adds and assign the value of a variable and a new value. | `int add += 5; //add has the value 5.` | [Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`-=` | Subtracts and assign the value of a variable and a new value. | `int sub += 2; // //sub value will be -2.` | [Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`++` | Adds one to an existing variable. | `int a = 1; a++; // the value of a is now 2.` | [Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`--` | Subtracts one from an existing variable. | `int s = 2; s--; //the value of s is now 1.` | [Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
Post-Increment `i++` | Since code is read left to right this will first read the value of i and then add 1 to it. | `i++` | [Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
Pre-Increment `++i` | This will instead add 1 to i then read the value! | `++i` | [Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`System.Math` | Math is a static class in the System namespace. | `System.Math.Max();` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`static` | Static means it cannot be instantiated | `static void Main(){}` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Max` | Function from System.Math used for finding the higest number. | `Math.Max(3,7);` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Min` | function used to finding the lowest number. | `Math.Min(3,7);` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Sqrt` | Function for finding the squareroot of a number. | `Math.Sqrt(12);` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Abs` | Function to find the absolute value of a number, always positive. | `Math.Abs(-12);` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Round` | Function to find the rounded number. | `Math.Round(3,5);` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Floor` | function to return the lower integer from a decimal number. | `Math.Floor(5,7);` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Ceiling` | Function to return the higer integer from a decimal number. | `Math.Ceiling(5,2);` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Clamp` | Function that returns the number which fits best within the clamps. | `Math.Clamp(value,min,max)` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Pow` | Function that returns the value to the power of another value. | `Math.Pow(value, power) // eg. 2,3 = 8 since 2^3 is = 8.` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`string.Length` | Returns the number of chars in a string. | `string.Length(name);` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`string.ToUpper` | Returns the same string but in upper case letters. | `string.ToUpper(name);` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`string.+` | Function to return a string that is combined with another string. | `"something "+"something else."` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`$"{}"` | Stringinterpolation, used for adding variables into the string. | `$"Hello my name is{name}."` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`string.[]` | Function for returning the specific char in a string. | `firstname[i]` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`string.IndexOf` | Function to return the index of first time a char is used in a string. | `firstname.IndexOf("e");` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`string.SubString(int)` | function that creates a new string at the starting point to the end of the old string. | `firstname.subString(4);` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`string.Substring(int, int)` | Creates a substring from an index to a specified length. | `firstname.subString(2,7);` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`string.Replace` | Replaces a specified char with another in the entire string. | `firstname.Replace(e,d);` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
immutable | This means something can never actually be changed, rather it creates a new copy that has been manipulated. | `string = string` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
Logical Operators | Operators used to implement logic. | `!, &&` | [Logical operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#logical-operators)
`!` | Reads as NOT. | `!true` | [Logical operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#logical-operators)
`&&` | Reads as AND | `this && this` | [Logical operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#logical-operators)
`||` | Reads as OR | `this || this` | [Logical operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#logical-operators)
Comparison Operators | Used to compare between two values. | `<,>,==` |   [Comparison operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#comparison-operators)
`>` | Reads as greater | `5>2` | [Comparison operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#comparison-operators)
`==` | Reads as equal | `5==5` | [Comparison operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#comparison-operators)
`!=` | Reads as NOTequal | `5!=7` | [Comparison operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#comparison-operators)
`>=` | Reads as greater or equal | `4>=3` | [Comparison operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#comparison-operators)
`<=` | reads as less or equal | `4<=7` | [Comparison operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#comparison-operators)
`if` | If a statement is true, this will execute. | `if(true){//do something}` | [If else](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#11-if--else)
`else` | when the if stement is false this will be done instead | `else{//do this other thing}` | [If else](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#11-if--else)
`else if` | Used for checking another statement and then if true execute the code | `else if(true){//do this then instead}` | [If else](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#11-if--else)
`? :` | Shortterm if else statement, does the same thing but with different syntax. | `condition ? then-value : else-value` | [If else](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#11-if--else)
Flow Control Statements | Code made for controlling the flow of operations. | `if, else, while` | [If else](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#11-if--else)
`System.Random` | Class containing functions to create random numbers. | `System.Random` | [Random](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#12-random)
pseudo-random | Something that seems random but is not. | `Random.Next();` | [Random](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#12-random)
seed | Used to create a recreateable rndom instance. | `Random(1234)` | [Random](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#12-random)
`Random.Next(int, int)` | Returns a random int between lower(inclusive) and higest(exclusive). | `Random.Next(0,11)` | [Random](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#12-random)
`Random.Next()` | Returns a random number between 0 and max value of int. | `Random.Next();` | [Random](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#12-random)
`Random.NextDouble()` | Returns a random double between 0 and 1(exclusive) | `random.NextDouble();` | [Random](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#12-random)
`while` | A Loop that continues aslong as it's statement is true. | `while(true){//do stuff.}` | [While](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.3-console-basics-3.md#13-while-loops)
bool-expression | An expression that will return a boolean value. | `(this thing is the same as this thing) = true;` | [While](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.3-console-basics-3.md#13-while-loops)
`do..while` | Same functionality as while loop, but will always run the code before checking the statement. | `do{//this cool stuff}while(true)` | [While](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.3-console-basics-3.md#13-while-loops)
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
