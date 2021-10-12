# CSharp Cheat Sheet

:metal: :metal: :metal:
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
`\|\|` | Reads as OR | `this \|\| this` | [Logical operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#logical-operators)
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
`for` | Loop that goes for a determined amount of time. | `for(int i = 0, i<x, i++){//do stuff}` | [For Loop](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#14-for-loop)
iteration statement | The part of the loop that progresses | `i++` | [for loop](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#14-for-loop)
loop body | The executing part of the loop. | `{Do stuff}` | [for loop](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#14-for-loop)
loop | A type of code that iterates the same code multiple times. | `for` | [for loop](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#14-for-loop)
execution | What is about to be done. | `{}` | [for loop](https://github.com/marczaku/cs[harp-oop/blob/main/slides/003.3.5-console-basics-4.md#14-for-loop)
execution jump | When you iterate and jump back to the beginning | `{}` | [for loop](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#14-for-loop)
`break` | Used to interupt a loop and continue after the loop. | `break;` | [Break Continue](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#15-break--continue)
`continue` | Used to interupt the current iteration of a loop. | `continue;` | [break continue](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#15-break--continue)
`Array` | A collection of variables of the same type. | `string[] a = new string[3];` | [Array](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#16-arrays)
`int[]` | An array of ints. | `int[] number = new int[4];` | [Array](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#16-arrays)
Array Initialization | Creating an array. | `int[] name = new int[5];` | [Array](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#16-arrays)
Array Access for Assignment | You can assign an element in the array with a value. | `name[1] = 5;` | [Array](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#16-arrays)
Array Access for Reading | You can also read the value in an array. | `Console.WriteLine(name[1]);` | [Array](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#16-arrays)
`Array.Resize` | Function that creates a new array in a diffrent size using the data already in the array. | `Array.Resize(name, 5);`| [Array](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#16-arrays)
`Array.Length` | The total number of elements in the array. | name.Length;` | [Array](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#16-arrays)
`foreach` | A loop that will iterate once for every element in an array. | `foreach(var VARIABLE in Array name){//do something}` | [Array](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#16-arrays)
`2D-Array` | A 2 dimensional array which is an array made as a "grid". | `int[,] name = new int[3,3];` | [2D Arrays](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#17-2d-arrays)
2D-Array Initialization | How to create a 2D-array. | `int[,] name = new int[4,4];` | [2D Arrays](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#17-2d-arrays)
2D-Array Access for Assignment | To set the value you need to specify in bot axels where you want the value assigned. | `name[3,2] = 12` | [2D Arrays](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#17-2d-arrays)
2D-Array Access for Reading | Same for reading value. | `Console.WriteLine(name[2,4]);` | [2D Arrays](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#17-2d-arrays)
Jagged Arrays | An array of arrays, each element can have diffrent sizes. | `string [][] crazy = new strings[2][];` | [Jagged arrays](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#jagged-arrays)
Method | Used for grouping functionality and make it reusable. | `public void Method(){//do your stuff!}` | [Methods](https://github.com/marczaku/csharp-oop/blob/main/slides/003.4-console-methods.md#1-methods)
`void` | This is a type made for methods that will not return anything when using the method | `static void Main(){//do cool stuff}` | [Methods](https://github.com/marczaku/csharp-oop/blob/main/slides/003.4-console-methods.md#1-methods)
Return Type | Return type is defined in the method and will tell if the method returns anything and what it then return. | `void, int` | [Methods](https://github.com/marczaku/csharp-oop/blob/main/slides/003.4-console-methods.md#1-methods)
`()` | Parenthesis, this is where you put in the required variables in a method. | `static void Main(int age){//do cool stuff with age}` | [Methods](https://github.com/marczaku/csharp-oop/blob/main/slides/003.4-console-methods.md#1-methods)
Parameter | What you put into the method to give it values from outside its scope. | `(int age, string name)` | [Parameters](https://github.com/marczaku/csharp-oop/blob/main/slides/003.4-console-methods.md#2-parameters)
Argument | The instance of an parameter. | `(12)` | [Parameters](https://github.com/marczaku/csharp-oop/blob/main/slides/003.4-console-methods.md#2-parameters)
Parameter-List | You can have multiple parameters called in a method. | `(int age, string name, house home)` | [Multiple parameters](https://github.com/marczaku/csharp-oop/blob/main/slides/003.4-console-methods.md#multiple-parameters)
Named Arguments | Arguments can be named to increase understanding of the code. | `(age: 12)` | [Named arguments](https://github.com/marczaku/csharp-oop/blob/main/slides/003.4-console-methods.md#named-arguments)
Optional Arguments | You can create a default value for the argument | `(int i = 12)` | [Optional arguments](https://github.com/marczaku/csharp-oop/blob/main/slides/003.4-console-methods.md#optional-arguments)
Default Value | using optimal arguments will create a default value. | `(int i = 12) // 12 is default value.`  | [Optional arguments](https://github.com/marczaku/csharp-oop/blob/main/slides/003.4-console-methods.md#optional-arguments)
`return` | Keyword, if empty finishes the current method. else if a method as a returntype this keyword is used. | `return age;` | [Return type](https://github.com/marczaku/csharp-oop/blob/main/slides/003.4-console-methods.md#3-return-type)
Code Paths | All code must return a value, either void or anything else. | `{{{return;}return;}return;}` | [Code paths](https://github.com/marczaku/csharp-oop/blob/main/slides/003.4-console-methods.md#5-code-paths)
Method Overloading | Having more methods share the same name but differ in input or output. | `void add(int, int); void add(float, float)` | [Overloading](https://github.com/marczaku/csharp-oop/blob/main/slides/003.4-console-methods.md#6-overloading)
Object-Oriented Programming | Prgorams are divided into objects, these objects contain functions and data. | IDK | [Object oriented](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#3-object-oriented)
Data | Storage for information. | `int i = 5;` | [Object oriented](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#3-object-oriented)
Function | Functions take data in and returns data out, it's the practical use of a method. | `void add(5,5);` | [Object oriented](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#3-object-orienteds)
Structured Programming | Programs are divided into functions and data. | IDK | [Structured programming](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#2-structured-programming)
Objects | Instansiations of a class. | `Dog dog = new Dog();` | [classes and objects](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#4-classes--objects)
Instance Method | A method used in the current object. | `dog.bark();` | [Classes and objects](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#4-classes--objects)
Class | The template for our objects. | `public class Dog{}` | [classes and objects](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#4-classes--objects)
Type | Definition of what the class is. | `Dog dog();` | [Static class members](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#6-static-class-members)
`new` | Keyword for instantiating a new object. | ` Dog dog = new Dog;` | [Object oriented](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#3-object-oriented)
`class` | The keyword for creating a class. | `class` | [CLasses and objects](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#4-classes--objects)
Class Member | Each individual method or data in the class. | `Dog.bark();` | [Classes and objects](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#4-classes--objects)
Class Instance | The defined and useable object. | `Dog dog = new Dog();` | [Classes and objects](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#4-classes--objects)
Garbage Collector | The feature that takes care of destroying objects. | `GC` | [Classes and objects](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#4-classes--objects)
`null` | Keyword for no instance | `dog = null;` | [Classes and objects](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#4-classes--objects)
Invoke | Using a method in an instance of a class. | `dog.bark();` | [Classes and objects](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#4-classes--objects)
Field | A variable belonging to the specific object. | `private string name = "Gus";` | [Class members](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#5-class-members)
Static Class Member | Always part of the class and not the instance. | `static void Add();` | [Static class member](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#6-static-class-members)
Static Class | A completly static class, cannot be instantiated using `new` | `public static class Main{}` | [Static class member](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#6-static-class-members)
Global Access | Stuff that can be accessed from anywhere | `static int age;` | [Static class member](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#6-static-class-members)
Constructor | Describes how a new object can be created | `public dog(){}` | [Constructor](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#7-constructor)
Initial Class Values | Values that the object will be insta with. | `public Dog(name){}` | [Constructor](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#7-constructor)
Parameterless | A constructor with no parameters, used to great objects with no need for extra info. | `public Dog(){}` | [Constructor](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#7-constructor)
Default Contructor | The parameterless constructor. | `public Dog(){}` | [Constructor](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#7-constructor)
Finalizer | Executes when the object is destroyed. | `~Dog(){}` | [Finalizer](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#8-finalizer)
Object Destruction | The fenomen of destroying an instance. | `GC.Collect` | [Finalizer](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#8-finalizer)
`GC.Collect` | Syntax of how to manually call the garbage collector. | `GC.Collect();` | [Finalizer](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#8-finalizer)
Encapsulation | The process of making something accessable only in a certain scope. | `private int age;` | [Access modifiers](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#9-access-modifiers)
Access Modifier | Used to limit access to class members. | `private, protected` | [Access modifiers](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#9-access-modifiers)
`private` | Access modifier used to limit access to only the specific class. | `private void Main(){}` | [Access modifiers](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#9-access-modifiers)
`protected` | Access modifier used to limit access to only the class and Inheriting classes. | `protected void Main(){}` | [Access modifiers](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#9-access-modifiers)
`public` | Access modifier used to give free access globaly | `public int age;` | [Access modifiers](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#9-access-modifiers)
`internal` | Access modifier used to give global access within the project. | `internal int age;` | [Access modifiers](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#9-access-modifiers)
Class Member Access | Used to limit access to members within the class. | `private, public` | [Access modifiers](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes.md#9-access-modifiers)
Inheritance | Made for reusing code for classes sharing characteristics. | `inheriter : base ` | [Inheritance](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#2-inheritance)
Property | Used in C# to replace getter and setter methods. | `public int Something{set{//do something}get{//return something}}` | [Properties](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#1-properties)
Getter Method | A method used to collect a value | `GetSomething{return;}` | [Properties](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#1-properties)
Setter Method | A method to manipulate and set a value | `SetSomething{//do stuff}` | [Properties](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#1-properties)
Validation | Making sure that values that are handled are of a correct format. | `Math.min(int, int)` | [Properties](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#1-properties)
Processing | Manipulating variables into something else we need. | `Math.Add(int, int)` | [Properties](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#1-properties)
`get` | Syntax for collecting a value | `get{return this stuff}` | [Properties](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#1-properties)
`set` | Syntax for setting a value. | `set {//this is now this}` | [Properties](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#1-properties)
Expression Body Syntax | Certain syntax for get and set. | `get=> this; set=> this=this;` | [Properties](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#1-properties)
Auto Property | A property has a hidden field for values. | `public int Age{get; private set;}` | [Properties](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#1-properties)
Read-Only Property | Read only properties can never change their value, only collect it. | `public string Name{get;}` | [Properties](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#1-properties)
base-Class | A class containing all logic that is useable across multiple classes. | `Specialised class : base class` | [Inheritance](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#2-inheritance)
Inherit From | Where this class is inheriting its members. | `inheritance : base` | [Inheritance](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#2-inheritance)
Derived Class | The class that is inheriting. | `Derived : base` | [Inheritance](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#2-inheritance)
Child Class | Same as derived class. | `child : base` | [Inheritance](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#2-inheritance)
Parent Class | Same as the base class. inheriting from Syntax. | `child : Parent` | [Inheritance](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#2-inheritance)
`sealed` | Keyword used for making a class uninheritable. | `public sealed class Dog` | [Inheritance](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#2-inheritance)
Polymorphism | Using a derived class as a base class. | `Dog:Animal{Dog dog = new Animal();}` | [Polymorphism](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#3-polymorphism)
`as` | Keyword for transforming a base object into the child class.  | `Dog dog = animal as Dog;` | [Polymorphism](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#3-polymorphism)
`virtual` | Keyword for making methods overrideable by child class. | `public virtual void Bark(){}` | [Polymorphism](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#3-polymorphism)
`override` | Keyword for making a overriden version of a method. | `public override void Bark(pitch){}` | [Polymorphism](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#3-polymorphism)
`base` | Keyword for calling the base class. | `base.Bark();` | [Polymorphism](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#3-polymorphism)
Abstraction | The concept of creating a class as a blueprint that can't be instantiated. | `public abstract class Dog{}` | [Abstraction](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#4-abstraction)
`abstract` | Keyword used for creating an abstract class. | `abstract` | [Abstraction](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#4-abstraction)
Implementation | Classes implement an interface | IDK | [Interfaces](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-3.md#11-interfaces)
Composition | Class using another class as a field or property. | `public class Dude{public Fist fist{get; set;}}` | [Composition](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#5-composition)
"Composition over Inheritance" | A coding philosophy where rather use of components in a class then inheriting. | TRUE | [Composition](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-2.md#5-composition)
`const` | Makes the var unchangeable. | `const int players = 2;` | TBA
`magic numbers` | Presens of numbers in code that isnt explained. | `Math.Min(0,5);` | TBA
Interface | A class that is only a blueprint, other classes implementing this needs to have all members implemented. | `public class Practical : Interface` `IClassName` | [Interfaces](https://github.com/marczaku/csharp-oop/blob/main/slides/003.5-classes-3.md#11-interfaces)
`Value Types` | Value Types are types that when passed to another variable or as an argument to a method. They get copied. / Cloned. | `int a;` | [Discord](https://discord.com/channels/690251537926193166/887723893127774309/897447267613671434)
