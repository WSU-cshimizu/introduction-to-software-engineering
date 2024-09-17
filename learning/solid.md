# S.O.L.I.D.
- S - Single-responsibility Principle
- O - Open-closed Principle
- L - Liskov Substitution Principle
- I - Interface Segregation Principle
- D - Dependency Inversion Principle

External reading:
- [The SOLID Principles of Software Design by Examples](https://team-coder.com/solid-principles/) by Robert Ecker
- [6 Principles Of Software Engineering That Every Engineer Should Know](https://medium.com/swlh/6-principles-of-software-engineering-that-every-developer-should-know-7868f362b633) by Joseph Pyram

## S - Single-responsibility Principle
- Every class is responsible for exactly one thing.
- This means it has only one reason to change. If you change anything in that class, it will affect only one particular behavior of the software.
- This makes the code more robust because there will be fewer side effects.
- If a class had two responsibilities and you changed anything, the risk would be high that you break the logic for the second behavior.

## O - Open-closed Principle
- The classes you use should be open for extension but closed for modification.
- This can be achieved with inheritance.
- You don't have to touch the class you want to extend if you create a subclass of it.
- The original class is closed for modification but you can add custom code to your subclass to add new behavior.

## L - Liskov Substitution Principle
- Assume we have a class B which is a subclass of A.
- If your program works with an object `a` of class A. You can replace it with an object `b` of class B without changing the behavior of the program.

## I - Interface Segregation Principle
- Classes should be as specialized as possible.
- You do not want any "god" classes that contain the _whole_ application logic.
- The source code should be **modular,** and every class should contain only the minimum necessary logic to achieve the desired behavior.
- The same goes for interfaces.
- Make small and specific interfaces so the client who implements them does not depend on methods it does not need.
- Instead of one class that can handle three special cases, it is better to have three classes, one for each special case.

## D - Dependency Inversion Principle
- Classes should not depend on concrete details of other classes.
- Even classes from a high domain level should not handle the specific details of components from a lower level.
- Both low and high level classes should depend on the same abstractions.
- To create specific behavior you can use techniques like inheritance or interfaces.