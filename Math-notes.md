Math-notes
-------------------
DOTNET
------
DOTNET - general purpose development platform, a framework
DOTNET uses C#, F# and visual basics
Has automatic memory management:
Managed heap, Garbage collector, avoiding memory leaks. everything build into DOTNET
Helps avoid invalid memory access, no broken pointers, no access to free memory, cannot access memory outside of array bounds
has a small cost, GC costs some performance

Garbage:
------
Memory needs to be cleaned up and reserved.
will start in the root and work its way through everything and flag the reachable data, then destroy what isnt reachable
finaly it calls the finalizer then compacting the memory to avoid fragmentation.
only works on reference types ( for obvious reasons)

Type safety:
-------
Every object is an instance of a specific type.
can only use valid operations
everything in DOTNET is an object originally.
DOTNET also has inheritance as a standard feature

Type inference
-----
they can induce the type of a variable from the expression on the right-hand-side.
its still typesafe however.
`var` keyword
needs to be done with right hand assignment always
if the type is very obvious, why not use it?


Delegates and lambdas
-----
Delegate is a type-safe function object, can assign methods to variables
lambda is short way of describing delegate instance.
they are basicaly functions

Generics
-----
coming from the DOTNET framework, used in lists and other generic functionality
<T>

ASYNC code
------
wrapped by task-objects
you can interact with them to cancel, pause, wait for completion etc.

LINQ
------
Language integrated query
set of functions making it readable with big sets of data
query style syntax

native interoperability
------
the OS has alot of functionality that differs between the platform
common language runtime (CLR) is useful thanks to not caring which platform we are on currently
could call OS specific calls aswell, never limited

Unsafe code
---------
you could call unsafe to write unsafe codeblocks if needed
`unsafe` keyword for creating these blocks

DOTNET-core
------
crossplatform implementation of DOTNET
cross platform server usage

DOTNET-framework
-------
has the DOTNET standard.
used primarily for applications for windows, creating forms and such

MONO / XAMARIN
--------
has only the minimal requirement (small footprint)
used for OSes on mobile platforms.
used by unity before but not anymore

UWP
------
used for touch enabled windows applications.
used by laptops, xbox etc.
microsoft crossplatform idea not that big anymore

DOTNET 5
------
the new release, unified platform with everything built in
desktop, web, cloud, mobile, gaming, IoT, AI
open-source on GitHub actually
combining everything previously existing as their own frameworks

DOTNET compilation
-------
there is diffrent CLR for each processor, C# converts into MSIL which is a intermediate language.
then through a C# install it converts MSIL into machine code with the help of DOTNET.
advantage is there is only ever need for a single build that will run everytwhere thanks to the dotnet install.
this is done ondemand during runtime.
has a low performance impact, thanks to being cached its not that bad

`Unity IL2CPP` - very strong doing convertions for diffrent platform using C++. Heavily optimized. can use up to date C# version
