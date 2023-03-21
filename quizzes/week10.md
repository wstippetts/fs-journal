# C# Fundamentals


**1.** What is the purpose of a `namespace`?
```
, a namespace is a way to group related code together and avoid naming conflicts between different parts of a program.
```
**2.** What is the difference between a `class` and a `struct`?
```
class is a reference type and struct is a value type
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
```
contructor
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
```
public
```
**6.** In the example what is `string` an indication of?
```
declaration of a string type 
```
**7.** In the example what is `abstract` preventing?
```
preventing Car class from being instanciated directly
```
**8.** In the example what is the purpose of `virtual`?
```
allows start method to be overridden by a derrived class
```
**9.** Name four access modifiers:
```
public, private, protected, internal, protected internal.
```
**10.** If you set a class or method to private, what can access it?
```
anything within the class.
```