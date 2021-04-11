# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
The namespace is used as a file name for a specific object in C#. They are used to name and identify various objects of differing kinds.
It is also useful when 'using' is declared before it so that it doesn't need to be typed every time for every object or class.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A class is a reference type and a struct is value type. Structs are stored on the heap and Classes are stored in the stack.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Using the "void" keyword in the return type for a method will tell the compiler that no return value is expected.
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
the type that is returned by Start()
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Abstract is preventing the object or method from becoming a sub-class of another class or method. It also signifies that the thing being modified has missing or incomplete implementation.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virtual will allow the value to be overriden by a derived class. This is an example of inheretence at work.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, Private, Virtural, Abstract
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```

```