# Basic Structure of a C# Program  

## Overview  
Every C# program follows a specific structure. Even for the simplest application, the program must contain at least one `Main` method, which serves as the entry point.

---

## Anatomy of a C# Program  

Below is an example of the basic structure of a C# program:  

```csharp
using System; // Importing namespaces

namespace MyFirstProgram // Namespace declaration
{
    class Program // Class declaration
    {
        static void Main(string[] args) // Main method: the entry point
        {
            Console.WriteLine("Hello, World!"); // Prints output to the console
        }
    }
}
```

### Explanation of the Components

1. **Namespaces**: Declared using the `using` keyword to import built-in or custom libraries.  
   Example: `using System;` provides access to console methods and other base utilities.  

2. **Namespace Declaration**: Defines a container for classes and other namespaces to avoid naming conflicts.  
   Example: `namespace MyFirstProgram`.  

3. **Class Declaration**: Classes are the blueprint for objects. A program typically contains one or more classes.  
   Example: `class Program`.  

4. **Main Method**: The `Main` method is the entry point of every C# application. It is where the program begins execution.  
   Example: `static void Main(string[] args)`.  

5. **Statements**: These are the actual instructions executed by the program.  
   Example: `Console.WriteLine("Hello, World!");` outputs text to the console.
