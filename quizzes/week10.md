# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespace is a way of grouping into a class or structure.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Classes help us organize larger objects that we can extend and inherit. Whereas structs are primarily simpler without inheritance.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```

When using the DELETE method there is a 'void' that doesn't  make a return.
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
The start is a virtual method.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
The string is how the data comes through, not just numbers but multiple characters and symbols as well.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Abstract is preventing you from creating an object from this class directly.

```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Virtual is a property declaring that there is an inheritance class. 
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, Private, Internal, and protected.

```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only that specific method or class can access.
```