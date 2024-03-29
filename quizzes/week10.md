# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
It is used for providing a way to keep one set of names separate from another. 
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structs are value types, or light versions of classes. Classes are reference types. 
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Void
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
Public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
An indication of the type of data being returned. 
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It prevents Car from being instantiated
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
It allows the Start() method to be overriden in the future so that it is reusable.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, Private, Protected, Internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
It can only be accessed by the code in the same class or struct
```