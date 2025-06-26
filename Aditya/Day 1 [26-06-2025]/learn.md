---

# Introduction

- C# is a type-safe object oriented programmming language similar to java
- Specially designed to create dotnet based applications
-  Developed by Microsoft within the .net framework by their lead architect Anders Hejlsberg in 1999
- Flexible programming language
- highly expressive syntax
- used to create traditional windows client applications , xml web services, distributed components , client server applications, database applications, WPF, MVC, .NET Core, etc. 
- Interop process enables c# programs to do almost anything that a native cpp applications can do
 

- csc Filename.cs --> used for compiling our c# program
- Filename.exe --> used for executing the program
  
---

### Basic Program 

```c#
class hello
{
   public static void Main()
   {
          System.Console.WriteLine("Hello World");
   }
}
```

### Addition Program 

```c#
class hello
{
   public static void Main()
   {
          int a = 10, b = 20, c;
          c = a + b;
          System.Console.WriteLine("Result is " +c);
   }
}
```

---

# C# program Architecture 

![image](https://github.com/user-attachments/assets/1a34862b-b28f-4645-bfb0-0d56186c5dc9)

This diagram illustrates the compile time and run time relationships of c# source code files the .net framework class libraries, assemblies and the CLR. 

- CLR is the virtual machine of .net framework used for converting the native code to machine code
- After the code is compiled it is saved as a MSIL metadata
---

### Simple interest code

```c#
using System;
class SI
{
   public static void Main()
   {
          float p = 12000,r=2,t=2,si;
          si = (p*r*t)/100;
          Console.WriteLine("simple interest is {0}", si);
   }
}
```



